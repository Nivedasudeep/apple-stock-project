# apple-stock-project
# Apple Stock Price Prediction – 30 Day Forecast 📈

This project focuses on forecasting **Apple Inc. (AAPL) stock prices for the next 30 days** using historical stock market data and a combination of **time series models and machine learning algorithms**.  
A **Streamlit web application** is included for interactive forecasting and visualization.

---

## 📌 Objective
To analyze Apple’s historical stock prices (2012–2019) and build models that can accurately predict the **next 30 days closing price**, helping investors and analysts make informed decisions.

---

## 📊 Dataset
- **Source:** Yahoo Finance  
- **Period:** 2012 – 2019  
- **File:** `AAPL.csv`  
- **Features:**
  - Date
  - Open
  - High
  - Low
  - Close
  - Volume  
- **Target Variable:** Closing Price

---

## 🧠 Models Used
- Persistent Model
- ARIMA
- SARIMA
- Random Forest
- XGBoost  

Models were compared using evaluation metrics such as **RMSE, MAE, and R² score**.  
XGBoost and the Persistent model showed the best performance.

---

## 📈 Exploratory Data Analysis (EDA)
- Closing price trend analysis  
- Moving averages (30-day, 90-day)  
- Volume analysis  
- Trend, seasonality, and volatility identification  

---

## 🖥️ Streamlit Application
The project includes a **Streamlit app** that allows users to:
- View historical stock price trends
- Generate a **30-day forecast**
- Visualize predictions interactively  

### Run the Streamlit App
```bash
pip install -r requirements.txt
streamlit run app.py
