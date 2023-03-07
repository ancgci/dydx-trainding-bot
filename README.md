# dydx-trainding-bot
Bot to interage with Dydx -


This bot was developed by my professor in a course I finished today (07/03/23). If you want more details where to get this course, call me on telegram (ancgci).
This DYDX bot can work locally, but I recommend running it in your preferred cloud.
He operates a different type of arbitrage. It can be used with the Testnet Goerli network. It is configured to alert on telegram when it starts.
##IF YOU USE THIS BOT IT IS AT YOUR OWN RISK##


/// Need create .env file to this bot operate with this detail: ///


# WALLET PRIVATE KEY
ETH_PRIVATE_KEY =  "your key"

#KEYS - Production
#Must to be on Mainnet ON DYDX
STARK_PRIVATE_KEY_MAINNET = "request me in private how get this"
DYDX_API_KEY_MAINNET = "request me in private how get this"
DYDX_API_SECRET_MAINNET = "request me in private how get this"
DYDX_API_PASSPHRASE_MAINNET = "request me in private how get this"

#KEYS - Developement
#Must to be on Testnet on DYDX
STARK_PRIVATE_KEY_TESTNET = "request me in private how get this"
DYDX_API_KEY_TESTNET = "request me in private how get this"
DYDX_API_SECRET_TESTNET = "request me in private how get this"
DYDX_API_PASSPHRASE_TESTNET = "request me in private how get this"

# TELEGRAM ITEMS
TELEGRAM_TOKEN = "request me in private how get this"
TELEGRAM_CHAT_ID = "request me in private how get this"

"https://api.telegram.org/bot{bot_token}/sendMessage?chat_id={chat_id}&text={message}"


/// Need create cron File: /// 

Do you choose time:

CRON item - Daily

0 12 * * *   python3 dydx_bot/program/main.py > output.txt  2>&1

CRON item - 5 Mins

*/5 * * * *  python3 dydx_bot/program/main.py > output.txt  2>&1


/// To contat me ///

- telegram (ancgci)
