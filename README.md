# Real-time stock price tracker with alert system (Python)
📈 Real-Time Stock Market Tracker
🚀 Overview
This project is a Real-Time Stock Market Tracker that fetches live stock prices, sends email alerts when a target price is reached, and visualizes stock performance over the past week.

🔥 Features
✅ Live Stock Price Tracking – Fetches real-time stock prices using yfinance
✅ Email Alerts – Sends an email notification when the stock price crosses a target threshold (smtplib)
✅ Stock Price Visualization – Displays last week's stock performance with matplotlib

🛠️ Tech Stack
Python 🐍
yfinance – Fetches stock market data
matplotlib – Visualizes stock trends
smtplib – Sends email alerts
time – Automates periodic stock price checks
📊 How It Works
1️⃣ Choose a Stock (e.g., AAPL, TSLA, GOOG)
2️⃣ Set a Target Price – The system will monitor price changes
3️⃣ Get Notified via Email when the stock reaches your target price
4️⃣ Visualize Stock Trends – See how the stock performed over the last 7 days

🔧 Installation & Usage
Install Dependencies
pip install yfinance matplotlib
Run the Script
python stock_tracker.py
📩 Email Alerts Setup
To enable email alerts, update the script with your SMTP credentials (use an App Password for Gmail).
