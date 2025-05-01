# 📈 Stock Trading Automation

Welcome to the **Stock Trading Automation** project — a collection of modular and well-documented Jupyter Notebooks designed to help you automate trading strategies using the Zerodha Kite Connect API.

This repository is built for retail traders, algorithmic trading enthusiasts, and developers who want to explore or deploy automated trading systems in Indian stock markets.

---

## 🚀 Features

- 🔗 **Zerodha API Integration**  
  Easily connect to Zerodha's trading platform and fetch live/historical data.

- 📊 **Live Trading Bots**
  - RSI-based Bot
  - Guppy Multiple Moving Averages (GMMA) Bots
  - Advanced bot handling multiple strategies simultaneously

- 🧪 **Backtesting Tools**  
  Evaluate your trading strategies on historical data before going live.

- 🧠 **Stock Screening**  
  Identify trade-worthy stocks using the GMMA screener logic.

- 🔄 **Timeframe Adjustment & Heikin-Ashi Conversion**  
  Convert candlestick patterns, change chart resolution, and analyze trends more effectively.

---

## 📁 Repository Structure

```bash
├── 1_Getting_Started_with_Zerodha.ipynb
├── 2_Backtesting_Program.ipynb
├── 3_Live_BOT_(1)_on_RSI.ipynb
├── 4_Live_BOT_(2)_on_GUPPY_with_screener.ipynb
├── 5_Live_BOT_(3)_Guppy_Automated.ipynb
├── 6_Live_BOT_(4)_advance_bot_multiple_bot_working_in_single_bot.ipynb
├── 7_Live_BOT_(5).ipynb
├── 8_Stock_Screener_(GUPPY).ipynb
├── 9_Technical_Indicators_of_Indian_Stock_Market.ipynb
├── 10_Historical_Data_Download.ipynb
├── 11_Candle_to_Heikin_Ashi_Conversion.ipynb
├── 12_Time_Frame_Change.ipynb
```

## 🔧 Requirements
- Python 3.7+
- Jupyter Notebook
- Kite Connect API
- Pandas, NumPy, TA-Lib, yfinance, matplotlib, etc.

```bash
pip install -r requirements.txt
```

## 🛠️ Setup & Usage

- Clone the Repository
```bash
git clone https://github.com/KshitizPandya/Stock_Trading_Automation.git
cd Stock_Trading_Automation
```

- Get Kite API Key
Register at https://developers.kite.trade and generate API credentials.
