# StockPortfolioOptimization

This project is a Stock Portfolio Optimization application that uses machine learning and sentiment analysis to help investors make data-driven decisions based on stock performance and news sentiment. The application integrates Yahoo Finance for historical stock data, Keras for machine learning models, and NewsAPI for sentiment analysis of news articles.

Table of Contents

- Project Overview

- Tech Stack

- Features

- Usage


## Project Overview

The Stock Portfolio Optimization app provides the following capabilities:

Stock Price Prediction:
Using historical stock data (from Yahoo Finance), the app uses a machine learning model to predict future stock prices.

Moving Averages:
Visualizes 100-day and 200-day moving averages of the stock to help users understand the long-term trend.

Sentiment Analysis:
Analyzes news articles related to the stock using the VADER Sentiment Analyzer and provides an overall sentiment score.

Interactive Visualization:
The app uses Streamlit to provide a user-friendly interface that allows users to interact with stock data, predictions, and sentiment scores.

Tech Stack

## Python Libraries:

- numpy: For numerical operations and data manipulation.

- pandas: For data manipulation and handling of stock data.

- matplotlib: For plotting and data visualization.

- yfinance: For fetching stock price data from Yahoo Finance.

- keras: For building and loading a pre-trained stock prediction model.

- streamlit: For creating an interactive web application interface.

- vaderSentiment: For performing sentiment analysis on news articles.

- requests: For making HTTP requests to NewsAPI to fetch news articles.

- sklearn: For data scaling and pre-processing.

External APIs:
Yahoo Finance: For retrieving historical stock data.

NewsAPI: For fetching news articles related to the stock and performing sentiment analysis.

## Features
Stock Data Visualization:
Displays historical stock prices (closing prices) in an interactive plot.

Plots 100-day and 200-day moving averages to show long-term trends.

Stock Price Prediction:
Uses a trained Keras-based machine learning model (keras_model.h5) to predict future stock prices based on historical data.

Provides a comparison between the predicted and actual stock prices.

News Sentiment Analysis:
Fetches news articles for the specified stock ticker from NewsAPI and analyzes the sentiment using the VADER Sentiment Analyzer.

Provides a sentiment score and an interpretation of the sentiment (positive, neutral, or negative).

Streamlit Web Interface:
Allows users to input a stock ticker symbol, select the size of the training data, and visualize stock data and predictions.

Includes a sidebar for controlling inputs like stock ticker and training data size.

## Usage

Running the App
To run the application locally, use the following command:
streamlit run app.py
