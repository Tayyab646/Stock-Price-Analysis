
# 📈 Stock Price Prediction

## 📌 Project Overview

This project focuses on **short-term stock price prediction** using machine learning techniques.
It predicts the **next day’s closing price** of a selected stock based on historical market data fetched from **Yahoo Finance**.

The project demonstrates practical skills in **time series data handling**, **API-based data collection**, and **regression modeling**.

---

## 🎯 Project Objective

The main objectives of this project are to:

* Fetch historical stock price data using the **yfinance API**
* Analyze and understand stock market trends and features
* Train machine learning models such as:

  * Linear Regression
  * Random Forest Regressor
* Predict the **next trading day’s closing price**
* Compare **actual vs predicted prices** using visual plots

---

## 📂 Dataset Source

The dataset is **automatically fetched** using the `yfinance` Python library, eliminating the need for manual data downloads.

Supported stock symbols include (but are not limited to):

* **AAPL** – Apple
* **TSLA** – Tesla
* **MSFT** – Microsoft
* **GOOGL** – Google
* **AMZN** – Amazon

Users can easily modify the stock ticker to experiment with different companies.

---

## 🧠 Features Used for Prediction

The following features are extracted from historical stock data:

* Open price
* High price
* Low price
* Trading volume
* Close price (used as the target label, shifted by one day)

These features help the model capture market behavior for short-term forecasting.

---

## 🛠 Skills Practiced

This project helped develop the following skills:

* Time series data handling
* API-based data fetching using **yfinance**
* Regression modeling with machine learning
* Data visualization and performance comparison
* Feature selection and preprocessing

---

## 📊 Visualization

The project includes plots that visually compare:

* Actual stock prices
* Predicted stock prices

This helps in understanding model performance and prediction accuracy.

---

## ✅ Conclusion

This project provides a hands-on introduction to financial data analysis and machine learning–based stock price prediction. It highlights how historical data and regression models can be used to make short-term forecasts while reinforcing core ML and data analysis concepts.

