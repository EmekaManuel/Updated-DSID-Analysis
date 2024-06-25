# Solana ID On-Chain Scoring Module

## Introduction

This module analyzes the on-chain footprint of Solana wallet accounts to derive a credibility score.

## Demo

![Project Screenshot](./public/project-demo.png)

## Setup

1. Clone the repository.
2. Install dependencies: `npm install`
3. Add your wallet address in `index.ts`.
4. Run the project: `npm start`

## Usage

The module calculates the score based on transaction history, token balances, smart contract interactions, and staking activities.

## API Endpoints

- `getTransactionHistory(publicKey: PublicKey)`
- `getTokenBalances(publicKey: PublicKey)`
- `getAccountInfo(publicKey: PublicKey)`
