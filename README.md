# Quantitative Multi-Asset Allocation Framework

This project implements a systematic investment strategy comparing the **Momentum Strategy** (based on Jegadeesh and Titman) against a classic **Buy & Hold** approach within the US sector universe.

## 📊 Project Overview
The goal of this framework is to backtest whether a rule-based momentum approach can outperform a passive investment strategy. It covers the entire data pipeline, from fetching historical market data to calculating performance metrics.

## 🛠 Key Features
* **Data Retrieval:** Automated fetching of financial data via `yfinance`.
* **Strategy Implementation:** Momentum-based sector rotation logic.
* **Risk Analysis:** Calculation of Risk via Drawdowns.
* **Visualization:** Performance curves and heatmaps using `seaborn` and `matplotlib`.

## 💻 Tech Stack
* **Python** (Jupyter Notebook)
* **Pandas & NumPy** for data manipulation
* **YFinance** for market data
* **Matplotlib & Seaborn** for financial visualization
