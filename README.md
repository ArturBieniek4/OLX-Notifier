# OLX-Notifier
## Features
 - Checks for offers matching your criteria every 5 minutes and notifies you when new offers are found
 - Filters a keyword and the price boundaries manually, because OLX likes to put irrelevant results on your search
 - Keeps track of found offers, so only new offers are shown
## How to use
 - `git clone https://github.com/ArturBieniek4/OLX-Notifier.git`
 - Create a Telegram bot, put `TELEGRAM_TOKEN` and `TELEGRAM_CHAT_ID` in `.env` file
 - Modify `searches.json` for your own needs
 - Run `python3 main.py`