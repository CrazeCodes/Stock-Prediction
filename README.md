# 📊 NSE Stock Prediction Dashboard

🚀 **Live Preview**: [nsestockprediction.netlify.app](https://nsestockprediction.netlify.app/)

This is a fully client-side, AI-inspired **stock prediction dashboard** for select **NSE-listed companies**. It uses simulated market data and JavaScript-based predictive logic (technical analysis) to estimate short-term stock price movements, presented with beautiful visualizations.

---

## 📌 Key Features

- 📈 **Dual Prediction Models**:
  - **Dynamic Feature Method** (based on technical indicators)
  - **Momentum-Based Method** (based on recent price movement trends)
  
- 📊 **Real-time 7-Day Price Forecast**
- 🧠 Embedded prediction logic with Moving Averages, RSI, Volatility
- 🔴 **Bearish/Bullish Market Signals**
- 📉 Interactive Chart.js graphs for historical and predicted prices
- ⚙️ Completely **offline and frontend-based** (no server or backend required)

---

## 💡 How It Works

- The dashboard generates **mock historical stock data** for select NSE stocks.
- It calculates technical indicators:
  - MA5, MA10, MA20
  - RSI (Relative Strength Index)
  - Volatility
- Two prediction models are applied:
  - **Dynamic Feature Model**: Uses a signal formula combining moving averages, RSI signals, and random volatility noise.
  - **Momentum Model**: Uses recent return trends to project forward movement.
- Predictions are plotted alongside historical trends using **Chart.js**.

---

## 🛠️ Tech Stack

| Technology    | Purpose                     |
|---------------|------------------------------|
| **HTML/CSS**  | Web layout and styling       |
| **JavaScript**| Data simulation & prediction |
| **Chart.js**  | Graphing library for charts  |
| **Netlify**   | Hosting platform             |

---

## 🧪 How to Run This Project

### ✅ Option 1: Instant Online Run

Use these online editors:

- [CodePen](https://codepen.io/)
- [JSFiddle](https://jsfiddle.net/)
- [Replit](https://replit.com/)
- [CodeSandbox](https://codesandbox.io/)

Just paste the full HTML code and hit "Run".

---

### ✅ Option 2: Run Locally

1. Copy and save the code as:

   ```bash
   stock-dashboard.html
