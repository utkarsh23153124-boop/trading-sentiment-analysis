# trading-sentiment-analysis

# Trading Sentiment Analysis 📊

## Overview
This project analyzes trading performance based on market sentiment (Fear vs Greed). 
The goal is to understand how trader behavior and profitability change with market sentiment.

---

## Datasets

1. **Fear & Greed Index**
   - Columns: Date, Classification (Fear / Greed)

2. **Historical Trading Data**
   - Fields include: Account, Execution Price, Size, Side, Closed PnL, Leverage, etc.

---

## Data Preparation

- Checked dataset shape (rows & columns)
- Handled missing values
- Checked duplicate rows and columns
- Cleaned column names
- Converted timestamps to datetime format
- Extracted daily date
- Merged datasets on date

---

## Key Metrics

- Daily PnL per account
- Win rate
- Average trade size
- Number of trades per day
- Long/Short ratio
- Leverage distribution

---

## Analysis

### 1. Performance vs Sentiment
- Compared average PnL across Fear and Greed periods
- Compared win rate across sentiment
- Analyzed drawdown (negative PnL)

### 2. Behavioral Changes
- Trade frequency by sentiment
- Average position size
- Long/Short bias
- Leverage usage

### 3. Trader Segmentation
- High vs Low leverage traders
- Frequent vs Infrequent traders
- Consistent vs Inconsistent traders

---

## Insights

- Traders perform better during Greed periods
- Trade frequency and position size increase during Greed
- High leverage traders show more volatile returns
- Consistent traders provide more stable performance

---

## Strategies

- Reduce leverage during Fear periods to manage risk
- Increase trade frequency during Greed with proper risk management
- Focus on consistent traders for stable returns

---

## Tools Used

- Python
- Pandas
- NumPy
- Matplotlib

---

## Conclusion

This project demonstrates how market sentiment influences trading behavior and performance, 
and how data-driven insights can help design better trading strategies.
