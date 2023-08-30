# fastCoin

## Description

fastCoin is a Solidity smart contract that defines a cryptocurrency.

The contract has the following public variables:

tokenName: A string variable that stores the name of the token, which is “fastCoin”.

tokenAbbrv: A string variable that stores the abbreviation of the token, which is “FC”.

totalSupply: An unsigned integer variable that stores the total number of tokens in circulation. The initial value of this variable is 0.

balances: A mapping variable that maps addresses to their respective token balances.

The contract also has two functions:

mint(uint amount, address receiver): This function takes two parameters: an unsigned integer amount and an address receiver.

The function increases the total supply by amount and increases the balance of the receiver address by that amount.

burn(uint amount, address user): This function takes two parameters: an unsigned integer amount and an address user.

The function deducts the value from the total supply and from the balance of the user. 

However, it has a conditional statement to ensure that the balance of “sender” is greater than or equal to the amount that is supposed to be burned.

## Getting Started

To get started with this project, you will need to have Solidity installed on your machine.

You can download it from here.

## Installing

To install this project, simply clone this repository using Git:

git clone https://github.com/your_username/fastCoin.git

## Executing

To execute this project, you will need to compile and deploy the smart contract.

You can do this using Remix IDE or Truffle Suite.

## Authors
This project was created by Agyeman.

License
This project is licensed under the MIT License
