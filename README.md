# MUSDT Trading Strategy Backtest

This project contains a **Python backtesting framework** built in a Jupyter/Colab notebook.  
It focuses on simulating trading strategies for the **M/USDT pair** (and potentially other crypto pairs), using order book data and custom logic to evaluate profitability.

## 📌 Features
- Load and clean historical trade/order book data.
- Implement strategy logic (entry, exit, position sizing), optimized using optuna.
- Backtest strategy performance over historical periods.
- Compute key metrics:
  - Realized vs unrealized P&L
  - Average PnL per trade
  - Win rate
  - Drawdown
- Support for hyperparameter tuning (e.g., quantile thresholds, rolling windows) to optimize PnL.

## 📂 File Structure
- `Backtest_MUSDT_Alexandros.ipynb` → Main notebook with code, analysis, and plots.
- (Optional) `data/` → Directory where raw or cleaned order book data is stored.

## 🚀 Getting Started

### 1. Requirements
Install dependencies (if running locally):
```bash
pip install pandas numpy matplotlib optuna ccxt
