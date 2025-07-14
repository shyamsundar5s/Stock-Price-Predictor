# Stock-Price-Predictor
This repository presents a comprehensive approach to predicting stock prices using machine learning, with a focus on both classical and deep learning models. The project demonstrates the workflow from data collection and preprocessing to benchmarking with Linear Regression and implementing advanced Long Short-Term Memory (LSTM) neural networks.

## Overview

Stock price prediction is a challenging time series forecasting task due to the highly volatile and non-linear behavior of financial markets. This project aims to forecast the future closing prices of stocks—using historical market data—employing both a benchmark linear regression model and advanced LSTM models.

## Features

- **Data Collection:** Retrieve historical stock data (e.g., Google ‘GOOGL’) directly from online sources.
- **Data Cleaning & Preprocessing:** Normalization, feature selection, and visualization.
- **Benchmark Modeling:** Implementation of a baseline Linear Regression model.
- **Deep Learning Modeling:** Construction and training of basic and improved LSTM networks using Keras.
- **Performance Evaluation:** Visual and statistical assessment of predictions (MSE, RMSE).
- **Visualization:** Graphical comparison of actual vs. predicted prices.

## Dataset

- **Source:** Google Finance/S&P 500 stock data.
- **Features:** Date, Open, High, Low, Close, Volume.
- **Target:** Closing price of the stock.

## Project Structure

1. **Data Acquisition:** Fetch historical data and store it as CSV.
2. **Preprocessing:** Clean and normalize the data, remove irrelevant features, and visualize trends.
3. **Baseline Model:** Train and evaluate a Linear Regression model as a reference.
4. **LSTM Models:** Prepare time series data, build LSTM architectures, and compare basic and improved models.
5. **Visualization & Evaluation:** Generate plots and report error metrics.
