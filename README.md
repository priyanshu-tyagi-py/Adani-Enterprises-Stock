# Adani Enterprises Stock Price Prediction
![Python](https://img.shields.io/badge/Python-3.10-blue)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-Scikit--Learn-orange)
![Time Series](https://img.shields.io/badge/Time%20Series-Analysis-green)
![Status](https://img.shields.io/badge/Project-Completed-success)
> A machine learning and time series analysis project to predict stock price direction and analyze market behavior using technical indicators.

## Problem Statement: <br>
Stock markets are highly dynamic and influenced by multiple factors such as market sentiment, economic conditions, global events, and company-specific developments. This makes predicting stock price movements a complex task. Additionally, financial data is inherently noisy, non-linear, and non-stationary, which limits the effectiveness of traditional modeling approaches. In this project, a machine learning-driven approach is used to analyze and predict the price movement of Adani Enterprises stock using historical data — focusing not just on prediction, but on extracting meaningful insights from the data.
<br>
<br>
## What This Project Does: <br>
* Cleans and preprocesses real-world stock data<br>
* Applies feature engineering using technical indicators<br>
* Performs time series decomposition (trend, seasonality, residuals)<br>
* Builds a machine learning classification model to predict price direction<br>
* Generates visual insights to understand market behavior<br>

## Tech Stack: <br>
* Python <br>
* Pandas, NumPy <br>
* Matplotlib, Seaborn <br>
* Scikit-learn <br>
* Statsmodels <br>

## Feature Engineering & Analysis:
This project strongly emphasizes feature engineering, which is critical in financial ML:
* Moving Averages → Trend identification <br>
* Bollinger Bands → Volatility analysis <br>
* RSI (Relative Strength Index) → Momentum detection <br>
* MACD → Trend reversal signals <br>
* Volume Analysis → Strength confirmation <br>
* Seasonal Decomposition → Separation of trend, seasonality, and noise <br>
  
## Machine Learning Model: <br>
**Model Used:** Logistic Regression (Binary Classification) <br>
### Why Logistic Regression?
* Provides a **strong baseline model**
* Easy to interpret and debug
* Suitable for **Up/Down prediction tasks**
* Performs well on **noisy financial data**

## Results & Discussion: <br>
The model achieves moderate accuracy, which is expected in stock market prediction tasks. <br>
### Why Accuracy is Limited?
* Financial markets are influenced by unpredictable external factors
* Data is noisy and highly volatile
* Market patterns change over time (non-stationarity)
* Logistic Regression cannot fully capture complex non-linear relationships<br>

This highlights an important insight:
This reflects real-world financial modeling challenges, where perfect prediction is less important than extracting actionable insights. <br>

## Future Improvements: <br>
* Implement advanced models: <br>
  * Random Forest <br>
  * XGBoost <br>
  * LSTM (Deep Learning for time series) <br>
* Integrate external data: <br>
  * News sentiment analysis <br>
  * Macroeconomic indicators <br>
* Improve model validation and tuning <br>

## Visualizations: <br>
* Time Series Plots <br>
* Candlestick Charts <br>
* Technical Indicator Graphs <br>
* Trend & Seasonality Decomposition <br>

## Support
If you found this project useful, consider giving it a star ⭐
