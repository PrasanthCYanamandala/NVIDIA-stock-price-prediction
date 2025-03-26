# 📈 NVIDIA Stock Price Movement Prediction – BUAN 6341 AML Project 1

This repository contains Group 5's submission for **Project 1** in the **Applied Machine Learning (AML)** course (BUAN 6341). The goal of this project is to **predict NVIDIA’s stock price direction (up/down)** using a rich set of features derived from historical stock data, technical indicators, macroeconomic variables, and company financials.

## 🎯 Project Objective

- Predict whether NVIDIA (NVDA) stock will go up or down
- Use a combination of:
  - Hourly stock price data
  - Technical indicators
  - Competitor stock data
  - Economic indicators (CPI, GDP, Interest Rates, etc.)
  - Company financials (Income Statement, Balance Sheet, Cash Flow)

## 📦 Data Sources

- **Stock data** (NVDA, AMD, Intel, Qualcomm, Google) – hourly historical prices
- **Technical indicators** – computed using `pandas_ta` (SMA, EMA, MACD, RSI, Bollinger Bands, etc.)
- **Economic indicators** – from FRED via `pandas_datareader`
- **Company financials** – using `yfinance` for:
  - Quarterly income statements
  - Balance sheets
  - Cash flow statements

## 🔍 Key Features Engineered

- Relative Strength Index (RSI)
- MACD & Signal Line
- Simple & Exponential Moving Averages
- Bollinger Bands
- On-Balance Volume (OBV)
- Average True Range (ATR)
- Chaikin Money Flow (CMF)
- VWAP
- Technical Envelopes
- Merged hourly data with macro indicators and financial data at monthly/quarterly level

## 🧠 Methodology Summary

1. **Data Integration**  
   - Merged stock data of NVIDIA with competitors on hourly granularity  
   - Combined with macroeconomic indicators and financial metrics at monthly/quarterly levels  

2. **Feature Engineering**  
   - Computed 15+ advanced technical indicators  
   - Created relative and contextual features across competitors and time  

3. **Exploratory Analysis**  
   - Analyzed trends in volatility, price momentum, and economic conditions  
   - Interpreted financial impact on stock price direction  

4. **Next Steps (not in current version)**  
   - Implement classification models (e.g., Random Forest, XGBoost, LSTM)  
   - Evaluate prediction accuracy on unseen stock data  

## 👥 Group Members

- **Siva Srinivas Narra** – SXN230069  
- **Prashanth Chowdary Yanamandala** – PXY230011  
- **Tarun Raghu** – TXR230002  

---

📌 *This project demonstrates the power of combining financial, technical, and macroeconomic data in time-series modeling for stock movement prediction.*
