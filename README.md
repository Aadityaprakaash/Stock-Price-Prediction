# Stock-Price-Prediction
🛠️ Dataset used is Yahoo Finance, we can directly fetch dataset needed via (import yFinance) in python,so this code collects closing price, hign, low, open and volume of a particular stock.
🛠️Here (ITC.NS) stock has been used from 01/01/2015 to 27/03/2025.
🛠️This repository contains a deep learning-based stock price prediction model using Bidirectional LSTM (BiLSTM). The model utilizes historical stock price data and various technical indicators to forecast future stock prices.
Features
  📈 Fetches historical stock data using Yahoo Finance API
  🔍 Computes technical indicators (SMA, EMA, RSI, MACD, ATR, Bollinger Bands, etc.)
  📊 Applies log transformation, scaling, and time-series windowing
  🤖 Implements a BiLSTM-based deep learning model
  🏆 Uses Adam optimizer and Mean Absolute Percentage Error (MAPE) for evaluation
  📉 Visualizes true vs. predicted stock prices
