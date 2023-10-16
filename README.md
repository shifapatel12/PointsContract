# PointsContract
# Points - ERC20 Token Smart Contract

Points is an Avalanche smart contract that implements the ERC20 token standard, allowing for the creation and management of a custom token named "Degen" (DGN). This token contract also includes additional functionality for minting, burning, and transferring tokens. Additionally, it utilizes the OpenZeppelin library for ERC20 token and Ownable functionality.

## Contract Details

- **Name**: Degen
- **Symbol**: DGN
- **Decimals**: 0

## Features

1. **Minting**: The contract owner can mint new tokens and distribute them to any address.
2. **Burning**: Users can burn their own tokens if they no longer wish to hold them.
3. **Transfer Tokens**: Users can transfer tokens to other addresses, provided they have a sufficient balance.
4. **Redeem Tokens**: Users can transfer tokens to the contract itself and set a flag in the contract, granting them a "power boost."

## Usage

You can deploy this contract on the Avalanche blockchain, and you can interact with it using various Ethereum wallet interfaces or through smart contract calls.

## Smart Contract Deployment

You can deploy this contract on the Avalanche network by compiling and deploying it through tools like Remix, Truffle, or Hardhat. Make sure to fund the contract with initial tokens for distribution.

## Prerequisites

- Solidity Compiler 0.8.9
- Truffle or Hardhat (for deployment and testing)

## Installation

1. Clone this repository to your local machine.
2. Install the required dependencies using npm or yarn.
