# Morning Aunty Bot
This telegram bot @morning-aunty-bot sends greetings with a cheerful message every morning to its users using Google Apps Script, powered entirely on Google infrastructure.

## ✨ Features

- Handles `/start` and `/subscribe` commands
- Logs user info (Telegram ID, name) into a linked Google Sheet
- Sends daily scheduled messages (quotes, greetings, reminders)
- Easy to extend with more commands or API integrations

## 🛠 Technology

- **Google Apps Script** – backend logic (JavaScript-based)
- **Google Sheets** – subscriber database
- **Telegram Bot API** – user interaction
  
## 🚀 How It Works

1. A user sends `/start` to the bot.
2. The bot stores their Telegram ID and name in a Google Sheet.
3. A time-based trigger sends daily messages to all subscribers.
