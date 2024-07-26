# Alpha Trade AI’s

## Overview

Alpha Trade AI transforms trading by making advanced tools accessible to all. Our mission is to empower traders of all levels, while our vision aims to democratize opportunities. We’re dedicated to enhancing lives and fostering future finance talent.

## Features

- **Real-time Data Updates**: Continuous market data updates using Socket.io.
- **User Authentication and Authorization**: Secure user login and management.
- **Market Analysis Tools**: Tools for analyzing market trends and making informed decisions.
- **Trade Execution and Management**: Execute and manage trades through the app.

## Technologies

- **Node.js**: Server-side runtime.
- **Express.js**: Web framework.
- **MongoDB**: Database.
- **Socket.io**: Real-time communication.
- **Nunjucks**: Templating engine.

## Setup

### 1. Clone the Repository
To get started, clone the repository to your local machine:

```console
$  git clone https://github.com/yourusername/trading-web-app.gits
```
### 2. Navigate to the Project Directory
Change into the project directory:

```console
cd trading-web-app
```

### 3. Install Dependencies

```console
npm install
```

### 4. Create a .env File
Create a .env file in the root directory of the project and add the following environment variables:
```console
PORT=1009
DB_URL="mongodb://alphatrade_ai:YVEzFDHz@172.31.1.241:27273/alphatrade_ai"
BASE_URL="https://alphatradeai.com/"
NUNJUCKS_WATCHER=true
COINBASE_KEY="afd871cc-60be-48dd-8205-3783ff38b5a5"
GPT_KEY="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"
WEBHOOK_SECRETE=whsec_485888f1b269add17ed256d1b03d5d5c260c40142ec80727bd0c0a8ca4f968b5
Binance_url="https://testnet.binancefuture.com/"
CoinBase_webhook_secrete="34124c63-da51-4eb9-8195-92b19c3662c4"
USE_TESTNET=true
STRIPE_PUBLISHABLE_KEY="pk_live_51NR0DCIS7JLvoYKmKYCsESDrpyx1RgkenVjEQSW6fEPRd3OT8MdM9Ex6fJAPyQgtogtUdC9ezioBLdVCvbgmXTYV005MrMmFWH"
STRIPE_SECRET_KEY=""
```
### 5. running the application locally
install the nodemon
```consolw
npm install -g nodemon
```
### 6. Access the App
``` console
http://localhost:3000
```
### 7. Using PM2
PM2 is a process manager for Node.js applications. It allows you to keep your app alive, reload it without downtime, and manage logs.
Install PM2 globally:
``` console
npm install -g pm2
```

for running the app using pm2
``` console
npm run start
```

## Usage

  * Register a new account or login to an existing account.
  * Navigate through the dashboard to view real-time market data and execute trades.
  * Use the market analysis tools to make informed trading decisions.
