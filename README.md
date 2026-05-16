# SDD - Decentralized Lottery (Blockchain Lottery DApp)

## Overview

Decentralized Lottery is a blockchain-based application built on Ethereum smart contracts. The system manages a fully decentralized lottery mechanism where ticket purchases, reward distribution, and lottery state transitions are handled on-chain.

The core logic is implemented in a Solidity smart contract, ensuring transparency, immutability, and deterministic execution of lottery rules.

<p align="center"> <img src="https://github.com/error-504941/SDD/assets/126831986/0f1f141f-aa19-4a28-9f61-4ba29a65c889" width="350" title="lotteria"> </p>
---

## Key Features

- Smart contract–based lottery system deployed on Ethereum
- Owner-controlled lottery lifecycle (start/end configuration)
- Time-based lottery execution using blockchain timestamps
- Ticket-based probabilistic reward system
- Wallet-based authentication for participants
- User dashboard for ticket tracking and winnings

---

## Architecture

The system is composed of:

- Smart Contract Layer (Solidity): core lottery logic and state management
- Frontend Application (React 18): user interaction layer
- Blockchain Network (Ethereum via Ganache for local development)

---

## Lottery Logic

- The contract owner initializes lottery parameters (duration, ticket price)
- Users connect their wallet to participate
- Ticket purchases increase winning probability proportionally
- Lottery closes automatically based on timestamp constraints
- Winner selection and reward distribution are executed by the contract owner

---

## Tech Stack

- Solidity
- React 18
- Ethereum (Ganache for local testing)

---

## Installation & Run

### Prerequisites
- Ganache installed and running
- Node.js installed

### Client setup

```bash
npm install
npm start
```

---

## Notes

This project was developed for academic purposes to explore blockchain fundamentals, smart contract development, and decentralized application architecture.
