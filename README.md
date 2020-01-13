# theblockchainbook

## DISCLAIMER: CONCEPTUAL PHASE

The following document outlines the structure of theblockchainbook. This is no means a guide on how the final product will turn out. This project is still a Proof Of Concept so many details will change in the upcoming months.

---

## Timeline

1. Week 01 - [6/1/2020 - 12/1/2020]
   - Project Inception
   - Structure for blocks and transactions
   - Genesis Block
   - Chain
   - Book: Blocks
2. Week 02 - [13-1/2020 - 20/1/2020]
   - Key-Value DB

## eBook format

Asciidoc

1. [Comparison Article](https://asciidoctor.org/docs/asciidoc-vs-markdown/)
2. [Cheatsheat](https://asciidoctor.org/docs/asciidoc-syntax-quick-reference/)

---

## Helpers

> The helper repository will maintain all helper functions used during the life of this repository. It will maintain packages that can be used at multiple instances to allow for greater modularity. For instance, the caching mechanism will lie in this repository to ensure that the readers are not bombarded with the implementation details.

Repository: [Helpers](https://github.com/theblockchainbook/helpers)

Functionality in the helper repository

1. Caching

---

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

## Lesson 5: Advanced Concepts: Transaction Clauses and Delegator Signing

1. Clauses
2. Delegator Signing

## Lesson 6: Advanced Concepts: Cache and Raw Blocks

1. Cache
2. Raw Blocks

## Lesson 7: Advanced Concepts: Genesis Contracts

1. Contracts
   - Executor
   - Energy
   - Authority
   - Extension
   - Params
   - Prototype

## Lesson 8: Advanced Concepts: Networks

1. Networks
   - Testnet
   - Mainnet
   - Devnet

## Lesson 9: Advanced Concetps: Key-Value DB integration

1. Why?
2. Potential KV's
   - LevelDB
   - BadgerDB
3. The KV interface
