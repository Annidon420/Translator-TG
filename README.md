# Telegram Translation Bot

A Telegram bot that allows users to translate messages into selected languages. Supports forwarding messages and writing messages in their own language to convert to a selected language.

## Features

- Forward any message to translate it.
- Send text in your language to translate to the selected target language.
- Set target language using /setlang command.
- Supports over 1000 languages (via deep-translator library).

## Setup

1. Install dependencies: `pip install -r requirements.txt`
2. Get a bot token from [@BotFather](https://t.me/botfather) on Telegram.
3. Replace `"YOUR_BOT_TOKEN"` in `main.py` with your actual token.
4. Run the bot: `python main.py`

## Usage

- /start: Start the bot and get instructions.
- /setlang <code>: Set the target language (e.g., /setlang es for Spanish).
- /langs: List all supported languages.
- Forward a message or send text to translate it.

## Dependencies

- python-telegram-bot
- deep-translator