# Trader Behavior Insights – Market Sentiment vs Performance

## 📊 Project Overview

This project aims to explore the relationship between market sentiment (Fear/Greed Index) and trader performance using two datasets: the Bitcoin Market Sentiment Index and Historical Trader Data from Hyperliquid. This analysis is part of an assignment for the Junior Data Scientist role at PrimeTrade.ai.

The core objective is to derive actionable insights by:
- Understanding how trader behavior aligns with market sentiment.
- Identifying patterns in performance during different sentiment phases.
- Informing smarter trading strategies based on sentiment analysis.

---

## 📁 Datasets

### 1. **Bitcoin Market Sentiment Dataset**
- **Source**: Alternative.me (via Google Drive)
- **Columns**:
  - `Date`
  - `Classification` (Fear/Greed)

### 2. **Historical Trader Data from Hyperliquid**
- **Source**: Hyperliquid Trading Platform (via Google Drive)
- **Columns include**:
  - `account`, `symbol`, `execution_price`, `size`, `side`, `time`, 
  - `start_position`, `event`, `closedPnL`, `leverage`, etc.

---

## 🔍 Analysis & Methodology

### 1. **Data Preprocessing**
- Handled missing values and standardized column formats.
- Merged sentiment data with trader data using the timestamp (`Date` and `time` alignment).
- Converted sentiment into numerical encoding for analysis (`Fear`=0, `Greed`=1).

### 2. **Exploratory Data Analysis (EDA)**
- Distribution of trades across different sentiment classifications.
- Profitability comparison during Fear vs. Greed periods.
- Trader behavior metrics (PnL, leverage, position size) by sentiment.

### 3. **Statistical & Visual Insights**
- Correlation analysis between market sentiment and PnL.
- Time series trends in market sentiment vs aggregated trading performance.
- Box plots, histograms, and bar charts for visual storytelling.

---

## 🧠 Key Insights

- Traders showed more aggressive leverage usage during **Greed** periods.
- Higher volatility in **PnL outcomes** was observed during **Fear** periods.
- A small cohort of traders consistently outperformed regardless of sentiment.
- Sentiment-driven behavior has a noticeable impact on **trade timing and size**.

---

