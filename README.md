# Full-Stack Blockchain Voting System

A decentralized voting system built on blockchain technology, ensuring transparent, tamper-proof, and secure electoral processes. Built with Truffle, Ganache & MetaMask.

## Project Overview

This project implements a full-stack blockchain-based voting system that eliminates fraud and ensures vote integrity through cryptographic hashing and smart contract automation.

### YouTube Video : https://youtu.be/ohc-LvRjfVg?si=M9_jmqhMPRfmSpgL

## Features

- **Smart Contract Based Voting** — Solidity contracts manage candidate registration and vote casting
- **MetaMask Integration** — Secure wallet-based voter authentication
- **Ganache Local Blockchain** — Local Ethereum network for development and testing
- **Truffle Framework** — Smart contract compilation, migration, and testing
- **Tamper-Proof Records** — Every vote is immutably recorded on the blockchain

## Tech Stack

| Layer | Technology |
|-------|-----------|
| Blockchain | Ethereum (Ganache) |
| Smart Contracts | Solidity |
| Development Framework | Truffle |
| Wallet | MetaMask |
| Frontend | HTML/CSS/JS with Web3.js |

## Getting Started

### Prerequisites
- [Node.js](https://nodejs.org/)
- [Truffle](https://www.trufflesuite.com/docs/truffle/overview)
- [Ganache](https://www.trufflesuite.com/ganache)
- [MetaMask](https://metamask.io/)

### Installation

```bash
# Install dependencies
npm install

# Compile contracts
truffle compile

# Deploy to local blockchain
truffle migrate

# Run tests
truffle test
```

## Project Structure

```
├── contracts/         # Solidity smart contracts
├── migrations/        # Truffle migration scripts
├── test/              # Test files
├── src/               # Frontend application
└── truffle-config.js  # Truffle configuration
```

## How It Works

1. **Admin** deploys the smart contract and registers candidates
2. **Voters** connect their MetaMask wallet to the application
3. Each voter can cast **one vote** per election
4. Votes are recorded as transactions on the blockchain
5. Results are publicly verifiable and immutable

## Author

**Rajgopal Pandilwar**

### Credits


## License

This project is open-source. Feel free to use it for educational purposes.

---

### Need Help?

Feel free to open an issue or reach out for any questions about the project.
