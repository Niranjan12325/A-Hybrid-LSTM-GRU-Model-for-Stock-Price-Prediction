# 📈 Stock Price Prediction using Deep Learning & Machine Learning

## 🔍 Overview
This project focuses on predicting stock prices using a combination of Deep Learning and Machine Learning models. 
It utilizes historical stock market data along with technical indicators to forecast future price movements.

---

## 🎯 Objectives
- Analyze historical stock price data
- Generate technical indicators for better feature representation
- Build multiple predictive models
- Compare performance of different models

---

## 🛠️ Tech Stack
- Python
- Pandas, NumPy
- Matplotlib, Seaborn, Plotly
- Scikit-learn
- TensorFlow / Keras
- yFinance (for stock data)
- ta (Technical Analysis library)

---

## 📊 Features
- Real-time stock data fetching using yFinance
- Feature engineering using technical indicators
- Data normalization using MinMaxScaler
- Visualization of stock trends
- Multiple model training and evaluation

---

## 🧠 Models Used
- LSTM (Long Short-Term Memory Neural Network)
- GRU (Gated Recurrent Unit)
- CNN (1D Convolutional Neural Network)
- Random Forest Regressor

👉 The project compares different models to determine the most accurate prediction approach.

---

## 📁 Dataset
- Data collected using yFinance API
- Includes:
  - Open, Close, High, Low prices
  - Volume
  - Technical indicators (via ta library)

---

## 🚀 How to Run

1. Open the notebook in Google Colab  
2. Install required libraries:
   ```bash
   pip install yfinance ta
