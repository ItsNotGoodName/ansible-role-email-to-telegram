# role-email-to-telegram

Ansible role for setting up 
[email-to-telegram](https://github.com/ItsNotGoodName/email-to-telegram) on 
Debian 10.

## Variables
```yaml
# API token from BotFather
telegram_token: 12345678

# Matches mail's to_address to a group/channel/chat with chat_id
# (The bot must be part of the group/channel/chat to be able to send messages)
telegram_transfers:
- { to_address: channel1@telegram.lan, chat_id: -1001111111111 }
- { to_address: channel2@telegram.lan, chat_id: -1002222222222 }
```
