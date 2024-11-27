# Telegram Mini App - Simple Game

This is a simple game application on Telegram, built with ReactJS. The game has mechanics similar to the "Dogs" game, where players can participate and connect their TON wallets to interact with the game. The app integrates multiple wallet options for users, such as Tonkeeper, MyTonWallet, Tonhub, and more.

**I would be delighted if you give this repo a star! 🌟**

## Table of Contents

- [Telegram Mini App - Simple Game](#telegram-mini-app---simple-game)
  - [Table of Contents](#table-of-contents)
  - [Introduction](#introduction)
  - [Installation 🛠️](#installation-️)
  - [Configuration 🌐](#configuration-)
  - [Important!](#important)
  - [Start 🌈](#start-)
  - [Features 🔥](#features-)
  - [Dependencies 🚩](#dependencies-)

## Introduction

This project is a simple mini-game designed for Telegram with gameplay similar to "Dogs." Players can connect their TON wallets to join the game and experience interactive features. The app supports popular wallet options and runs smoothly within the Telegram environment.

![Home](https://res.cloudinary.com/dk6y8q94b/image/upload/v1724310049/itllytgv1hoskcobllkx.png)

![Score](https://res.cloudinary.com/dk6y8q94b/image/upload/v1724310049/hqu7dbmj6yojuf5madlq.png)

## Installation 🛠️

1. Clone the repository:

   ```bash
   git clone https://github.com/Kidkender/mini-app-telegram
   ```

2. Navigate to the project directory:

   ```bash
   cd mini-app-tele
   ```

3. Install the necessary packages:

   ```bash
   yarn install
   ```

## Configuration 🌐

Before running the app, make sure to set up the required environment variables. You may need to create a .env file in the project root directory with the following keys:

> VITE_BACKEND_URL
> VITE_BOT_TOKEN
> VITE_REFERRAL_LINK

## Important!

Before running the front-end, please make sure to run the backend server first. You can find the repository backend server at [this link](https://github.com/Kidkender/tma-backend).

## Start 🌈

After successfully installing the packages, you can start the development server with:

```bash
yarn dev
```

## Features 🔥

- **Reward Tokens**: Players receive reward tokens based on the number of years they have participated in Telegram.
- **Ranking and Leaderboard**: A leaderboard system to track and display player rankings based on performance and achievements.
- **Invite Friends**: Players can invite friends to join the game and receive bonuses or rewards.
- **TON Wallet Integration**: Supports various wallets for easy connectivity:
  - Tonkeeper
  - MyTonWallet
  - Tonhub
  - OKX
  - And more...

## Dependencies 🚩

> Yarn
> Axios
> ReactJS
> Taildwindcss
