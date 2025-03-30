# Stock Price Prediction using BiLSTM

🛠️ **Dataset Used:**  
- Yahoo Finance is used to fetch stock market data.  
- We can directly fetch datasets using `import yfinance` in Python.  
- This code collects closing price, high, low, open, and volume of a particular stock.  

🛠️ **Stock Data Used:**  
- Stock: `ITC.NS`  
- Timeframe: 01/01/2015 to 27/03/2025  

🛠️ **Stock Price Prediction Model:**  
- This repository contains a deep learning-based stock price prediction model using **Bidirectional LSTM (BiLSTM)**.  
- The model utilizes historical stock price data and various technical indicators to forecast future stock prices.  

### **Features 📈**  
✅ Fetches historical stock data using Yahoo Finance API  
✅ Computes technical indicators (SMA, EMA, RSI, MACD, ATR, Bollinger Bands, etc.)  
✅ Applies log transformation, scaling, and time-series windowing  
✅ Implements a BiLSTM-based deep learning model  
✅ Uses Adam optimizer and Mean Absolute Percentage Error (MAPE) for evaluation  
✅ Visualizes true vs. predicted stock prices  
