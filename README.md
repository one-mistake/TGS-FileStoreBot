# PyroFilesStoreBot

This is Telegram Parmanent Files Store Bot by [@](https://github.com/one-mistake).

- **Language:** [Python3](https://www.python.org)
- **Library:** [Pyrogram](https://docs.pyrogram.org)

### Features:

- In PM Just Forward or Send any file it will save on Database & give you the Access Link.
- In Channel Add Bot as Admin with Edit Rights. When you will send any file or media in Channel it will Edit the Broadcast Message with Saved Link Button.
- You can also Broadcast anythings via this Bot.
- You can also Do Force Sub to a Channel to allow access the Bot.
- Save Multiple Files in Same Link. (Batch)

### Demo Bot:

<a href="https://t.me/TGS_FileStoreBot"><img src="https://img.shields.io/badge/Demo-Telegram%20Bot-blue.svg?logo=telegram"></a>

## Configs:

- `API_ID` - Get this from [Telegram](https://my.telegram.org)
- `API_HASH` - Get this from [Telegram](https://my.telegram.org)
- `BOT_TOKEN` - Get this from [@BotFather](https://t.me/BotFather)
- `BOT_USERNAME` - You Bot Username. _(Without [@])_
- `DB_CHANNEL` - A Telegram Channel ID.
  - Make a Channel for Storing Files. We will use that as Database. Channel must be Private! Else you will be Copyright by [Telegram DMCA](https://t.me/dmcatelegram)!
- `BOT_OWNER` - Bot Owner UserID
  - Put your Telegram UserID for doing Broadcast.
- `DATABASE_URL` - MongoDB Database URL
  - This for Saving UserIDs. When you will Broadcast, bot will forward the Broadcast to DB Users.
- `UPDATES_CHANNEL` - Force Sub Channel ID _(Optional)_
  - ID of a Channel which you want to do Force Sub to use the bot.
- `LOG_CHANNEL` - Logs Channel ID
  - This for some getting user info. If any new User added to DB, Bot will send Log to that Logs Channel. You can use same DB Channel ID.
- `FORWARD_AS_COPY` - Value should be `True` or `False` _(Optional)_
  - If `True` all messages will be forwarder _As Copy_. If `False` all messages will be forwarder with Forward Tag.
- `BROADCAST_AS_COPY` - Value should be `True` or `False` _(Optional)_ - Broadcast with Forward Tag or as Copy._(Without Forward Tag)_
- `BANNED_USERS` - Banned unwanted members - Put all banned user IDs & Separate with space.
- `BANNED_CHAT_IDS` - All Banned Channel IDs _(Optional)_
  - Put all banned channel IDs & Separate with space.

### Deploy Now:

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/one-mistake/TGS-FileStoreBot)

## Commands:

```
start - start the bot
clear_batch - Clear User Batch Files
status - Show number of users in DB [Owner Only]
broadcast - Broadcast replied message to DB Users [Owner Only]
ban_user - [user_id] [ban_duration] [ban_reason] Ban Any User [Owner Only]
unban_user - [user_id] Unban Any User [Owner Only]
banned_users - Get All Banned Users [Owner Only]
```

### Support Group:

<a href="https://t.me/HackingCraze24_7d"><img src="https://img.shields.io/badge/Telegram-Join%20Telegram%20Group-blue.svg?logo=telegram"></a>
