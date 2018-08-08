# Telegram interactive client

See Telethon

## To execute

You need a telegram API ID and Hash. Get it from https://my.telegram.org/auth?to=apps

```
export TG_API_ID=...
export TG_API_HASH=...
export TG_PHONE_NUMBER="+1...."

pip install asyncio telethon

git clone https://github.com/naiemk/telegram_scripts.git
cd telegram_scripts
python interactive_telegram_client.py
```

Select your chat, then use the `!h` command 

Change the line 152 (dialog_count) to a larger number if you don’t see your chat
