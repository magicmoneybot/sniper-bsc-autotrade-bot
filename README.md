<div align="center">
    <img src="https://i.imgur.com/mF3T0jn.png">
    <h3 align="center">Eryx - PancakeSwap Sniper</h3>
    <p align="center">
        Simple yet fast and efficient PancakeSwap sniper-bot running on the Binance Smart Chain.
        <hr>
        <a href="#getting-started">⬇️ Download Lite Version</a>
        /
        <a href="https://github.com/magicmoneybot/sniper-bsc-autotrade-bot/issues">🐞 Report a bug</a>
        /
        <a href="https://github.com/magicmoneybot/sniper-bsc-autotrade-bot/issues">🆕 Request a feature</a>
    </p>
</div>

## Table Of Contents

<ul>
    <li>
		<a href="#description">Description</a>
		<ul>
			<li><a href="#features">Features</a></li>
		</ul>
	</li>
    <li>
        <a href="#getting-started">Getting started</a>
        <ul>
            <li><a href="#requirements">Requirements</a></li>
            <li><a href="#installation">Installation</a></li>
            <li><a href="#configuration">Configuration</a></li>
        </ul>
    </li>
	<li><a href="#go-premium">Go Premium</a></li>
</ul>


## Description
![Alt Text](https://i.imgur.com/N2STawe.gif)

A fast and efficient bot written in NodeJS to automatically buy and sell tokens on the Binance Smart Chain as soon as liquidity is added and trade is enabled.
<br><br>
The bot is extremely fast as long as you use a **good** node and not a public one. With a node from Quicknode you can expect a buy/sell transaction in less than 5 seconds.
<br><br>
The bot uploaded on github is the **lite** version of the real bot. 
You do **not** get all of the features from the premium version.
### Features

Current features supported by the **lite** version:

- [x] Buying
- [x] Block-offset system
- [x] Liquidity sniper

Additional features supported by the **premium** version:
- [x] Auto / manual selling
- [x] Tax checker
- [x] Auto updates (updates are done automatically without the need of a re-download)
- [x] Support
- [x] Trailing auto-sell.
- [x] Sell using a delay
- [x] Multi-blockchain support.
- [x] Other liquidity sniping methods.
- [x] Contract analyzer.

## Getting Started
### Requirements
<ul>
    <li>Windows 10 / Ubuntu / Mac OS</li>
	<li>Latest <a href="https://nodejs.org/en/download/">NodeJS</a> installed.</li>
	<li>Latest <a href="https://git-scm.com/downloads">Git</a> installed.</li>
	<li>A <b>decent</b> internet connection.</li>
	<li>
		A <b>decent</b> BSC node, preferably paid, but you may also use free ones.
		<ul>
			<li><a href="https://www.quicknode.com/">Quicknode (paid)</a></li>
			<li><a href="https://www.moralis.io/">Moralis (free)</a></li>
		</ul>
	</li>
	<li>A BSC wallet with a private key. (it is recommended to create a new wallet to use with this bot)</li>
</ul>

### Installation

1. Download and install NodeJS from <a href="https://nodejs.org/en/download/">here</a>.
2. Download and install Git from <a href="https://git-scm.com/downloads">here</a>.
3. Open a command prompt / terminal and clone the repository.
	```sh
	git clone https://github.com/magicmoneybot/sniper-bsc-autotrade-bot.git && cd snipr
	```
4. In the same command prompt, install the NPM packages.
	```sh
	npm install
	```
5. That's it! Time for configuration. 🎉

### Configuration

```ini
[SNIPER]

; DO NOT REMOVE.
IDENTIFIER=#token

[WALLET]
; This is your BSC wallet's private key.
SECRET_KEY=private_wallet_key

; The uptime of this node is pretty bad, you should consider using a private node.
WSS_NODE=wss://bsc-ws-node.nariox.org:443


[CONTRACTS]
; These variables support two pre-defined contracts (WBNB & BUSD). 
; For other contracts you'll have to specify the contract address yourself.
INPUT=WBNB
OUTPUT=BUSD


[TRANSACTION]

GAS_LIMIT=500000
GAS_PRICE=5

; This variable is the amount of crypto you wish to use with the input contract.
; If for example you use WBNB as input, you will have to use WBNB's format.
AMOUNT_IN=0.0033

BUY_SLIPPAGE=10
```

## Go Premium

<p>
	The premium version comes with a <b>one-time</b> fee of <b>$200.00</b> (BNB/BUSD).<br>
	You can see all of the features <a href="#features">here</a>.<br><br>
	If you wish to purchase the premium version of the bot, please contact me using the contact method listed below.
</p>

### Contact
<ul>
	<li>Discord: magicmoneybot#2677</li>
</ul>
