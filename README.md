# Stock Market Prediction Bot with LSTM Networks

This Python script utilizes Long Short-Term Memory (LSTM) networks to predict stock prices. It uses historical data to train the model and then attempts to predict future closing prices.

## Tech Stack

* Python
* NumPy
* Pandas
* Matplotlib
* Scikit-learn
* Keras


## Features

1. Download stock data from Yahoo Finance using yfinance
2. Preprocess data using MinMaxScaler
3. Train LSTM model to predict closing prices
4. Evaluate model performance with MAE, MAPE, MDAPE
5. Visualize predictions vs actual closing prices


## Deployment

To deploy this project:

- Clone this repository.
- Install required libraries: pip install numpy pandas matplotlib yfinance sklearn keras
- Update date_start with your desired start date for historical data.
- Run the script: python stock_market_prediction.py
- Enter the stock name you want to predict.
- The script will display the predicted closing price for the next day and visualize the historical data with predictions.


## Disclaimer

This script is for educational purposes only and should not be used for making financial decisions. Stock market predictions are inherently uncertain and this model does not guarantee accurate results.
