# Crypto Order Book Prediction

This project explores deep learning models for short-term cryptocurrency price movement prediction using order book and trade data.

## Project Overview

* Uses minute-level order book data (BTC/ETH/ADA).
* Extracts features such as returns, volatility, RSI, and moving averages.
* Creates sequential inputs for RNN/LSTM models.
* Performs binary classification (price up vs down).
* Includes a backtesting framework to evaluate strategies.

## Project Structure

```
├── data/                 # Raw order book CSV files (BTC, ETH, ADA)
├── notebooks/            # Kaggle/Colab notebooks
├── src/                  # Source code for feature engineering and models
├── results/              # Model outputs and backtest results
└── README.md             # Project description
```

## Getting Started

1. Clone the repository

   ```bash
   git clone https://github.com/<your-username>/crypto-order-book-prediction.git
   cd crypto-order-book-prediction
   ```
2. Install dependencies

   ```bash
   pip install -r requirements.txt
   ```
3. Run the notebooks or scripts for data preprocessing, training, and backtesting.

## Future Work

* Extend to multi-class prediction (strong up, neutral, strong down).
* Experiment with Transformer-based models.
* Incorporate more features such as depth imbalance and order flow.

---
