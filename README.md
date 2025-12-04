# Weather & Airport Info Telegram Bot

A Telegram bot and API designed to provide convenient local airport weather information. Currently, it supports retrieving current weather, METAR, and TAF data for airports.

This project is ideal for developers who want to integrate aviation weather information into their apps or Telegram bots.

## Features

Query local airport weather information

Retrieve METAR reports

Retrieve TAF forecasts

Easy-to-use API for developers

Telegram bot integration for quick access

## Installation & Setup

Clone the repository

```bash
git clone git@github.com:ronkaotw/weather_bot.git
cd weather_bot


Install dependencies

npm install


## Start the server

npm run start
### or for development with auto-reload
nodemon index.js
```
## Usage

Once the bot/server is running, you can query local airport weather, METAR, and TAF.

Example Telegram commands:

/airport [airport_code] → get airport info

/metar [airport_code] → get METAR report

/taf [airport_code] → get TAF forecast

/airmet [airport_code] → get airmet weather

/dev [airport_code] → get dev info

## Notes

AIRMET data is currently only available for the Americas. Other regions are under development.

Please refer to the following resources for API limitations and reference:

node-telegram-bot-api

CheckWX API

## Tech Stack

Node.js

Telegram Bot API (node-telegram-bot-api)

CheckWX API (for METAR/TAF data)

Optional: nodemon for development

## Author

@ronkaotw