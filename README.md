# TELEGRAM WHALE ALERT BOT
This repo help everyone running a custom telegram whale alert bot for any token on Ethereu, BSC, Base

## 1. Prepare telegram bot and telegram channel
- Open telegram
- Chat with @BotFather
- Type command `/newbot`
- Save telegram bot token to TELEGRAM_BOT_TOKEN in .env
- Create a new telegram channel
- Add above telegram to channel as admin
- Chat with @username_to_id_bot
- Enter telegram channel name to get CHAT_ID, saving to TELEGRAM_CHAT_ID to .env

## 2. Get API key from txdecoder.xyz
- Go to https://txdecoder.xyz
- Sign in with Google
- Upgrade account to Plan that support Websocket. https://txdecoder.xyz/#pricing
- Get API key , saving to TXDECODER_API_KEY in .env

## 3. Run
- Clone this repo
- Run below command

```bash
npm install
cp .env.sample .env
```

- Update .env file
```bash
TELEGRAM_BOT_TOKEN=
TELEGRAM_CHAT_ID=
TXDECODER_API_KEY=

# Token CAKE
TOKEN_ADDRESS=0x0E09FaBB73Bd3Ade0a17ECC321fD13a19e81cE82
# min value 10_000 USD
THRESHOLD_VALUE_USD=10000
```