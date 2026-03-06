# Telegram Bot Starter

Your repository was effectively empty (only a `.gitkeep` placeholder), which is why you were not seeing any code on GitHub.

This commit adds a minimal Telegram bot starter so the repository contains real source code.

## Files

- `bot.py` – basic polling Telegram bot.
- `requirements.txt` – Python dependency list.

## Run locally

1. Create a bot with [@BotFather](https://t.me/BotFather) and copy your token.
2. Create and activate a virtual environment:

   ```bash
   python3 -m venv .venv
   source .venv/bin/activate
   ```

3. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

4. Export your token:

   ```bash
   export TELEGRAM_BOT_TOKEN="your-token-here"
   ```

5. Run the bot:

   ```bash
   python bot.py
   ```

The bot responds to `/start` and echoes text messages.
