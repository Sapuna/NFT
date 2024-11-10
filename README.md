# NFT Project

This project provides a basic ERC-721 (NFT) implementation with minting functionality, using Solidity smart contracts and the Truffle framework. It includes deployment, migration, and testing scripts to facilitate NFT creation and management on a blockchain network.

## Project Structure

- **contracts/**: Contains Solidity smart contracts for NFT creation and management.
  - `ERC721PresetMinterPauserAutoId.sol`: Provides a base ERC-721 token setup.
  - `NFT.sol`: Main contract for creating NFTs, handling token minting and management.
  - `Migrations.sol`: Used for handling contract migrations.

- **migrations/**: Scripts for deploying contracts to the blockchain.
  - `1_initial_migration.js`: Manages the initial migration.
  - `2_deploy_nft.js`: Handles the NFT contract deployment.

- **scripts/**: JavaScript files for interacting with deployed contracts.
  - `mint.js`: Mints new NFTs by interacting with the deployed NFT contract.

- **test/**: Tests for verifying contract functionality.
  - `NFT.js`: Contains unit tests for the NFT contract.

- **truffle-config.js**: Configuration file for setting up network connections and compiler options in the Truffle environment.

## Requirements

- **Node.js** and **npm**: Ensure Node.js and npm are installed on your system.
- **Truffle**: Install Truffle globally using `npm install -g truffle`.
- **Ganache**: For local testing, Ganache provides a personal Ethereum blockchain.

## Installation

1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd nft-project
