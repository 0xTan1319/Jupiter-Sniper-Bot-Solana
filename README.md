<div align="center">
    <h1>📟 JUPITER TOKEN SNIPER🪐</h1>

https://github.com/0xTan1319/jupiter-python-cli/assets/152310566/81f79ed5-8c47-469f-aeb8-c3be70c9541f

</div>

---

<p align="center">
    <img src="https://img.shields.io/github/stars/0xTan1319/jupiter-python-cli">
    <img src="https://img.shields.io/github/forks/0xTan1319/jupiter-python-cli">
    <br>
    <img src="https://img.shields.io/github/issues/0xTan1319/jupiter-python-cli">
    <img src="https://img.shields.io/github/issues-closed/0xTan1319/jupiter-python-cli">
    <br>
    <img src="https://img.shields.io/github/languages/top/0xTan1319/jupiter-python-cli">
    <img src="https://img.shields.io/github/last-commit/0xTan1319/jupiter-python-cli">
    <br>
</p>

# 📖 Introduction
**Jupiter Python CLI** is a Sniper bot that sniper all the tokens on  **[Jupiter](https://jup.ag/) features** including a **Fast** sniper.<br>

# ⚠️ Disclaimer
**Please note that I'm not responsible for any loss of funds, damages, or other libailities resulting from the use of this software or any associated services.<br>
This tool is provided for educational purposes only and should not be used as financial advice, it is still in expiremental phase so use it at your own risk.**

# ✨ Quickstart

This project has been made for Python 3.11

## 🛠️ Installation

💾 **Clone this repository**
```sh
git clone github.com/0xTan1319/Jupiter-Sniper-Bot-Solana
```
💻 **Create a virtual environnment**
```sh
python -m venv venv
```
🌐 **Activate Virtual Environnement**
```sh
.\venv\Scripts\Activate.ps1
```
▶️ **Start CLI**
```sh
python main.py
```

# 🗺️ CLI Overview
```
📟 CLI
│
├── 🪐 Jupiter Exchange
│   ├── Swap
│   ├── Limit Order
│   │   ├── Open Limit Order
│   │   ├── Display Canceled Orders History
│   │   └── Display Filled Orders History
│   ├── DCA
│   │   ├── Open DCA Account
│   │   └── Manage DCA Accounts
│   ├── Token Sniper
│   │   ├── Add a token to snipe
│   │   ├── Watch token
│   │   └── Edit tokens
│   └── Change wallet
├── 💳 Manage Wallets
│   ├── Add wallet
│   ├── Edit wallet name
│   └── Delete wallet(s)
├── 🔧 CLI settings
│   ├── Solana RPC URL Endpoint
│   ├── Discord
│   └── Telegram
├── ❓ About
└── 🔚 Exit CLI
```

# 🤖 Sniper Bot
**In top of most of the Jupiter features that you can use, you are also able to snipe token.**<br>
❗**Please note that Sniper Bot is experimental and subject to change as there might be issues that I didn't see.**

### ⚙️ How it works
Every second, the bot will send a GET request to [Jupiter API Quote](https://quote-api.jup.ag/v6/quote).<br>
If there is a route available for this token, it will then execute it.<br>
Please note that only tokens with sufficient liquidity and on-chain metadata are listed in Jupiter API: min. 250$ liquidty and buy/sell price impact are below 30%.<br>
When these criteria are met, it will take a few minutes to automatically add the token.<br>

### 🆕 Add a token to snipe
- Token/Project name
- Token Address
- Amount ($) to buy
- Take Profit ($)
- Stop Loss ($)
- Slippage (%)

If token has a launch date:
- Month
- Day
- Hours
- Minutes

### 🔭 Watch token
You can watch your trading position by selecting the token.<br>
<img src="https://github.com/0xTan1319/jupiter-python-cli/blob/main/images/sniper_bot_watch.png?raw=true" width="50%" height="50%">

### ✍🏻 Edit tokens
You can modify token info as follow:
- Name
- Address
- Selected Wallet
- Buy Amount
- Take Profit
- Stop Loss
- Slippage
- Launch date
- Delete

# 🗨️ Q&A
### Where are my private keys?
*Your private keys are stored in `wallets.json`.*
### Is there any fees when swapping using CLI?
*There are no additional fees when performing swaps via the CLI; the costs should be the same as using the Jupiter UI.*
### Does sniper bot remains running if I close the CLI?
*If you close the CLI, the sniper bot will stop running.*
### Is it possible to swap any tokens?
*You can only swap tokens that are listed on Jupiter based on their criterias.*

# 📝 TO-DO
- [ ] Clean up code ⚡
- [ ] Add docstrings 📑
- [ ] Display tokens owned 🪙
- [ ] Favorite tokens displayed in first tokens for swap/limit orders/dca... ⭐
- [ ] Wallet Duplication detection
- [ ] Display message when swap failed (slippage error...)
- [ ] Disable swap / limits orders / etc, if not enough $SOL to cover the tx fees
- [ ] Give possibility to exit current choice (swap, limit order, dca, donation...) 🏃🚪
- [ ] Adjust Wallets ID when one is deleted
- [ ] Bridge 🌉
- [ ] Perpetual 💸

# 🤝 Contributions
If you are interesting in contributing, fork the repository and submit a pull request in order to merge your improvements into the main repository.<br>
Contact me for any inquiry, I will reach you as soon as possible.<br>
[![Telegram](https://img.shields.io/badge/Telegram-%231DA1F2.svg?logo=Twitter&logoColor=white)](https://t.me/shiny0103)

# 👑 Donations
This project doesn't include platform fees. If you find value in it and would like to support its development, your donations are greatly appreciated.<br>
You can donate through CLI in About menu.<br>

# ☎️ Connect
If you have question or any other problem, ask here [![Telegram: @shiny0103](https://img.shields.io/badge/Telegram-%231DA1F2.svg?logo=Twitter&logoColor=white)](https://t.me/shiny0103)

