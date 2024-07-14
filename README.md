# NFT Mint, Vault & Swaps


## Introduction
This is an anchor program to mint NFT collections, Locking them in vault and enabling swaps using with $SOL.

## Core Features
- Mint a collection of NFTs using Anchor.

- Develop a vault system to lock NFTs, where rental fees are returned to the protocol.

- Ensure image storage and retrieval are functional and metadata is appropriately assigned.

- Create a swap program using Native Rust or Anchor that allows users to exchange $SOL for NFTs.


# Getting Started
## Prerequisites
Install Anchor

Use version 0.30.0 for compatibility with the program

```
avm install 0.30.0 && avm use 0.30.0
```

## Running the Tests
Execute the tests to see the program in action:

```
anchor build
anchor test
```
