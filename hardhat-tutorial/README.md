# Sample Hardhat Project

This project demonstrates a basic Hardhat use case. It comes with a sample contract, a test for that contract, and a script that deploys that contract.

Try running some of the following tasks:

```shell
npx hardhat help
npx hardhat test
REPORT_GAS=true npx hardhat test
npx hardhat node
npx hardhat run scripts/deploy.js
```

Steps: 

1. Create dApp directory
2. cd /dApp-dir, create hardhat app directory
3. run npm init --yes
4. run npm install --save-dev hardhat
5. Initialize hardhat project with npx hardhat
6. Write your contract in the contract/ directory
7. Update the hardhat deploy script 
8. touch .env file and add Metamask Account's PRIVATE_KEY env var and QUICKNODE_HTTP_URL (eg. Quicknode's Ethereum Goerli Nentwork endpoint)
9. Update hardhat config
10. Compile: run npx hardhat compile
11. Deploy: npx hardhat run scripts/deploy.js --network goerli
