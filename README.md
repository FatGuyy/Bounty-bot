# No he wasn't

# This is something new


> A GitHub App built with [Probot](https://github.com/probot/probot) that A bot that dispatches event based on pr messages

## Setup

```sh
# Install dependencies
npm install

# Run the bot
npm start
```

## Docker

```sh
# 1. Build container
docker build -t bounty-bot .

# 2. Start container
docker run -e APP_ID=<app-id> -e PRIVATE_KEY=<pem-value> bounty-bot
```
