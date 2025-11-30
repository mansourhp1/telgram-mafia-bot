# Telegram Mafia Bot

A simple PHP Telegram bot for playing Mafia game in Telegram groups.

## Features

- Start and manage Mafia game sessions
- Assign roles to users
- Handle day/night cycles
- Vote to eliminate players

## Setup

1. Clone the repo
2. Set your Telegram Bot Token in config.php
3. Upload to a PHP server
4. Set the webhook using Telegram API:

```bash
https://api.telegram.org/bot<YOUR_BOT_TOKEN>/setWebhook?url=https://yourdomain.com/bot.php
