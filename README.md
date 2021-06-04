
# GitHub-Webhook-Bot 🤖
Simple Telegram Bot, which will listen to GitHub Webhook and inform via Telegram


## Setting Up Config ✍
1) Go to `src/helper.h` ---> [Here](https://github.com/gautamajay52/GitHub-Webhook-Bot/blob/main/src/helper.h#L10)
2) Edit your Bot Token.
3) Edit your ID.
4) Add your PORT.
5) Add your forwading url in webhook section of your repo.
    ```bash
    https://your-forwading-url/github
    ```
6) Set your webhook(Only if you wanted to receive `/start` command feedback)
    ```bash
    curl "https://api.telegram.org/bot<BOT_TOKEN>/setWebhook?url=https://your-forwading-url/telegram"
    ```


## To Build and Run: 🏃‍♂

```bash
# cloning repo
git clone https://github.com/gautamajay52/GitHub-Webhook-Bot
cd GitHub-Webhook-Bot

# Installing Requirements
sudo apt-get install libboost-all-dev

# To Build
g++ src/main.cpp -lpthread -lboost_system -lz -o git.out

# To Run
./git.out

```

## Easy 👌
[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy)

## Credits: 🌎
* [GautamKumar(me)](https://github.com/gautamajay52) for [Nothing](https://github.com/gautamajay52/GitHub-Webhook-Bot)😬
* [CrowCpp](https://github.com/crowcpp/crow) for [crow_all.h](https://github.com/gautamajay52/GitHub-Webhook-Bot/blob/main/src/crow_all.h) 😁
