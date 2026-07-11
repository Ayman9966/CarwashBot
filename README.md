# 🚗 Car Service Tracker Bot

Telegram bot for tracking car service orders with custom pricing.

## Setup on Render

1. Create a new **Background Worker** on Render
2. Upload this ZIP or connect GitHub repo
3. Add Environment Variables:
   - `BOT_TOKEN` = your token from @BotFather
   - `OWNER_CHAT_ID` = your ID from @userinfobot
4. Deploy!

## Features

- ✅ Clean chat (single message)
- ✅ Custom price confirmation (10s timer)
- ✅ Daily CSV backup
- ✅ Restore from backup
- ✅ Delete confirmation
- ✅ Auto-return to main menu

## Edit Services

Open `bot.py` and edit the `SERVICES` dict to change prices and categories.

## Data Files

- `orders.json` — main data
- `backups/` — CSV backups
