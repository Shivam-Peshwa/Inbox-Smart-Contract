# Inbox Smart Contract  
A simple Ethereum smart contract that allows users to store and update a message on the blockchain.


# 📜 Inbox Smart Contract

This repository contains smart contract projects from my Solidity course, including a simple contract called `Inbox.sol`. The contract is written in Solidity and deployed using Ethereum development tools.

---

## 🚀 Features
- Smart contract development using Solidity.
- Deployment to an Ethereum blockchain.
- Uses modern Ethereum development tools (Truffle, Hardhat, or Web3.js).
- Basic contract interaction through JavaScript.

---

## 🛠️ Installation & Setup

To get started, clone this repository and install the dependencies:

```sh
git clone https://github.com/Shivam-Peshwa/Inbox-Smart-Contract.git
cd Inbox-Smart-Contract
npm install

// SPDX-License-Identifier: MIT
pragma solidity ^0.8.0;

contract Inbox {
    string public message;

    constructor(string memory initialMessage) {
        message = initialMessage;
    }

    function setMessage(string memory newMessage) public {
        message = newMessage;
    }
}

node compile.js #Compiles the contract
node deploy.js #Deploys the contract

npm test #To run the test, ensure you have Mocha installed to run this


### 📌 Key Improvements:
- **Added Sections**: Features, Installation, Smart Contract Overview, Deployment, Testing, and Contributions.
- **Formatted Code Blocks**: Used syntax highlighting for Solidity and shell commands.
- **Professional Structure**: Makes it easier for others to understand and use your project.

