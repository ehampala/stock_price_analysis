# 📊 Stock Price Exploratory Data Analysis (EDA)

## 📌 Overview

This project presents an in-depth **Exploratory Data Analysis (EDA)** of stock market time series data, focusing on **Apple Inc. (AAPL)** and a comparative analysis with other major tech companies like **Google (GOOG)**, **Amazon (AMZN)**, and **Microsoft (MSFT)**.

The goal is to extract meaningful insights, identify patterns, detect outliers, and assess the statistical properties of the data — all essential steps before building predictive models.

---

## 📁 Dataset

Data is sourced directly using the [`yfinance`](https://pypi.org/project/yfinance/) Python library, covering **daily adjusted close prices** from **2018-01-01 to 2024-12-31** for:

- Apple Inc. (`AAPL`)
- Alphabet Inc. (`GOOG`)
- Amazon (`AMZN`)
- Microsoft (`MSFT`)

---

## 🧪 Key EDA Components


- ✅ Basic dataset inspection (missing values, data types)
- 📈 Time series visualization of stock prices
- 📊 Rolling mean and volatility analysis
- 📈 Technical Indicator Analysis
- 📉 Daily and log returns
- 🧮 Outlier detection using z-scores/iqr
- 🧭 Stationarity check with Augmented Dickey-Fuller test
- 📆 Seasonal decomposition of time series
- 🔁 Autocorrelation and Partial Autocorrelation (ACF / PACF)
- ♻️ Correlation matrix between selected tech stocks
- 📌 Insight summary with takeaways and next steps

---

## 🔍 Key Insights


- Stock returns show non-stationarity but weak autocorrelation.
- Volatility clusters are visible around major market events.
- Strong positive correlation exists between major tech stocks.
- Outliers in daily returns may indicate impactful news or earnings reports.

---

## 🚀 Next Steps

- Add **technical indicators** (e.g., RSI, MACD)
- Forecast future prices using **ARIMA**, **LSTM** or **TFT**
- Build an **interactive dashboard** with Streamlit or Plotly Dash

---

## 🛠️ Requirements

- Python ≥ 3.8
- `pandas`, `numpy`, `matplotlib`, `seaborn`
- `statsmodels`, `scipy`, `yfinance`

To install the dependencies:

```bash
pip install -r requirements.txt