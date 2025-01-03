# Supply Chain Application

This project is a decentralized supply chain application built on Ethereum blockchain. It uses smart contracts to simulate the supply chain processes and provides a user interface to interact with the system.

## Features

- Decentralized supply chain management
- Smart contract integration with Ethereum
- MetaMask wallet connection
- Ganache for local blockchain development
- Frontend developed using React.js

## Prerequisites

Before running this project, ensure you have the following installed:

- [Node.js](https://nodejs.org/)
- [Truffle](https://www.trufflesuite.com/)
- [Ganache](https://trufflesuite.com/ganache/)
- [MetaMask](https://metamask.io/) browser extension

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/Naieem-55/supply_chain.git
   cd supply_chain
   ```
2. Install dependencies for the smart contracts:

```
cd src/Smart-Contract
npm install
```

3. Install dependencies for the React application:

```
cd ../client
npm install
```


Compile the smart contracts:
```
cd src/Smart-Contract
truffle compile
```
Deploy the contracts to Ganache:
```
truffle migrate --reset --network development
```

License
This project is licensed under the MIT License.