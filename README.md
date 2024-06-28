Simple Token Contract

Overview

The Simple Token Contract is a basic ERC-20 token implementation on the Ethereum blockchain. It allows users to mint and burn tokens, and keeps track of the total supply and individual balances.

Description

This project provides a simple implementation of a token contract on the Ethereum blockchain. The contract allows users to mint new tokens and assign them to specific addresses, as well as burn tokens from existing balances. The contract keeps track of the total supply of tokens and individual balances for each address. This project is intended for educational purposes and serves as a starting point for building more complex token economies.

Getting Started

    Installing
To use the Simple Token Contract, you will need to have a Solidity compiler and an Ethereum development environment set up on your machine. You can download the contract code from this repository and compile it using the Solidity compiler.

    Executing Program
To deploy and interact with the contract, you will need to use a tool such as Truffle or Remix. Here are the step-by-step instructions to deploy and interact with the contract:

Compile the contract using the Solidity compiler: solcjs --bin --abi SimpleTokenContract.sol
Deploy the contract to the Ethereum network using Truffle: truffle deploy
Interact with the contract using Truffle: truffle console
Mint new tokens: SimpleTokenContract.mint(address, value)
Burn tokens: SimpleTokenContract.burn(address, value)

Help

If you encounter any issues while deploying or interacting with the contract, you can check the Truffle or Remix documentation for troubleshooting guides. Additionally, you can check the Solidity documentation for any syntax or compilation errors.

To view the contract's help information, you can use the following command: truffle console --help

