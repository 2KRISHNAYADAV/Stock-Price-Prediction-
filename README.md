# 📈 Stock Price Prediction using ARIMA & LSTM

> Built forecasting models using Statistical and Deep Learning techniques to analyze and predict stock price movements.

---

## 🚀 Project Overview

This project focuses on predicting future stock closing prices using historical stock market data.

Two different approaches were implemented and compared:

- 📊 **ARIMA** (Statistical Time Series Model)
- 🤖 **LSTM** (Deep Learning Model)

The goal was to compare traditional statistical modeling with deep learning for financial forecasting.

---

## 📂 Dataset

- Source: Yahoo Finance Historical Data
- Features Used:
  - Date
  - Open
  - High
  - Low
  - Close
  - Volume

---

## 🛠️ Tech Stack

| Category | Tools Used |
|----------|------------|
| Language | Python |
| Data Processing | Pandas, NumPy |
| Visualization | Matplotlib, Seaborn |
| Statistical Modeling | statsmodels (ARIMA) |
| Deep Learning | TensorFlow / Keras |
| Scaling | MinMaxScaler |
| Evaluation | RMSE |

---

## 🔄 Complete Machine Learning Pipeline

The project follows a full production-level workflow:

1. Data Collection
2. Data Cleaning
3. Exploratory Data Analysis (EDA)
4. Stationarity Check (ADF Test)
5. ARIMA Implementation
6. Data Scaling
7. Sequence Creation (Sliding Window)
8. LSTM Model Training
9. Model Evaluation (RMSE Comparison)

---

## 📊 Exploratory Data Analysis

- Trend visualization of stock prices
- Rolling mean analysis
- Volatility inspection
- ACF & PACF plots for ARIMA parameter tuning

---

## 📈 ARIMA Model

- Checked stationarity using ADF test
- Applied differencing
- Selected (p, d, q) using ACF & PACF
- Trained ARIMA model
- Evaluated using RMSE

### ARIMA RMSE:
**24.54**

---

## 🤖 LSTM Model

### Steps:

- Applied MinMax Scaling
- Created 60-day time sequences
- Built stacked LSTM architecture
- Used Dropout to prevent overfitting
- Optimizer: Adam
- Loss Function: MSE
<img width="680" height="838" alt="Screenshot 2026-03-02 115514" src="https://github.com/user-attachments/assets/79a5c581-18da-4d56-ba53-210461eca750" />
<img width="688" height="496" alt="Screenshot 2026-03-02 122023" src="https://github.com/user-attachments/assets/68f4127e-4ad1-402a-926c-55dfacf4bb2a" />

### LSTM RMSE:
**2.89**
<img width="530" height="193" alt="Screenshot 2026-03-02 122049" src="https://github.com/user-attachments/assets/80ad6c27-bae5-4df6-b25e-e1e82988f230" />

---

## 🆚 Model Comparison

| Metric | ARIMA | LSTM |
|--------|--------|--------|
| Linear Pattern | ✅ | ✅ |
| Non-Linear Pattern | ❌ | ✅ |
| RMSE | 24.54 | 2.89 |
| Performance | Moderate | High |

LSTM significantly outperformed ARIMA due to its ability to capture complex non-linear dependencies in stock price movements.

---

## 📉 Visualization

Model comparison plot between:
- Actual Prices
- ARIMA Predictions
- LSTM Predictions
<img width="831" height="592" alt="Screenshot 2026-03-02 122107" src="https://github.com/user-attachments/assets/15ffc8c3-42bd-45a5-808d-67c6c522e3a2" />


---

## 🎯 Key Learnings

- Importance of stationarity in time-series modeling
- Difference between statistical and deep learning approaches
- Time-series preprocessing techniques
- Sequence generation for LSTM
- Model evaluation using RMSE

---

## 🔮 Future Improvements

- Hyperparameter tuning
- Add GRU model comparison
- Deploy using Streamlit
- Real-time API integration
- Hybrid ARIMA + LSTM model

---

## 👨‍💻 Author

Krishna Yadav  
Machine Learning Engineer | Deep Learning Enthusiast  

---

## ⭐ If you found this useful, consider giving it a star!
