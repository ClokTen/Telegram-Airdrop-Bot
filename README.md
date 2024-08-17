# ClokTen Telegram Airdrop Bot

This Telegram bot collects wallet addresses from users in my Clokten Telegram channel and allows you to export the collected addresses to a CSV file.

## Features

- Collect wallet addresses from users.
- Validate addresses (customizable).
- Export collected addresses to a CSV file.

## Getting Started

### 1. Create a Telegram Bot

1. **Chat with [BotFather](https://t.me/botfather)** on Telegram.
2. Use the `/newbot` command to create a new bot and obtain your API token.

### 2. Clone the Repository

Clone this repository to your local machine:

```bash
git clone https://github.com/yourusername/clokten-airdrop-bot.git
cd clokten-airdrop-bot
```

### 3. Install Dependencies

Ensure you have Python installed. Install the required Python package:

```bash
pip install python-telegram-bot
```

### 4. Configure the Bot

Open `bot.py` and replace `'YOUR_API_TOKEN'` with your actual Telegram bot API token:

```python
API_TOKEN = 'YOUR_API_TOKEN'
```

### 5. Run the Bot

Execute the bot script:

```bash
python bot.py
```

### 6. Add the Bot to Your Channel

1. Add the bot to your Clokten Telegram channel or group.
2. Ensure the bot has permissions to send messages in the channel.

### 7. Using the Bot

- **Start Interaction**: Users can start interacting with the bot by sending `/start`.
- **Send Wallet Address**: Users paste their wallet address into the chat.
- **Export CSV**: As an admin, use the `/export` command to generate and download a CSV file with all collected addresses.

### Example Commands

1. **/start**: Start interaction with the bot.
2. **Send Wallet Address**: Paste the wallet address directly.
3. **/export**: Export collected wallet addresses to `wallet_addresses.csv`.
