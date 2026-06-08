
# 🧠 Bitcoin Sentiment × Hyperliquid Trader Analysis

> Primetrade.ai Data Science Internship Assignment

## 📌 Objective

The objective of this project is to analyze the relationship between Bitcoin market sentiment (Fear & Greed Index) and trader performance on Hyperliquid.

Using historical trading data and sentiment data, the analysis aims to uncover hidden patterns, evaluate trader profitability under different market conditions, and generate actionable trading insights.

---

## 📂 Datasets Used

### 1. Bitcoin Fear & Greed Index
Contains daily Bitcoin market sentiment classifications.

Columns:
- Date
- Classification (Fear, Greed, Extreme Greed, Neutral)
- Value

### 2. Hyperliquid Historical Trader Data

Contains historical trading activity from Hyperliquid traders.

Key Columns:
- Account
- Symbol
- Side
- Execution Price
- Size
- ClosedPnL
- Leverage
- Timestamp

---

## 🔄 Data Processing

The following preprocessing steps were performed:

- Data cleaning and validation
- Timestamp conversion
- Date standardization
- Feature engineering
- Dataset merging using trade date
- Profitability calculations
- Sentiment-based analysis

---

## 📊 Analysis Performed

### Market Sentiment Analysis
- Fear
- Greed
- Extreme Greed
- Neutral

### Trader Performance Analysis
- Average PnL
- Win Rate
- Trade Volume
- Trade Direction

### Asset-Level Analysis
- BTC
- ETH
- SOL

### Position Size Analysis
- Small Trades
- Medium Trades
- Large Trades
- Whale Trades

### Time-Based Analysis
- Hourly Performance
- Monthly Trends
- Sentiment Transitions

---

# 🔑 Key Findings

## 1. SELL During Extreme Greed

- Win Rate: 90.6%
- Mean PnL: $176 per trade

Extreme optimism often resulted in profitable mean-reversion opportunities.

---

## 2. BUY During Fear

- Win Rate: 86.3%
- Mean PnL: $209 per trade

Fear-based market conditions provided strong buying opportunities.

---

## 3. SOL Outperformed Other Assets

During Greed periods:

- Mean PnL ≈ $890

Highest profitability among analyzed assets.

---

## 4. ETH Underperformed During Extreme Greed

- Mean PnL ≈ -$58.93

Suggesting weaker performance near market tops.

---

## 5. Sentiment Transitions Matter

Fear → Greed transition generated:

- Mean PnL ≈ $523

Highest profitability among transition categories.

---

## 6. Trade Size Impacts Profitability

| Trade Size | Mean PnL |
|------------|----------|
| < $100 | $2.26 |
| > $100,000 | $1,755 |

---

## 7. Best Trading Hours

### Highest Mean Profit
- 12:00 PM IST

### Highest Win Rate
- 7:00 AM IST

### Lowest Performance
- 11:00 PM IST

---

## 📈 Visualizations Included

The notebook contains:

- Mean PnL by Sentiment
- Win Rate by Trade Direction
- Trade Volume Distribution
- Monthly Profitability Trends
- Position Size Impact
- Coin × Sentiment Heatmap
- Hourly Win Rate Analysis
- Top Trader Performance
- Sentiment Transition Analysis

---

## ▶️ Running the Notebook

### Google Colab

1. Open `DS_TASK.ipynb`
2. Upload:
   - `fear_greed_index.csv`
   - `historical_data.csv`
3. Run all cells sequentially

Required Libraries:

```python
pandas
numpy
matplotlib
seaborn
```

---

## 📁 Project Files

```text
DS_TASK.ipynb
fear_greed_index.csv
historical_data.csv
README.md
```

---

##  Conclusion

The analysis demonstrates that Bitcoin market sentiment significantly influences trader profitability and behavior.

Key observations include:

- Buying during Fear generated strong returns.
- Selling during Extreme Greed achieved high win rates.
- SOL showed exceptional performance during bullish sentiment.
- Sentiment transition periods provided valuable trading signals.
- Position sizing had a major impact on profitability.

These findings suggest that incorporating sentiment indicators into trading strategies can improve decision-making and risk management.

---

## 👨‍💻 Author

Sornambal P

Submitted for:
Primetrade.ai Data Science Internship Assignment
