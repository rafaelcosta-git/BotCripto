# 🤖 BotCripto

A cryptocurrency trading bot built with Node.js and the Binance Testnet API.

The project automatically monitors Bitcoin market data, calculates a Simple Moving Average (SMA), and executes buy or sell orders based on predefined trading conditions.

## 🚀 Features

* Real-time cryptocurrency market monitoring
* Integration with Binance Testnet API
* Automated buy and sell order execution
* Simple Moving Average (SMA) strategy
* Secure API key management using environment variables
* Automated trading decisions based on market conditions

## 🛠️ Technologies Used

* Node.js
* JavaScript
* Binance API
* Axios
* Dotenv
* Crypto Module

## ⚙️ How It Works

The bot continuously retrieves BTC/USDT market data from the Binance Testnet.

1. Fetches the latest candlestick data.
2. Calculates a 21-period Simple Moving Average (SMA).
3. Compares the current market price with the SMA.
4. Executes a buy order when the price falls significantly below the average.
5. Executes a sell order when the price rises significantly above the average.

This strategy demonstrates how automated systems can react faster than manual trading by processing market data and executing actions in real time.

## 🔐 Security

API credentials are stored securely using environment variables through a `.env` file and are never exposed in the source code.

## 📚 What I Learned

Through this project I gained practical experience with:

* REST APIs
* HTTP requests (GET and POST)
* Real-time data processing
* Algorithmic trading concepts
* Environment variable management
* Automation workflows
* External service integration

## Future Improvements

- RSI indicator integration
- MACD strategy implementation
- Stop-loss and take-profit mechanisms
- Trading performance dashboard
- Web-based monitoring interface
- Multiple cryptocurrency support

## 👨‍💻 Author

Rafael Costa

GitHub: https://github.com/rafaelcosta-git
