# TIME-SERIES-ANALYSIS-EURUSD
Time Series Analysis using Yahoo Finance Data

This project focuses on performing time series analysis using data obtained from Yahoo Finance. The project involves importing the necessary libraries, fetching stock data for a specific time period, exploring and visualizing the data, and applying various analysis techniques.

The project utilizes the following steps:

1. Importing Data: The project begins by importing the required libraries, including yfinance for fetching data from Yahoo Finance.

2. Data Fetching: Stock data for a specified currency pair (EUR/USD) is fetched from Yahoo Finance using the yfinance library. The data includes open, high, low, close prices, adjusted close prices, and volume.

3. Data Exploration: The project explores the fetched data by examining its structure and obtaining summary statistics. This step provides insights into the data's dimensions, data types, and statistical measures such as mean, standard deviation, and quartiles.

4. Plots: The project includes visualizations of the data using line charts, histograms, candlestick charts, and correlation heatmaps. These plots provide a visual representation of price movements and the relationship between different variables.

5. Stochastic Oscillator: The project applies the Stochastic Oscillator indicator, which measures momentum and identifies overbought or oversold conditions in the market. The %K and %D values of the Stochastic Oscillator are plotted alongside the price data.

6. Multiple Linear Regression: The project performs multiple linear regression using the stock's open, high, low, adjusted close prices, and volume as predictor variables. The close price is considered the target variable. The regression coefficients and intercept are obtained and printed.

7. AutoARIMA: The project employs the auto_arima function from the pmdarima library to find the best parameters (p, d, q) for an ARIMA model. The function uses stepwise search to minimize the Akaike Information Criterion (AIC) and determines the best model for the data.

The project provides a concise overview of time series analysis using Yahoo Finance data, including data fetching, exploration, visualization, and analysis techniques such as stochastic oscillator, multiple linear regression, and ARIMA modeling.
