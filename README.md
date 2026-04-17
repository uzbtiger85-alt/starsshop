# ⭐ Star Shop Bot

Telegram bot for selling Stars, Premium and Gifts.

## 🚀 Deploy on Railway

1. Fork this repo
2. Go to [railway.app](https://railway.app) → New Project → Deploy from GitHub
3. Add environment variables in Railway dashboard (see below)

## ⚙️ Environment Variables

Copy `.env.example` to `.env` for local development:

```bash
cp .env.example .env
```

Then fill in your values:

| Variable | Description |
|---|---|
| `BOT_TOKEN` | Your bot token from @BotFather |
| `ADMIN_ID` | Your Telegram user ID |
| `CHAT_ID` | Target chat/channel ID |
| `CARD_NUMBER` | Payment card number |
| `ADMIN_USERNAME` | Admin Telegram username (without @) |
| `SUPPORT_USERNAMES` | Support usernames separated by comma |
| `REVIEW_CHANNEL_ID` | Review channel ID |

> ⚠️ **Never commit your `.env` file to GitHub!** It is already in `.gitignore`.

## 📦 Requirements

```bash
pip install -r requirements.txt
```

## ▶️ Run locally

```bash
python bot.py
```
