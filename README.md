# Telegram bot 
Telegram bot for getting detailed information about TV programs from the website tvmaze.com

### Installation
```
pip install tvmazetgbot
pip install git
```

### Get started
*How to work with this lib:*
* you can start bot in terminal:
`pytnon -m tvmazetgbot -t <TELEGRAM_TOKEN>`
* Or import Bot class from library:


```Python
from tvmazetgbot import Bot

tg_bot = Bot(token="TELEGRAM_TOKEN")
tg_bot.start()
```