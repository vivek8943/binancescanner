# binancescanner
>DISCLAIMER:  I am in no way affiliated with Binance, use at your own risk. There are no warranties or guarantees expressed or implied. You assume all responsibility and liability.

Eyes everywhere! binancescanner is a price and volume scanner with customizable threshold notifications. It's good for monitoring fast moving markets. One part of the traderstoolkit coming soon.

### Optional Configuration

1. [Signup](https://www.binance.com/?ref=13223626) for Binance
1. Enable Two-factor Authentication
1. Go API Center, [Create New](https://www.binance.com/userCenter/createApi.html) Api Key

        [✓] Read Info [ ] Enable Trading [ ] Enable Withdrawals

1. Add API keys to BIscanner.py
1. Change trading pair from BTC to USDT, ETH or BNB

### Requirements
   
    High-speed Internet connection
	
    Python 3.6
        import time
		import sys
        import binance
        import twisted
        import colorama

### Usage
    python BIscanner.py

### Issues
    None as of yet.

### Support
If you need any help you can find me on:
- Discord: @krishtopher
- Telegram: @krishtopher

### Roadmap

binancescanner is currently in early testing stages but will be expanded.
    - Add docstrings
    - Graceful exception handling
    - Command line arguments for TRADING PAIR and THRESHOLDS
	- Remove the need for authentication

### traderstoolkit
> **testing for public release*

> ***in development*

traderstoolkit is a collection of scripts and tools to allow easier trading. Each tool will be released standalone as they are completed and the toolkit will be released as a whole at a later date.
## BITFINEX ONLY
- BFtrader.py* - multiple trades, single currency trading bot

- BFarbv1.py* - arbitrage calculator for multiple currencies

- BFarbv2.py** - arbitrage calculator for multiple currencies with built-in trader

***

## BINANCE ONLY
- BIscanner.py - eyes everywhere! price and volume scanner with customizable threshold notifications

- BIarbv1.py** - arbitrage calculator for multiple currencies

- BIarbv2.py** - arbitrage calculator for multiple currencies with built-in trader

***

## BITMEX ONLY
- BMtrader.py** - single trade, single currency (XBTUSD) trading bot

## GLOBAL
- sentiment.py* - configurable real time sentiment analysis of tweets associated with particular cryptocurrencies (susceptible to spam tweets/bots)

### Donate

If this library helped you out feel free to donate. 

- ETH: 0x1f9145dA965506e41924460Dd86E60ce1083be6c
- LTC: MDfztCZvet4jGFFUbi8TwNts3uayZmGebJ
- BCH: 19iLgsCkXQY8wJXqnRVN64kL5pWs2bLqbW
- BTC: 3BZg92TdEW3utKy5ErDtV2kbdGtK33Z9CB