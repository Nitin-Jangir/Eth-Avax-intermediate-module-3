# ERC-20 Token Smart Contract

This is a basic ERC-20 token smart contract written in Solidity. The contract allows users to create and manage a custom token on the Ethereum blockchain. The token follows the ERC-20 standard, which is widely used for fungible tokens.

## Table of Contents

- [Getting Started](#getting-started)
- [Token Details](#token-details)
- [Token Functions](#token-functions)
- [Deployment and Interactions](#deployment-and-interactions)
- [License](#license)

## Getting Started

To get started with the ERC-20 token smart contract, you can follow these steps:

1. Install a Solidity compiler such as `solc` or use an online Solidity IDE like Remix.

2. Copy the entire contents of the `MyUniqueToken.sol` file into your Solidity compiler or Remix.

3. Compile the contract to check for any errors or warnings.

4. Deploy the contract to an Ethereum network of your choice (mainnet or testnet).

## Token Details

The ERC-20 token has the following details:

- **Name**: MyUniqueToken
- **Symbol**: MUT
- **Decimals**: 18
- **Total Supply**: 1,000,000 tokens (1000000 * 10^18 with 18 decimals)

## Token Functions

The ERC-20 token smart contract provides the following functions:

### 1. `mint(address _to, uint256 _amount)`

This function allows the contract owner to mint new tokens and assign them to a specified address. Only the contract owner can call this function.

### 2. `burn(uint256 _amount)`

This function allows any token holder to burn (destroy) their own tokens. The tokens are removed from circulation, and the total supply decreases accordingly.

### 3. `transfer(address _to, uint256 _amount)`

This function allows users to transfer tokens to another address. The caller must have a sufficient balance to perform the transfer.

## Deployment and Interactions

To deploy and interact with the ERC-20 token smart contract, you can follow these steps:

1. Deploy the contract to an Ethereum network using your preferred deployment tool (e.g., Remix, HardHat, Truffle).

2. After deployment, you will receive the contract address. This address represents your token contract on the blockchain.

3. You can interact with the contract using the provided functions. For example:
   - Call the `mint` function to create and assign new tokens to a specified address.
   - Call the `burn` function to burn a certain amount of your own tokens.
   - Call the `transfer` function to send tokens to another address.

4. Make sure you have sufficient gas and appropriate permissions (e.g., contract ownership) to execute certain functions.

## License

This ERC-20 token smart contract is open-source and licensed under the MIT License. You can freely use, modify, and distribute it as per the terms of the MIT License.

