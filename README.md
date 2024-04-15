Final Project: Stock Price Prediction

Authors: Vinh Bui, Anson Quon, Suhas Prasad

Description
We strive to use multiple techniques and algorithms in ML to compare the performance of different financial instruments against each other and predict the price from trending news data.

Problem Statement
Most investors can be classified as “long-term investors” – people who do not engage with or rely on daily pricing data to inform frequent trading activities and simply buy a stock and forget about it. We want to see if we can improve upon this naive strategy and effectively quantify the differences in risk and gain.

Objective
We will use historical data of price actions and news to predict whether the stock price is going to go up or down in the future.

Approach/ Methodology
Our prediction strategy distinguishes between two types of investors based on their approach to forecasting stock price movements: the Baseline investor and the Machine Learning (ML) investor. Each employs a distinct method for making predictions, as outlined below.

Baseline: The Baseline investor adopts a simple, heuristic-based approach to predicting stock prices, wherein the investor assumes that the stock price will always increase the following day. This strategy is derived from observations made during the Exploratory Data Analysis (EDA) phase, which suggested a general upward trend in the training dataset. While simplistic, this method serves as our benchmark for evaluating the sophistication and value added by employing more complex ML models.

Machine Learning Models: Unlike the Baseline investor, the ML investor leverages advanced analytics and predictive modeling techniques, categorized into three distinct groups:

Classical Time Series Models: These models, such as ARIMA (AutoRegressive Integrated Moving Average) and Exponential Smoothing, are specifically designed to forecast future points in a time series based on past data. They can be parameterized to handle data with trends, seasonality, and other temporal patterns. Our time series models were developed in R and are located in the files apple_stock_time_series_analysis.Rmd.

Classical Machine Learning Models: This category includes models like Linear Regression, Decision Trees, and Random Forests, which, though not specifically tailored for time series data, can be adapted for predictive tasks by engineering features that capture temporal dependencies.

Modern Machine Learning Models: Encompassing advanced techniques such as Neural Networks and Deep Learning, including LSTM (Long Short-Term Memory) networks and convolutional models designed for sequence prediction. These models can capture complex patterns in large datasets, potentially offering superior predictive performance on challenging forecasting tasks.

# Note:
- prophet.ipynb: This is the jupyter notebook that I use to predict stocks using Prophet python packages, but I do not have time to do more throughout implementations.
- accuracy.ipynb: For calculating and comparing the model's performances





