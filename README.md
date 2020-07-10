# S&P 500 Time-Series Forecasting
S&amp;P500 Stock Index Movement Forecastor with various Statistical and Machine Learning Models

## Description
The S&P 500 is a stock market index that measures the stock performance of 500 large companies listed on stock exchanges in the United States. It is considered to be one of the best representations of the U.S. stock market.

<p align="center">
  <img src="https://github.com/snsten/SP500_Time-Series_Forecasting/blob/master/plots/sp_main.png">
</p>

## Exploratory Data Analysis
- Lag features Autocorrelation and Partial Autocorrelation
<p align="center">
  <img src="https://github.com/snsten/SP500_Time-Series_Forecasting/blob/master/plots/lag_corr.png">
</p>

## Models
Statistical Models include:
- ARIMA and SARIMAX
<p align="center">
  <img src="https://github.com/snsten/SP500_Time-Series_Forecasting/blob/master/plots/arima.png">
</p>

- Prophet
<p align="center">
  <img src="https://github.com/snsten/SP500_Time-Series_Forecasting/blob/master/plots/prophet.png">
</p>

Deep Learning Models include RNN variants such as:
- LSTM
<p align="center">
  <img src="https://github.com/snsten/SP500_Time-Series_Forecasting/blob/master/plots/lstm.png">
</p>

- Stacked LSTM
<p align="center">
  <img src="https://github.com/snsten/SP500_Time-Series_Forecasting/blob/master/plots/stack_lstm.png">
</p>

- CNN-LSTM
<p align="center">
  <img src="https://github.com/snsten/SP500_Time-Series_Forecasting/blob/master/plots/cnn_lstm.png">
</p>

## Requirements
Install requirements.txt file to make sure tested versions of libraries are in use.
Tested on local and google colab environment with following version of packages

- Python 3.6.x
- TensorFlow 2.2.0
- Keras 2.3.1
- Numpy 1.18.5
- Statsmodels 0.10.2
- Matplotlib 3.2.2

## References
- S&P Dow Jones Indices LLC, S&P 500 [SP500], retrieved from FRED, Federal Reserve Bank of St. Louis; https://fred.stlouisfed.org/series/SP500, June 30, 2020.
