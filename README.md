<p align="center">
  <img src="./logo.png" width="200" title="RouletteBot" alt="RouletteBot">
</p>

# Discord Bot Template
A Discord bot template for deployment on Heroku.

## Add to Server
<a href="ADD_YOUR_BOT_URL_HERE">
    <img src="https://discord.com/assets/e4923594e694a21542a489471ecffa50.svg" alt="Discord link" width="150"/>
</a>

NOTE: I recommend hosting this bot yourself with the Heroku One-Click deploy button below, as I will most likely be shutting down my own instance until I need to use it. 

## Deployment
[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/contejus/DiscordBotTemplateHeroku/tree/master)

## Setup
1. Clone repository using `git clone https://github.com/contejus/DiscordBotTemplateHeroku.git`.
2. Change directory using `cd DiscordBotTemplateHeroku/`
3. Create a `.env` file with the following contents:
    `DISCORD_TOKEN=<YOUR_DISCORD_TOKEN_HERE>`
4. Create a Discord bot and Discord API token using the Discord Developer Portal, as well as a custom invite to allow the bot to join your server.
5. Create a virtual environment with `python -m venv venv`.
6. Activate virtual environment with `source venv/bin/activate` on Linux or `source venv/Scripts/activate` on Windows.
7. Install requirements with `pip install -r requirements.txt`.
8. Run the bot with `python bot.py`.
