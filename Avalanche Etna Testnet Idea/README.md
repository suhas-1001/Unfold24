# Etna Testnet Projects

Welcome to the **Etna Testnet Projects Repository**! This repository contains a suite of blockchain projects designed to align with the Etna Testnet Ideas from the Avalanche9000 upgrade. Each project demonstrates specific functionalities within the Avalanche ecosystem, focusing on interchain messaging, token bridging, and contract creation.

## Table of Contents
- [Overview](#overview)
- [Project List](#project-list)
- [Prerequisites](#prerequisites)
- [Setup and Deployment](#setup-and-deployment)
- [Project Details](#project-details)
  - [0. Send and Receive](#0-send-and-receive)
  - [1. Send Roundtrip](#1-send-roundtrip)
  - [2a. Invoking Functions](#2a-invoking-functions)
  - [2b. Invoking Functions](#2b-invoking-functions)
  - [3. Registry](#3-registry)
  - [4. Creating Contracts](#4-creating-contracts)
  - [5. Native-to-ERC20 Token Bridge](#5-native-to-erc20-token-bridge)
  - [6. ERC20-to-Native Token Bridge](#6-erc20-to-native-token-bridge)
  - [7. Native-to-Native Token Bridge](#7-native-to-native-token-bridge)
  - [8. ERC20-to-ERC20 Token Bridge](#8-erc20-to-erc20-token-bridge)
- [Technologies Used](#technologies-used)
- [Contributing](#contributing)
- [License](#license)

---

## Overview

This repository is a collection of projects that leverage the features of the Avalanche9000 upgrade, specifically the Etna Testnet. These projects showcase:
- Interchain messaging for seamless communication across different blockchains.
- Token bridges for interoperability between native and ERC20 tokens.
- Smart contract creation and function invocation.

---

## Project List

1. **0-send-receive** - Basic send and receive functionality across chains.
2. **1-send-roundtrip** - Demonstrates a roundtrip token transaction.
3. **2a-invoking-functions** - Function invocation on one chain.
4. **2b-invoking-functions** - Cross-chain function invocation.
5. **3-registry** - A registry contract for managing metadata or assets.
6. **4-creating-contracts** - On-chain creation of smart contracts.
7. **5-native-to-erc20-token-bridge** - Bridging native tokens to ERC20 tokens.
8. **6-erc20-to-native-bridge** - Bridging ERC20 tokens to native tokens.
9. **7-native-to-native-token-bridge** - Bridging between native tokens across chains.
10. **8-erc20-to-erc20-token-bridge** - Bridging ERC20 tokens across chains.

---

## Prerequisites

To run these projects, you will need:
- [Node.js](https://nodejs.org/) (v16 or higher)
- [npm](https://www.npmjs.com/) or [yarn](https://yarnpkg.com/)
- [Hardhat](https://hardhat.org/)
- Avalanche Fuji Testnet account and credentials

---

## Setup and Deployment

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/etna-testnet-projects.git
   cd etna-testnet-projects
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Set up environment variables:
   Create a `.env` file and add the following:
   ```env
   PRIVATE_KEY=<your-private-key>
   AVALANCHE_RPC_URL=<fuji-testnet-url>
   ```

4. Deploy the contracts:
   ```bash
   npx hardhat run scripts/deploy.js --network fuji
   ```

---

## Project Details

### 0. Send and Receive
**Description:** Demonstrates basic token sending and receiving across chains.
- Utilizes interchain messaging for communication.
- Ideal for understanding the basics of cross-chain communication.

### 1. Send Roundtrip
**Description:** Shows a complete roundtrip transaction of tokens.
- Tokens are sent from Chain A to Chain B and back to Chain A.
- Highlights the reliability of interchain messaging.

### 2a. Invoking Functions
**Description:** Demonstrates function invocation on a single chain.
- Calls a smart contract function on the same chain.

### 2b. Invoking Functions
**Description:** Demonstrates cross-chain function invocation.
- Shows advanced use of interchain messaging for executing remote contract calls.

### 3. Registry
**Description:** Implements a registry smart contract.
- Manages metadata or assets with cross-chain compatibility.

### 4. Creating Contracts
**Description:** Enables on-chain creation of smart contracts.
- Demonstrates dynamic contract deployment.

### 5. Native-to-ERC20 Token Bridge
**Description:** Bridges native tokens to ERC20 tokens.
- Facilitates interoperability between native and ERC20 token standards.

### 6. ERC20-to-Native Token Bridge
**Description:** Bridges ERC20 tokens to native tokens.
- Highlights reverse bridging functionality.

### 7. Native-to-Native Token Bridge
**Description:** Bridges native tokens across chains.
- Simplifies token movement in a multi-chain ecosystem.

### 8. ERC20-to-ERC20 Token Bridge
**Description:** Bridges ERC20 tokens across chains.
- Supports ERC20 token interoperability in a seamless manner.

---

## Technologies Used
- **Blockchain:** Avalanche Fuji Testnet
- **Development Framework:** Hardhat
- **Languages:** Solidity, JavaScript
- **Tools:** Avalanche DevNet Resources, Interchain Messaging



