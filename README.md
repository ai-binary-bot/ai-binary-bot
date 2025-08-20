I# AI Binary Bot 🤖📈

**Automated Binary Options Trading Bot for Pocket Option**

This bot allows you to run **fully automated trades** on [Pocket Option](https://pocketoption.com) using Python + Selenium.  
It can be deployed **24/7** on Render, Replit, or any VPS.

---

## 🚀 Features
- 🔄 24/7 trading using Render **Background Worker**
- 🐍 Built with **Python 3 + Selenium**
- ⚙️ Easy configuration via **environment variables**
- 📊 Supports **Demo & Real accounts**
- ⏱️ Trade expiry times: `15s | 30s | 1m | 5m`
- 🔐 Secured with Telegram ID restriction
- ✅ Confirmation button before executing trades
- 📲 100% mobile-ready (via Telegram bot)

---

## 🛠️ Setup Guide

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/YOUR-USERNAME/ai-binary-bot.git
cd ai-binary-bot
ai-binary-bot/
│
├── bot.py                # Main bot script, e tsamaisa trades ka Pocket Option
├── requirements.txt      # Full dependencies
├── README.md             # Project description e lokisitsoeng
├── config.json           # Pocket Option login & settings
├── .env.example          # Example environment variables
└── utils/
    ├── po_api.py         # Functions tsa Pocket Option API
    └── helpers.py        # Functions tse thusang trading logic
