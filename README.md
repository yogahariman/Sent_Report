# Sent_Report
Source : https://medium.com/@robertbracco1/how-to-write-a-telegram-bot-to-send-messages-with-python-bcdf45d0a580

1. Create New Bot
  https://telegram.me/BotFather
  Send the message “/newbot”
2. Install telegram-send and link it to your bot:
  pip install telegram-send
  telegram-send --configure
3. Send a test message from your python code
  import telegram_send
  telegram_send.send(messages=["Hello!"])
4. 
