# Solana Token Launchpad

## Overview
The **Solana Token Launchpad** is a web application that allows users to create and deploy SPL tokens on the Solana blockchain. It provides an intuitive interface for users to specify token parameters, including name, symbol, image URL, and initial supply. This project is built using **React** and integrates the **Solana web3.js** and **@solana/spl-token** libraries for blockchain interactions.

## Features
- Create SPL tokens on the Solana Devnet
- User-friendly interface for specifying token details
- Wallet connection using **Solana Wallet Adapter**
- Automated token minting and associated account creation

## Tech Stack
- **Frontend**: React, Vite
- **Blockchain**: Solana Web3.js, SPL Token Library
- **Wallet Integration**: Solana Wallet Adapter

## Installation
### Prerequisites
Ensure you have the following installed:
- Node.js (>= 16.x)
- npm or yarn


## Project Structure
```
solana-token-launchpad/
│── src/
│   ├── components/
│   │   ├── TokenLaunchpad.jsx  # Token creation logic
│   ├── App.jsx                 # Main app component
│   ├── main.jsx                # Entry point
│── public/
│── index.html                   # HTML template
│── package.json                  # Dependencies
│── vite.config.js                # Vite configuration
```

## Usage
1. Connect your Solana wallet using the **WalletMultiButton**.
2. Enter token details such as:
   - Name
   - Symbol
   - Image URL (optional)
   - Initial supply
3. Click **Create a Token** to deploy your SPL token.
4. The console will log the **mint address** and associated token account.


## Solana Integration Details
- Uses **Solana Web3.js** for blockchain transactions.
- Implements **@solana/spl-token** for token creation and minting.
- Connects to Solana **Devnet** (modifiable in `App.jsx`).
- Wallet interactions via **Solana Wallet Adapter**.

