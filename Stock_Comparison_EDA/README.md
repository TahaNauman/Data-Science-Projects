# Stock Comparison EDA

This project performs an **Exploratory Data Analysis (EDA)** comparing the stock performance of **Apple (AAPL)** and **Microsoft (MSFT)** over a selected time period. The analysis focuses on price trends, daily returns, return distributions, correlations, and cumulative returns to gain insights into the comparative performance of these two tech giants.

---

## Dataset

- Source: Yahoo Finance (via Python `yfinance` library)
- Stocks: AAPL, MSFT
- Time period: 2020-01-01 to 2026-01-01
- Data includes: Open, High, Low, Close, Adjusted Close, Volume

---

## Libraries Used

```python
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns
import yfinance as yf
