#CryptoKitties

This is an IDE setup to run a local version of CryptoKitties using the original smart contract deployed at https://etherscan.io/address/0x06012c8cf97bead5deae237070f9587f8e7a266d#code

## Setup
 
###Dependencies:

Install Node.js

Install Truffle using `npm install truffle`

Install Ganache https://github.com/trufflesuite/ganache

###Run

Start Ganache with Quickstart option

Move into project folder

Run `truffle compile` to compile solidity into Ethereum Virtual Machine (EVM) code

Run `truffle migrate` to migrate compiled smart contracts using `/migrations` to Ganache RPC Server