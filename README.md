# Financial Market Analysis Using Machine Learning

# 1. Stock Price Prediction using LSTM and Technical Indicators

This project predicts stock prices by combining a Long Short-Term Memory (LSTM) network with technical indicators. Two main parts are included:

**Part 1: LSTM Stock Price Prediction**

- Focuses on building and evaluating an LSTM model to predict the closing price of Google (GOOG) stock.
- Visualizes historical data, including moving averages, to gain insights into price trends.
- Evaluates model performance using RMSE, R-squared, and adjusted R-squared metrics.

**Part 2: Stock Trading Strategy using LSTM and Technical Indicators**

- Develops a comprehensive stock trading strategy using LSTM predictions along with technical indicators like Moving Average (MA), Relative Strength Index (RSI), and Bollinger Bands. 
- Includes functions for:
    - Fetching stock data for multiple tickers.
    - Calculating technical indicators.
    - Generating buy/sell signals based on combined indicators and LSTM predictions.
    - Calculating position size based on risk management.
    - Backtesting the strategy and optimizing parameters using Bayesian Optimization.
- Provides a usage example and detailed explanations of the output and generated plots. 

## Requirements

- Python 3.7+
- Libraries: `yfinance`, `pandas`, `numpy`, `matplotlib`, `sklearn`, `tensorflow`, `ta`, `bayesian-optimization`

## Usage

1. Install the required libraries.
2. Run the Jupyter notebook `stock_prediction_lstm.ipynb`.


# 2. Stock Price Prediction using LightGBM

This project demonstrates stock price prediction using the LightGBM gradient boosting framework. The model predicts the open-to-close percentage change of Japanese stocks listed in the TOPIX 100 index, considering various technical indicators and the previous day's performance of the S&P 500 index.

## Features

- Data Acquisition: Downloads historical stock data for TOPIX 100 companies and the S&P 500 index using the `yfinance` library.
- Feature Engineering: Calculates technical indicators like moving averages, RSI, and moving average convergence divergence (MACD).
- Model Building: Utilizes LightGBM, a gradient boosting framework known for its speed and accuracy, to build the prediction model.
- Feature Importance Analysis: Identifies and visualizes the most influential features contributing to the model's predictions.
- Backtesting: Simulates trading based on the model's predictions and calculates cumulative returns.

## Requirements

- Python 3.7+
- Libraries: `yfinance`, `japanize_matplotlib`, `seaborn`, `tqdm`, `lightgbm`

## Usage

1. Install the required libraries.
2. Run the Jupyter notebook `stock_prediction_lightgbm.ipynb`.


# Disclaimer

This project is for educational and informational purposes only and should not be considered financial advice. Trading in the stock market involves risk, and past performance is not indicative of future results.
We do not guarantee any benefits when using it for actual financial market data analysis.

We have taken every precaution to ensure the accuracy of the published code, but we do not guarantee its content.

Any activities using the information in this repository are at your own risk. The authors and related parties assume no responsibility for any disadvantages or other issues arising from the use of the contents of this repository.

