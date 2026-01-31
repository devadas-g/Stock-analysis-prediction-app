# 📈 Stock Analysis & Prediction App

An interactive **Stock Market Analysis and Forecasting Web Application** built using **Python and Streamlit**.  
The app allows users to analyze historical stock data, visualize technical indicators, and predict future stock prices using **time-series forecasting**.

---

## 🚀 Features

- 🔍 Search stocks using ticker symbols (e.g., TSLA, AAPL, INFY)
- 📊 Interactive **candlestick & closing price charts**
- 📈 Technical indicators:
  - Relative Strength Index (**RSI**)
  - Moving Average Convergence Divergence (**MACD**)
- 🤖 **30-day stock price prediction** using ARIMA time-series model
- 📉 Model performance evaluation using **RMSE**
- 🎨 Interactive and responsive visualizations using **Plotly**

---

## 🛠️ Tech Stack

- **Programming Language:** Python  
- **Web Framework:** Streamlit  
- **Data Source:** Yahoo Finance API (yFinance)  
- **Data Processing:** Pandas, NumPy  
- **Visualization:** Plotly  
- **Time-Series Forecasting:** ARIMA (statsmodels)

---

## 📂 Project Structure
Time-series-project/
│
├── pages/
│ ├── Stock_analysis.py
│ ├── Stock_Prediction.py
│ └── Trading.py
│
├── utils/
│ ├── model_train.py
│ └── plotly_figure.py
│
├── app.png
├── requirements.txt
├── README.md
└── SOURCES.txt

---


## ▶️ How to Run the Application
python -m streamlit run Trading.py


---

## 📊 Streamlit App Preview

<img width="1895" height="909" alt="Screenshot 2026-01-31 232134" src="https://github.com/user-attachments/assets/ea245c6b-a153-4008-a1dc-82560b6e1139" />



