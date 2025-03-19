# Zerodha Trading Strategies and Backtesting

## About the Project
This repository is a collection of Python-based trading strategies and backtesting programs, developed as part of my Computer Science Engineering (CSE) tenure at UIET Kurukshetra University in 2018. The project focuses on automated and manual live trading on the NSE-BSE markets using Zerodha's API. It incorporates Artificial Intelligence techniques to execute trades based on various technical indicators.

The repository consists of:
- **Live trading bots**
- **Backtesting programs**
- **Stock screeners**
- **Technical indicator implementations**
- **Historical data downloaders**

## Features
- **Live Trading Bots:** Automated and manual trading bots utilizing technical strategies.
- **Backtesting Programs:** Test trading strategies on historical data.
- **Stock Screener:** Scans stocks based on Guppy and other technical indicators.
- **Technical Indicators:** Implementation of popular stock market indicators.
- **Data Conversion:** Converts candlestick data to Heikin-Ashi format.
- **Time Frame Adjustments:** Custom time frame modifications for analysis.

## Files and Notebooks

| File Name | Description |
|-----------|-------------|
| **1)_Getting_Started_with_Zerodha_.ipynb** | Introduction and setup guide for Zerodha API |
| **BACKTESTIG_PROGRAM_.ipynb** | Backtesting any stock's buy/sell strategy on historical data |
| **Buy on RSI when the current high of candle is more than previous high of candle.ipynb** | Buy order based on RSI when RSI > 50 |
| **Hisorical_Data_Download_of_stocks.ipynb** | Code to download historical data for any stock |
| **Live_BOT_(1)_on_RSI_.ipynb** | Live trading bot based on RSI strategy |
| **Live_BOT_(2)_on_GUPPY_with_screener.ipynb** | Manual input Guppy strategy bot |
| **Live_BOT_(3)_Guppy_Automated_.ipynb** | Fully automated Guppy strategy bot |
| **Live_BOT_(4)_advance_bot_multiple_bot_working_in_single_bot_.ipynb** | Mini Guppy bot with backtesting, screener, and indicators |
| **Live_BOT_(5).ipynb** | Mini Guppy bot with stock tracking features |
| **Stock_Screener_(GUPPY)_.ipynb** | Stock screener scanning multiple stocks based on Guppy strategy |
| **Technical_Indicator's_of_Indian_Stock_market.ipynb** | Implementation of key technical indicators for Indian stock market |
| **change time frame.ipynb** | Adjusts time frames for Zerodha trading |
| **conversion code of Candles to hikenashi.ipynb** | Converts candlestick data into Heikin-Ashi format |
| **order_information.jpg** | Image related to order placement |

## Technologies Used
- **Python**
- **Zerodha API (Kite Connect)**
- **Pandas & NumPy**
- **Matplotlib & Seaborn**
- **TA-Lib (Technical Analysis Library)**
- **REST API & Websockets**

## Setup Instructions
1. Install required dependencies:
   ```sh
   pip install kiteconnect pandas numpy matplotlib seaborn TA-Lib
   ```
2. Get API credentials from Zerodha and configure them.
3. Run the desired Jupyter Notebook.

## License
This project is for educational and research purposes only. Live trading involves financial risks, and users should trade responsibly.

## Author
Developed as part of my academic and professional exploration into AI-driven stock trading strategies.

Feel free to explore and contribute! 🚀

