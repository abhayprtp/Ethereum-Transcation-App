

---

# Ethereum Transaction App using Hardhat

## Overview

This project is a decentralized application (dApp) built on Ethereum using Hardhat, a development environment that facilitates the deployment and testing of Ethereum smart contracts. The app allows users to interact with the Ethereum blockchain by sending transactions, estimating gas fees, and interacting with smart contracts.

## Features

- **Transaction Sending:** Users can send Ethereum transactions to specified addresses.
- **Gas Fee Estimation:** The app provides an estimate of gas fees before transactions are sent.
- **Contract Interactions:** Users can interact with deployed smart contracts, executing functions and retrieving data.

## Installation

1. Clone the repository:


2. Install dependencies:

   ```bash
   npm install
   ```

## Usage

1. **Compile Smart Contracts:**

   ```bash
   npx hardhat compile
   ```

2. **Deploy Contracts:**

   Before deploying contracts, start a local Ethereum network:

   ```bash
   npx hardhat node
   ```

   Deploy contracts to the local network:

   ```bash
   npx hardhat run scripts/deploy.js --network localhost
   ```

3. **Run the Application:**

   ```bash
   npm start
   ```

   Open your browser and navigate to `http://localhost:3000` to use the app.

## Contributing

Contributions are welcome! If you have suggestions, improvements, or encounter issues, please create an issue or submit a pull request.

## License

This project is licensed under the MIT License. See the LICENSE file for details.

---

**Owned by Abhay Singh**

---
