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

# Deployed contract
0xDfF42208b39AAaD1814aaE101884CfE7fF85ff10

# Eth scan
https://mumbai.polygonscan.com/address/0xDfF42208b39AAaD1814aaE101884CfE7fF85ff10

# Dev flow
npx hardhat compile
npx hardhat run scripts/deploy.js --network mumbai
npx hardhat verify --network mumbai 0xDfF42208b39AAaD1814aaE101884CfE7fF85ff10

#