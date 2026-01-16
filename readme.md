# Stock Market Analysis Dashboard

A Streamlit web application for analyzing stocks with real-time Yahoo Finance data, technical indicators, and price forecasting.

## Features

- Real-time Stock Data from Yahoo Finance
- Technical Indicators (SMA 20/50, RSI 14, MACD)
- Volume Analysis with color-coded charts
- 30-day Price Forecasting
- Portfolio Comparison for multiple stocks
- Statistical Analysis (volatility, skewness, kurtosis)

## Quick Start

1. Clone the repository:
   ```bash
   git clone https://github.com/saimtec/Stock-Market-Analysis.git
   cd Stock-Market-Analysis

   Create virtual environment:
    pip install -r requirements.txt

Activate virtual environment:

Windows: .venv\Scripts\activate
Linux/Mac: source .venv/bin/activate
Install dependencies:

Run the app:

Requirements
Python 3.10+
streamlit
pandas
numpy
matplotlib
yfinance

Project Structure:

Stock-Market-Analysis/
├── [app.py](http://_vscodecontentref_/0)              # Main Streamlit application
├── [requirements.txt](http://_vscodecontentref_/1)    # Python dependencies
├── [README.md](http://_vscodecontentref_/2)           # Documentation
└── .gitignore          # Git ignore file


Supported Stock Symbols
* AAPL - Apple
* GOOGL - Google
* MSFT - Microsoft
* AMZN - Amazon
* TSLA - Tesla
* META - Meta
* NVDA - NVIDIA
* JPM - JPMorgan



Author
GitHub: saimtec

Run the app:
streamlit run app.py