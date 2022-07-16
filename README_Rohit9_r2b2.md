# Basic Sample Hardhat Project

This project demonstrates a basic Hardhat use case. It comes with a sample contract, a test for that contract, a sample script that deploys that contract, and an example of a task implementation, which simply lists the available accounts.

Try running some of the following tasks:


INSTALL:
1:npm install --save-dev hardhat
2:npx hardhat
3:npm install --save-dev @nomiclabs/hardhat-etherscan(for verify)


```shell
npx hardhat accounts
npx hardhat compile
npx hardhat clean
npx hardhat test
npx hardhat node
node scripts/sample-script.js
npx hardhat help
```
FOR DEPLOY:

npx hardhat run --network Bscmainnet scripts/deploy.js

FOR VERIFY_for example:
 npx hardhat verify \
--contract "contracts/.sol:" \
--network Bscmainnet 
  

 npx hardhat verify  --network Bscmainnet
  