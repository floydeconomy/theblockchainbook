# theblockchainbook

## DISCLAIMER: CONCEPTUAL PHASE
The following document outlines the structure of theblockchainbook. This is no means a guide on how the final product will turn out.

## Timeline
1. Week 01 - [6/1/2020 - 12/1/2020]
  * Project Inception
  * Structure for blocks and transactions
  * Chain concepts


# Blockchain Programming

## Lesson 1: Project Information

What it will not do?

- Provide overview of complex blockchain architecture such as
  - Keyblocks/Microblocks
  - Deterministic Consensus Algorithms
    - Why? Because there isn't a reliable BFT Consensus

## Lesson 2: Blocks

1. Blocks
   - Architecture
     - Header
       - Address structure
       - Bytes32/Hash structure
     - Body
     - Builder
   - Block ID representation and calculation
     - Setting first 4 bytes as 0 for height
     - Public-Key Crypto Library
       - Types
         - Keccak256
         - Black2b
         - RCHash
   - Genesis Block
     - Builder
       - ChainConfig
       - BlockConfig
         - ExtraData
         - Timestamp

2) Testing
3) Cache (Ethereum vs Vechain)
   - ID

## Lesson 3: Chain

## Lesson 4: Transactions

1. Transactions
   - Architecture
     - Header
     - Body
   - Builder
   - Transaction ID representation and calculate
   - Clauses vs Traditional
2. Testing
3. Cache

## Lesson 5: Advanced Transaction Concepts

1. Clauses
2. Delegator Signing

## Lesson 6: Advanced Block Concepts

1. Cache
2. Raw Blocks

## Lesson 7: Advanced Genesis Block Concepts

1. Networks
   - Testnet
   - Mainnet
   - Devnet
2. Contracts
   - Executor
   - Energy
   - Authority
   - Extension
   - Params
   - Prototype
