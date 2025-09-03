# SEC & ICO Smart Contracts

This repository contains the smart contracts for **SEC Token** and its **ICO Contract**.  
The goal of this project is to implement a custom ERC20 token with transaction tax features and manage its Initial Coin Offering (ICO) on an Ethereum/EVM-compatible blockchain.

## 📂 Project Structure



├── SEC.sol # Custom ERC20 Token (SEC)
├── ICO.sol # ICO Management Contract
└── ... # Additional helpers and libraries



## ⚙️ Features

### SEC Token
- ERC20 standard (manual implementation)  
- Liquidity management (manual & automatic)  
- LP tokens sent to `owner()`  
- limit for minting tokens

### ICO Contract
- ICO purchase management  
- Per-transaction purchase limit  
- Buy fee applied  
- Direct integration with SEC token  

## 🚀 Getting Started

1. Clone the repository:
```bash
git clone https://github.com/your-username/sec-ico-contracts.git
cd sec-ico-contracts


📖 Requirements
Node.js v18+
Hardhat
MetaMask or any wallet to interact with contracts on test networks
📌 Roadmap
 Deployment scripts for test networks
 Frontend integration for ICO purchase
 Extended test coverage