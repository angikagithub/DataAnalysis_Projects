# Stock Market Analysis Project
## Overview
A collection of data points indexed in time order is called a time series. Since time series data are ubiquitous, any data scientist or analyst must be able to manipulate them.

Here I examined stock market statistics, especially related to a few technological stocks **(Apple, Amazon, Google, and Microsoft)**.

Here the dataset is live and have retrieved stock information from **yfinance** and utilize **Seaborn** and **Matplotlib** to display various parts of it. 
Used many methods for assessing a stock's risk based on its historical performance. Also used the **Long Short Term Memory (LSTM)** approach to forecast future stock values!

***Here the analysis answers the following questions:***

1. What was the change in price of the stock over time?
2. What was the daily return of the stock on average?
3. What was the moving average of the various stocks?
4. What was the correlation between different stocks'?
5. How much value do we put at risk by investing in a particular stock?
6. How can we attempt to predict future stock behavior? (Predicting the closing price stock price of APPLE inc using LSTM)

## Install Packages
To install the necessary packages, run the following commands:

```sh
pip install yfinance
pip install mpl_finance
pip install tensorflow
```
