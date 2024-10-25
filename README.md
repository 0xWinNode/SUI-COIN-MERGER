# SUI COIN MERGER
The Sui Coin Merger is a powerful tool designed for interacting with SUI networks. This bot automates merging processes of all coin making it an ideal solution for you to merge all coin assets.

## Table Of Contents
- [SUI COIN MERGER](#sui-coin-merger)
  - [Table Of Contents](#table-of-contents)
  - [Prerequisite](#prerequisite)
  - [Join My Telegram Channel](#join-my-telegram-channel)
  - [BOT FEATURE](#bot-feature)
  - [Setup \& Configure BOT](#setup--configure-bot)
    - [Linux](#linux)
    - [Windows](#windows)
  - [Update Bot](#update-bot)
  - [CONTRIBUTE](#contribute)
  - [SUPPORT](#support)

## Prerequisite
- Git
- Node JS (v22)


## BOT FEATURE
- Multi Account 
- Use PK
- Auto Merge ALl Your COIN


## Setup & Configure BOT

### Linux
1. Clone project repo
   ```
   git clone https://github.com/0xWinNode/SUI-COIN-MERGER.git && cd SUI-COIN-MERGER
   ```
2. Run
   ```
   npm install
   ```
3. Run
   ```
   cp -r accounts/accounts_tmp.js accounts/accounts.js
   ```
4. Configure your accounts
   ```
   nano accounts/accounts.js
   ```
5. Configure the bot config
    ```
   nano config/config.js
    ```
6. To run Auto TX
   ```
   npm run start
   ```
   
### Windows
1. Open your `Command Prompt` or `Power Shell`.
2. Clone project repo
   ```
   git clone https://github.com/0xWinNode/SUI-COIN-MERGER.git
   ```
   and cd to project dir
   ```
   cd SUI-COIN-MERGER
   ```
3. Run 
   ```
   npm install
   ```
5. Navigate to `sui-coin-merger` directory. 
6. Navigate to `accounts` folder and rename `accounts_tmp.js` to `accounts.js`.
7. Now open `acccounts.js` and setup your accounts. 
8. Now Back to `sui-coin-merger` directory and Navigate to `config` and adjust the `config.js` as needed.
9.  Back to `sui-coin-merger` directory.
10. To start the app open your `Command Prompt` or `Power Shell`
11. To run auto Tx Bot
    ```
    npm run start
    ```

## Update Bot

To update bot follow this step :
1. run
   ```
   git pull
   ```
   or
   ```
   git pull --rebase
   ```
   if error run
   ```
   git stash && git pull
   ```
2. run
   ```
   npm update
   ```
2. start the bot


## CONTRIBUTE

Feel free to fork and contribute adding more feature thanks.
