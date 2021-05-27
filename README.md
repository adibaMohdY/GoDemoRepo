# GoDemoRepo

testing


GoDemoRepo/.github/workflows/
1. CI.yml
2. CD.yml
3. notify.yml : send a telegram notifcation when there is a push notification
      - create a new bot via @BotFather to receive token
      - creating a chat group and inviting bot into it
      - get ID of chat group via https://api.telegram.org/bot<TELEGRAM_TOKEN>/getUpdates
      - create and save secrets in Settings,
              secrets.TELEGRAM_TO == ID of chat group
              secrets.TELEGRAM_TOKEN == token

