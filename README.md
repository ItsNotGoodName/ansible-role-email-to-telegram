# role-email-to-telegram

Ansible role for setting up [email-to-telegram](https://github.com/ItsNotGoodName/email-to-telegram) on Debian 10.

## Variables
```yaml
# Token from BotFather
telegram_token: 12345678

telegram_transfers:
- { to_address: channel1@telegram.lan, chat_id: -1001111111111 }
- { to_address: channel2@telegram.lan, chat_id: -1002222222222 }
```
