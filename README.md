# MyATM

This is the Assessment for Module 2 of the ETH+AVAX Proof of learn. This explores the workings of the solidity contracts inside a local blockchain.

## Description

This project makes use of Solidity and Javascript to learn about the workings of the smart contracts. The contracts folder contains the smart contracts, and the pages folder contains index.js file which handles the background script code for the web page hosted locally. The scripts folder contains deploy.js to compile and deploy smart contracts.

## Getting Started

### Before Cloning

Ensure that you have npm installed.

### After Cloning

1. Inside the project directory, in the terminal type: npm i
2. Open two additional terminals in your VS code
3. In the second terminal type: npx hardhat node
4. In the third terminal, type: npx hardhat run --network localhost scripts/deploy.js
5. Back in the first terminal, type npm run dev to launch the front-end.

After this, the project will be running on your localhost. 
Typically at http://localhost:3000/

## Authors

Aditya
