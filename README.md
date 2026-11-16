# Institutional Options Backtest Dashboard

A professional-grade options backtesting engine built using Python and Streamlit, designed to simulate institutional-level ATM straddle strategies with realistic cost modeling and advanced analytics.

## Features

- **ATM Straddle / Volatility Mean-Reversion Strategy**
- Realistic Indian brokerage cost model
- 5-minute time-frame backtesting
- Performance metrics (Sharpe, Drawdown, Win Rate)
- Interactive Streamlit dashboard
- Trade-level analytics

## Tech Stack

- Python
- Pandas
- NumPy
- Plotly
- Streamlit

## Strategy Logic

The system:

- Buys ATM straddles when IV percentile is low (cheap volatility)
- Filters entries using spot momentum and EMA trend strength
- Implements stop loss, take profit, IV-based exit, and time-based exit
- Models realistic slippage and brokerage costs

## How to Run

```bash
pip install -r requirements.txt
streamlit run gmain.py
```
