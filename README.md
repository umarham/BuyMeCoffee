# Basic Sample Hardhat Project

This project demonstrates a basic Hardhat use case. It comes with a sample contract, a test for that contract, a sample script that deploys that contract, and an example of a task implementation, which simply lists the available accounts.

Try running some of the following tasks:

```shell
npx hardhat accounts
npx hardhat compile
npx hardhat clean
npx hardhat test
npx hardhat node
node scripts/sample-script.js
npx hardhat help
```

BuyMeACoffee solidity contract
This repo contains a contract that implements tipping functionality.

Install dependencies with npm install.

Once you have a contract deployed to Goerli testnet, grab the contract address and update the contractAddress variable in scripts/withdraw.js, then: run 

npx hardhat run scripts/withdraw.js
will allow you to withdraw any tips stored on the contract.
