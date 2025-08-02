# Decentralized Voting System

A secure, transparent, and decentralized voting platform built using **Solidity**, **Hardhat**, **TailwindCSS**, **TypeScript**, and **Firebase**.

##  Features
-  Voter registration and authentication
-  Transparent vote casting and tallying using Ethereum blockchain
-  Secure smart contract (written in Solidity)
-  Responsive frontend built with Vite + TailwindCSS
-  Firebase hosting for deployment
## Project Structure

```bash
Voting-2-main/
│
├── contracts/                 # Solidity smart contract + Hardhat config
│   ├── VotingContract.sol
│   ├── hardhat.config.js
│   └── .env.example
│
├── index.html                 # Frontend entry point
├── package.json               # Project dependencies
├── tailwind.config.ts         # TailwindCSS config
├── tsconfig.json              # TypeScript config
├── firebase.json              # Firebase hosting config
└── vite.config.ts             # Vite bundler config
