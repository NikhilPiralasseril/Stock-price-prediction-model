# Stock-price-prediction-model

Stock Price Prediction repo contains two components:
1. A Streamlit web application (Stock_Price_Predictor_App.py) for interactive stock price prediction using a pre-trained Keras model.
2. A Jupyter Notebook (Stock_Price_Analysis.ipynb) for exploratory data analysis and visualization of stock data.
The project fetches historical stock data using the yfinance library, performs analysis with moving averages, and predicts future stock prices with a deep learning model. It’s designed for anyone interested in stock market trends, data science, or machine learning.

Features: 
Streamlit App (Stock_Price_Predictor_App.py)
User Input: Enter any stock ticker (e.g., "GOOG" for Google).
Data Fetching: Downloads 20 years of historical stock data from Yahoo Finance.
Visualizations:
Plots of original closing prices with moving averages (100, 200, and 250 days).
Comparison of original vs. predicted closing prices.
Prediction: Uses a pre-trained Keras model to forecast stock prices on the test set.
Interactive UI: Built with Streamlit for a seamless, browser-based experience.

Jupyter Notebook (Stock_Price_Analysis.ipynb)
Data Exploration: Loads and inspects 20 years of Google stock data ("GOOG").
Column Analysis: Includes Open, High, Low, Close, Adj Close, and Volume (configurable with auto_adjust).
Statistics: Summary stats and missing value checks.
Visualization: Basic plot of closing prices (extendable with custom functions).
Flexibility: Demonstrates raw data handling for further experimentation.
