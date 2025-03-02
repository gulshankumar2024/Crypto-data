# 📈 Live Cryptocurrency Data Tracker

This project fetches **live cryptocurrency data** for the top 50 coins, analyzes key metrics, and updates an **Excel file** every 5 minutes. It also generates an **analysis report** summarizing market trends.

---

## 🛠 Features
✅ Fetches **live cryptocurrency data** from the CoinGecko API  
✅ Extracts details like **price, market cap, trading volume, and % change**  
✅ Updates **Live_Crypto_Data.xlsx** every 5 minutes  
✅ Generates an **Analysis_Report.txt** summarizing:  
  - 🔝 **Top 5 Cryptos by Market Cap**  
  - 💰 **Average Price of Top 50 Cryptos**  
  - 📈 **Biggest 24-hour Gainer & Loser**  

---

## 🚀 Installation & Setup

### **1️⃣ Install Required Libraries**
Before running the script, install dependencies:
```sh
pip install requests pandas openpyxl schedule
