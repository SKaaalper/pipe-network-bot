# Pipe Network Guardian

Pipe Network | The decentralized CDN redefining data delivery 🌍 | Faster bandwidth, lower latency ⚡ | Built on @Solana.
Pipe Network is taking decentralized content delivery to the next level with a two-tier node system that ensures high performance and reliability. PoP Nodes and Guardian Nodes. 🖥️📊

## and what we running here is Guardian Nodes📊


![pipe-network](image-1.png)

## Guardian Nodes 🛡️

Sitting above the PoP nodes, Guardian Nodes act like watchdogs. They continuously monitor network health, gather telemetry data, and optimize routing to ensure users get the fastest and most reliable data paths.

## **Register here**: [https://pipecdn.app](https://pipecdn.app/signup?ref=YWxsaXphbW)

## How it Works 🔍

Guardian Nodes collect real-time metrics like latency, bandwidth, and uptime from PoP nodes.
With these insights, they can reroute traffic dynamically to avoid bottlenecks, improving overall network performance. 🚀

## OKE its enough for that intro , lets dive into the code. I will show you how to deploy a simple Guardian Node using CLI BETA VERSION

## Features

- **Register New Accounts**
- **Login To Existing Accounts**
- **Accounts Management**
- **Support Multi Accounts**
- **Support Proxy**

## Requirements

- **Node.js**: Ensure you have Node.js installed. Recommended version: 20+
- **Dependencies**: Install necessary dependencies with `npm install`.

## File Structure

- **account.json**
- **proxy.txt**
- **token.json**

## Free Proxy for 7 Days
- Go here [7Days proxy free trial](https://dashboard.proxyscrape.com/v2/services/premium/ip-authentication/d0a61512-5605-46df-8653-7e7a3d26c830)
- Create account
- Authenticate 1 IP you use for the Proxy
- For Cloud `curl http://ipinfo.io/` Copy and paste it into your machine
- For Windows `http://ipinfo.io/` Copy and paste it into your browser
- Copy your IP add then authenticate

## Setup

1. Clone this repository:
   ```bash
   git clone https://github.com/SKaaalper/pipe-network-bot.git && cd pipe-network-bot
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. `account.json` Save your account info like `email` and `password`
   ```
   nano account.json
   ```
Format:
   ```
   [
      {
         "email" : "test1@gmail.com",
         "password": "test1"
      },
      {
         "email" : "test2@gmail.com",
         "password": "test2"
      }
   ]
  ```
   
4. `token,json` it Save access token after you login
   ```
   nano token.json
   ```

5. `proxy.txt` to store proxy you want to use, each line for 1 proxy `http://username:pass@ip:port`
   ```
   nano proxy.txt
   ```
   
6. Run The Script: Make sure you already fill proxy in `proxy.txt` before start the bot
   ```bash
   npm run start
   ```
   
7. Follow the instructions in the terminal to complete the setup.
   - choose 1 to register new account.
   - you need login after you register accounts to get your access token.
   - choose 2 to login to account.
   - finally choose 3 to to run the bot.
     ![banner](image.png)
