# 🚗 Car Service Tracker Bot

## Setup on Render (Web Service)

1. Create new **Web Service** on Render (not Background Worker)
2. Build: `pip install -r requirements.txt`
3. Start: `python bot.py`
4. Add env vars: BOT_TOKEN, OWNER_CHAT_ID
5. Deploy!

## Important

- Use **Web Service** not Background Worker
- Flask keeps the service alive
- Bot runs in background thread
