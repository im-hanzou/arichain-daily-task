# AriChain Daily Task
AriChain Daily Task automated daily check-in and answer quiz using Telegram Bot By [MamangZed](https://github.com/mamangzed)
## Tools and components required
1. Ari Chain Account
   -  Download : [iOS](https://apps.apple.com/kr/app/ari-wallet/id6504207160) / [Android](https://play.google.com/store/apps/details?id=arichain.app.ari.wallet)
   -  Register and insert referral code: ``678d5b168b5a1``
2. VPS or RDP (OPTIONAL), Get free $200 credit [DigitalOcean](https://m.do.co/c/3f132e0f7e13) for 60 days here: [Register](https://m.do.co/c/3f132e0f7e13)
3. Node.js [v20.18.3](https://nodejs.org/en/blog/release/v20.18.3) (LTS) or Latest
4. Telegram [Chat ID](https://www.youtube.com/watch?v=b81_8ekbKpg&ab_channel=DhirajMediaAgency) and [BOT Token](https://www.youtube.com/watch?v=EOke01hZgZ0&ab_channel=UNgineering)
## Installation
- Tutorial how to create Telegram BOT and get the BOT TOKEN: [YouTube](https://www.youtube.com/watch?v=EOke01hZgZ0&ab_channel=UNgineering)
- Tutorial how to get your Telegram Chat ID: [YouTube](https://www.youtube.com/watch?v=b81_8ekbKpg&ab_channel=DhirajMediaAgency)
- Install Node.js For Windows: [Node.js](https://nodejs.org/dist/v20.18.3/node-v20.18.3-x64.msi)
- For Unix and Termux: [Node.js](https://www.digitalocean.com/community/tutorials/how-to-install-node-js-on-ubuntu-22-04)
- Don't Forget to Install GIT: ``apt install git``
- Download script [Manually](https://github.com/im-hanzou/arichain-daily-task/archive/refs/heads/main.zip) or use git:
```bash
git clone https://github.com/im-hanzou/arichain-daily-task
```
- Make sure you already in bot folder:
```bash
cd arichain-daily-task
```
- Install modules:
```bash
npm install
```
## Run the Bot
- Go to your Telegram Bot and chat `/start`
- Insert your Arichain email address in `accounts.json`:
>This script support multiple accounts
```bash
[
    {
        "email": "youremail@gmail.com"
    }
]
```
- Insert you Telegram Bot Token in `.env`:
```bash
TELEGRAM_ID=651XXXYOUR_TELEGRAM_CHATID
BOT_TOKEN=74151XXXX:AAEXXYOUR_TELEGRAM_BOT_TOKEN
```
- Run Command:
```bash
node index.js
```
- Answer the daily quiz everyday
# Notes
- Run this bot, use my referrer code if you don't have one.
- You can just run this bot at your own risk, I'm not responsible for any loss or damage caused by this bot.
- This bot is for educational purposes only.
