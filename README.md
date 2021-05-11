
#CryptoKitties

This is an IDE setup to run a local version of CryptoKitties using the original smart contract deployed at https://etherscan.io/address/0x06012c8cf97bead5deae237070f9587f8e7a266d#code

## Setup
 
###Dependencies

Install Node.js

Install Truffle using `npm install truffle`

Install Ganache https://github.com/trufflesuite/ganache

###IDE

Install IDEA https://www.jetbrains.com/de-de/idea/

Install plugin IntelliJ-Solidity

Open project folder

###Run

Start Ganache with Quickstart option

Move with terminal into the project folder

Run `truffle compile` to compile the solidity contracts into Ethereum Virtual Machine (EVM) code

Run `truffle migrate` to migrate compiled smart contracts using `/migrations` to Ganache RPC Server