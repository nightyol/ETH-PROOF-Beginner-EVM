# ETH-PROOF-Beginner-EVM
## MetaCrafters Assignments
This repository contains my completed assignments for the MetaCrafters course. Each assignment is organized in its own folder, with the necessary code files and any additional resources.

## Table of Content
Assessment : - ETH PROOF - Beginner Level

## Getting Started
To get started with the assignments, follow these steps:

Clone this repository: git clone https://github.com/your-username/metacrafters-assignments.git.
Navigate to the specific assignment folder: cd assignmentX (replace X with the assignment number).
Read the assignment description and requirements in the README file within each assignment folder.
Complete the assignment by writing the necessary code and making any required changes.
Test your code and ensure it meets the assignment requirements.
Commit and push your changes to your GitHub repository.

# Test.sol
This Solidity contract implements the MyToken token contract. It is a simple ERC-20 compatible token contract that allows users to mint and burn tokens.

## Contract Details
SPDX License Identifier: MIT
Solidity Version: 0.8.18
Contract Variables
tokenName
Type: string
Description: Stores the name of the token.
tokenAbbrv
Type: string
Description: Stores the abbreviation of the token.
totalSupply
Type: uint
Description: Stores the total supply of the token.
## Contract Functions
mint(address account, uint value)
This function allows the contract owner to mint new tokens and assign them to a specified account.

Parameters:
account: The address of the account to which the tokens will be minted.
value: The amount of tokens to be minted.
burn(address account, uint value)
This function allows the contract owner to burn existing tokens from a specified account.

Parameters:
account: The address of the account from which the tokens will be burned.
value: The amount of tokens to be burned.

## Usage
Deploy the contract on the Ethereum network using Solidity compiler version 0.8.18 or compatible.
Call the mint function to create new tokens and assign them to specific accounts.
Call the burn function to destroy existing tokens from specific accounts.
## Author
tanay kumar rai
## License
This project is licensed under the MIT License. You are free to modify and distribute the code for personal and educational purposes.
