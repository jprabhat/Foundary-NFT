# NFT Project in Solidity

Welcome to the NFT Project! This repository contains the Solidity code for creating, deploying, and managing non-fungible tokens (NFTs) on the Ethereum blockchain. Built with security and efficiency in mind, this project leverages the ERC-721 standard to create unique digital assets that can be securely stored, traded, and managed on the blockchain.

## Key Features
- **ERC-721 Compliant**: Ensures compatibility with existing NFT marketplaces and wallets.
- **Metadata Management**: Configures token metadata to enhance user experience on platforms that support NFTs.
- **Gas Optimization**: Designed with gas efficiency in mind to reduce transaction costs.

## Project Structure
- **Contracts**: Contains the core Solidity files defining the NFT smart contracts.
- **Scripts**: Includes scripts for deploying and interacting with the contracts.
- **Tests**: Comprehensive test suite to ensure contract functionality and security.

## Getting Started

### Prerequisites
- **Solidity**: Recommended version (e.g., 0.8.x)


### Installation
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/yourusername/Foundary-NFT.git
   cd Foundary-NFT

Foundry consists of:

-   **Forge**: Ethereum testing framework (like Truffle, Hardhat and DappTools).
-   **Cast**: Swiss army knife for interacting with EVM smart contracts, sending transactions and getting chain data.
-   **Anvil**: Local Ethereum node, akin to Ganache, Hardhat Network.
-   **Chisel**: Fast, utilitarian, and verbose solidity REPL.

## Documentation

https://book.getfoundry.sh/

## Usage

### Build

```shell
$ forge build
```

### Test

```shell
$ forge test
```

### Format

```shell
$ forge fmt
```

### Gas Snapshots

```shell
$ forge snapshot
```

### Anvil

```shell
$ anvil
```

### Deploy

```shell
$ forge script script/Counter.s.sol:CounterScript --rpc-url <your_rpc_url> --private-key <your_private_key>
```

### Cast

```shell
$ cast <subcommand>
```

### Help

```shell
$ forge --help
$ anvil --help
$ cast --help
```
