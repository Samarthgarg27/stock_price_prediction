# stock_price_prediction
Machine learning project for predicting stock prices using historical market data.
# Stock Price Prediction Using Machine Learning

A machine learning project that predicts the next day's stock closing price using historical stock market data and machine learning techniques.

## Project Overview

The goal of this project is to use historical stock market data to build a model that can estimate the next day's closing price.

The project uses historical data such as Open, High, Low, Close, and Volume prices. Additional features such as moving averages and previous closing prices are created to improve the prediction.

Two machine learning models are trained and compared:

- Linear Regression
- Random Forest Regressor

The models are evaluated using MAE, RMSE, and R² Score.

## Features

The following features are used for prediction:

- Open Price
- High Price
- Low Price
- Closing Price
- Trading Volume
- Previous Day Closing Price
- 5-Day Moving Average
- 10-Day Moving Average
- 20-Day Moving Average
- Daily Return

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- yFinance
- Joblib
- Google Colab

## Project Workflow

```text
Historical Stock Data
        ↓
Data Collection
        ↓
Data Cleaning
        ↓
Exploratory Data Analysis
        ↓
Feature Engineering
        ↓
Train/Test Split
        ↓
Linear Regression
        ↓
Random Forest Regressor
        ↓
Model Evaluation
        ↓
Actual vs Predicted Visualization
        ↓
Feature Importance Analysis
        ↓
Next-Day Price Prediction
