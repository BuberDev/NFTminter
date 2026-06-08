# NFT Minter Smart Contract

A Solidity ERC721 NFT minter built with OpenZeppelin contracts.

This project demonstrates how to create a basic NFT smart contract with minting functionality and token URI storage.

## Why this project matters

NFT minting is one of the most common practical use cases in Web3 development. This project shows the ability to work with ERC721 standards, OpenZeppelin contracts, token metadata, and Solidity inheritance.

## Tech Stack

* Solidity `^0.8.4`
* OpenZeppelin Contracts
* ERC721
* ERC721Enumerable
* ERC721URIStorage
* SafeMath

## Smart Contract Overview

The main contract is `Minter.sol`.

It extends:

* `ERC721`
* `ERC721Enumerable`
* `ERC721URIStorage`

The contract defines an NFT collection named:

```solidity
BuberMinter
```

with the symbol:

```solidity
BM
```

## Features

* ERC721 NFT contract
* NFT minting function
* Token URI storage
* OpenZeppelin-based inheritance
* Enumerable NFT support
* Metadata URI assignment
* Minting to `msg.sender`

## Minting flow

The `mint` function:

1. Gets the current total supply.
2. Uses the total supply as the next token index.
3. Mints a new NFT to `msg.sender`.
4. Assigns a metadata URI to the minted NFT.

## Key Solidity concepts demonstrated

* ERC721 standard
* OpenZeppelin contract inheritance
* NFT minting
* Token URI metadata
* Function overriding
* Multiple inheritance handling
* Smart contract constructor

## Example use cases

* NFT collection minting
* Digital collectibles
* Tokenized certificates
* Web3 identity badges
* Metadata-based NFT assets

## Relevance to Blockchain Developer roles

This project is relevant to roles requiring:

* Solidity
* ERC721 / NFT development
* OpenZeppelin usage
* Smart contract inheritance
* Token metadata handling
* EVM-based asset creation

## Author

Dawid Bubernak / BuberDev
