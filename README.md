# 📈 Algorithmic Trading Bot  

This project is a simple yet powerful **algorithmic trading bot** that uses a **Simple Moving Average (SMA) crossover strategy** to generate buy/sell signals, backtest them on historical data, and track portfolio performance.  

It’s part of my journey into **AI-powered finance & algorithmic trading**, where I’m learning to bridge my passion for **machine learning, finance, and clean software design**.  

---

## 🚀 Features  
- 📊 **SMA Crossover Strategy** (Fast SMA vs. Slow SMA)  
- 🛠️ **Backtesting Engine** – evaluates the strategy on historical price data  
- 💰 **Trade Logging** – records entries, exits, and PnL per trade  
- 📉 **Risk Metrics** – calculates win rate, total return, and max drawdown  
- 📈 **Equity Curve Plotting** – visualizes portfolio performance over time  
- 🐍 **Clean OOP Python Design** for reusability and extensibility  

---

## 📊 Backtest Results (Sample)  
- **Total Trades:** 460  
- **Win Rate:** 45.43%  
- **Total Return:** \$113,656.96  
- **Average Trade PnL:** \$247.08  
- **Max Drawdown:** \$129,291.83  

---

## 🛠️ Tech Stack  
- **Python**  
- **Pandas & NumPy** (data handling)  
- **Matplotlib** (equity curve plotting)  
- **YFinance** (data fetching, optional)  

---

## 📂 Project Structure  

trading-bot/
│── data/ # Store historical price data
│── bot.py # Core trading bot logic (OOP-based)
│── backtest.py # Backtesting engine
│── utils.py # Helper functions (e.g., plotting)
│── README.md # Project documentation


---

## ▶️ How to Run  

1. **Clone repo & install requirements**  
   ```bash
   git clone <your-repo-url>
   cd trading-bot
   pip install -r requirements.txt


📌 Learnings

This project helped me deeply understand:

Strategy design & backtesting

Clean OOP implementation in Python

Financial metrics for evaluating trading systems

How to iterate toward more advanced AI-driven strategies

🔮 Next Steps

Add risk management rules (stop-loss, take-profit, position sizing)

Explore other strategies (RSI, MACD, Bollinger Bands)

Implement paper trading via broker APIs (Alpaca, Interactive Brokers)

Extend toward AI-powered strategies (reinforcement learning, deep learning)

✨ Author

👤 Taanish Chauhan

📧 taanishchauhan1406@gmail.com

🌐 www.linkedin.com/in/taanish-chauhan-289589317
