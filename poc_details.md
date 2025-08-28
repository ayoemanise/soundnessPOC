# PoC Details – CrossChain ID Verifier

## Overview
This Proof of Concept demonstrates the foundation of the CrossChain ID Verifier project. It shows how a user identity can be registered and verified on the SL chain, with a simple frontend interface.

## Components
1. **Smart Contract**
   - SL Identity Contract deployed on testnet
   - Functions: registerIdentity, verifyIdentity

2. **Frontend**
   - Basic React + TypeScript interface
   - Allows user to connect wallet and register identity

3. **Backend (Optional)**
   - Node.js server for GraphQL queries
   - Simple integration to fetch registered identities

## Achievements
- ✅ Identity contract deployed on SL testnet
- ✅ Wallet connection + registration flow in frontend
- ❌ Cross-chain verification (to be completed in MVP stage)

## Repository
- GitHub: https://github.com/ayoemanise/crosschain-id-verifier-poc

## How to Test
1. Clone the repo
2. Install dependencies (`npm install`)
3. Run frontend (`npm run dev`)
4. Connect wallet to SL testnet
5. Register an identity
