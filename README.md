# 📈 RSI Indicator Strategy – Stock Market Analysis with Python

A fully interactive **Google Colab notebook** implementing the **Relative Strength Index (RSI)** — one of the most popular momentum indicators in technical analysis — to identify potential **buy** and **sell** signals in stock prices.

🔗 **[Launch in Google Colab](https://colab.research.google.com/drive/1POsmL_2WxEuhu_6-PlEkRJjLC_c-ySeF#scrollTo=lmC5brMEUFO2)**

---

## 📌 Overview

This project demonstrates how to use Python and financial data to:

- Analyze stock momentum with RSI
- Detect overbought/oversold conditions
- Visualize signals on price charts
- Apply the technique on **real-world examples**:  
  - 🏢 **Sony Corporation (SONY)**
  - 🍏 **Apple Inc. (AAPL)**

---

## 🧠 What is RSI?

**Relative Strength Index (RSI)** is a technical indicator that measures the strength of recent price changes. It oscillates between 0 and 100.

- **RSI > 70** → Overbought → ⚠️ Possible **Sell**
- **RSI < 30** → Oversold → 🟢 Possible **Buy**

---

## 🔍 Features

✅ Fetch live historical stock data via `yfinance`  
✅ Calculate RSI using a rolling window (default: 14 days)  
✅ Mark buy/sell signals directly on the chart  
✅ Backtest a basic RSI-based trading strategy  
✅ Visualize RSI + price trends with `matplotlib`  

---

## 🛠️ Tech Stack

- **Python** (Google Colab)
- `pandas` – data manipulation  
- `yfinance` – stock data  
- `numpy` – numerical operations  
- `matplotlib` – charting

---

## 📉 RSI Charts & Signal Visualization

### 📊 SONY RSI Chart
<img width="1896" height="1066" alt="SONY RSI Chart" src="https://github.com/user-attachments/assets/af3b0ec3-e32c-460b-a5c8-620fd00fd9c8" />

---

### 🍏 AAPL RSI Chart
<img width="1840" height="1056" alt="AAPL RSI Chart" src="https://github.com/user-attachments/assets/a9f79a83-6c72-4e04-a69e-987c63468089" />

---

## 🚀 How to Use

1. Open the notebook 👉 [Colab Link](https://colab.research.google.com/drive/1POsmL_2WxEuhu_6-PlEkRJjLC_c-ySeF#scrollTo=lmC5brMEUFO2)
2. Click **Runtime > Run All**
3. Modify the ticker symbols (`'SONY'`, `'AAPL'`, etc.) to analyze other stocks
4. Customize RSI thresholds if needed

---

## 📦 Requirements

Install necessary packages (if running locally):

```bash
pip install yfinance pandas matplotlib
```

##✍️ Author
Aadya Agarwal
Empowering smart analysis through data and code.
