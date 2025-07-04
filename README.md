# 📈 Stock Price Trend Prediction Using LSTM and Streamlit

This project is a **Stock Price Prediction Web App** built using **Long Short-Term Memory (LSTM)** neural networks and deployed with **Streamlit**.  
It allows users to visualize historical stock trends and predict future stock prices interactively.

---

## 🚀 Features

- 📅 Select any **Start Date** and **End Date** for stock data
- 🔍 Enter any **Stock Ticker Symbol** (e.g., AAPL, TSLA, MSFT)
- 📊 Visualizations of:
  - Closing Price vs Time
  - 100-Day Moving Average
  - 100 & 200-Day Moving Averages
  - Predicted Price vs Actual Price
- 📈 LSTM Model trained on historical stock prices
- 🌐 Simple and clean **Streamlit** interface

---

## 🛠 Technologies Used

- Python
- Streamlit
- Keras & TensorFlow (LSTM)
- Scikit-learn
- Matplotlib & Pandas
- Yahoo Finance API (`yfinance`)

---

## ⚙️ How to Run Locally

1. Clone this repository:
   ```bash
   git clone https://github.com/AnushkaSontakke2005/stock-price-prediction.git
   cd stock-price-prediction

2.Install Dependencies:
pip install -r requirements.txt

3.Run the Streamlit app:
streamlit run app.py
