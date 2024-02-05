# Telegram Bot Template

This Python-based Telegram bot is a basic template for building more advanced Telegram bots.

## Features

- Logging: Comprehensive logging of bot activities, including command usage and execution outcomes, to a file named `bot_activity.log`.
- Environment Variable Management: Utilizes `.env` for secure storage and retrieval of essential configurations like Telegram bot token and allowed user ID.
- Command Handling: Supports several commands for user interaction:
  - `/start` - Initiates interaction with the bot, restricted to an authorized user.
  - `/chatid` - Provides the user with their chat ID.

## Setup
### Prerequisites

- Python 3.x
- `python-telegram-bot` library
- `python-dotenv library` for environment variable management

### Installation

1. Clone the repository to your local machine.
2. Install the required Python packages using `pip`:

```
pip install python-telegram-bot python-dotenv
```

3. Create a `.env` file in the root directory of the project with the following variables:

```
TELEGRAM_BOT_TOKEN=your_bot_token_here
TELEGRAM_ALLOWED_ID=your_telegram_user_id_here
```

4. Replace `your_bot_token_here` and `your_telegram_user_id_here` with your actual Telegram bot token and Telegram user ID, respectively.

### Usage

1. Start the bot by running the script:

```
python telegram_display_bot.py
```

2. Interact with the bot via the supported commands in a Telegram chat.

## Security

This bot is configured to respond only to commands from a specified Telegram user ID, set through the environment variable `TELEGRAM_ALLOWED_ID`. Ensure this ID and access to your Telegram account is kept secure and not shared with unauthorized individuals. Ensure access to all other related hardware is managed as

## Logging

Activity logging is enabled by default, with logs stored in `bot_activity.log`. These logs provide insights into bot usage and help with troubleshooting.

## Contributing

Contributions to enhance the bot's functionality or address issues are welcome, but I have no prior experience with managing contributions.

## License

This project is open-source and available under MIT License.

## Disclaimer

This bot is developed for educational and personal use. The author is not responsible for any misuse or damage caused by this software. Always ensure you have permission to run .bat files and modify display configurations on the target machine.
