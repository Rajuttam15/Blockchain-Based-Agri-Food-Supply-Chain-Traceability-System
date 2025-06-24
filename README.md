
# Authenticity in Food Supply Chain Using Blockchain

![Solidity](https://img.shields.io/badge/Solidity-000000?style=for-the-badge&logo=solidity&logoColor=white)
![Ethereum](https://img.shields.io/badge/Ethereum-white?style=for-the-badge&logo=ethereum&logoColor=blue)
![Javascript](https://img.shields.io/badge/Javascript-ffff00?&style=for-the-badge&logo=react&logoColor=black) 
![React](https://img.shields.io/badge/React-0095D5?&style=for-the-badge&logo=react&logoColor=white)

---

## 🧾 Project Description

### 📌 Introduction
The food supply chain is a complex but necessary food production arrangement needed by the global community to maintain sustainability and food security. The supply chain has been extended geographically, involving many more stakeholders—making it longer and more complicated, and bringing new challenges:

- Lack of traceability and communication
- Rising supply chain costs
- Supply of fraudulent food products
- Failure in monitoring warehouses

### 🎯 Objectives
The project aims to design a **decentralized food supply chain** to trace products from end to end and provide a smart and reliable way of delivering product information to customers.

**Key Features:**
- Platform to trace food products worldwide
- Restrict duplicate and unauthentic products
- Ensure proper food distribution
- Reduce supply chain costs

---

## 🏗️ System Architecture

The application follows a **layered architecture**:

- **Application Layer**
- **Blockchain Layer**
- **Infrastructure Layer**

<p align="center">
  <img src="https://res.cloudinary.com/dstmsi8qv/image/upload/v1652867380/Supply%20Chain/Github%20Readme/layer_arch_s5avzr.png" width="500px"/>
</p>

---

## 🔍 Methodology

### 1. Traceability System
- Each product has a **unique serial code**.
- Every transaction is recorded on the **Ethereum blockchain** using a **smart contract**.
- Access Control allows only verified participants to interact.

### 2. Trading Mechanism
<p align="center">
  <img src="https://res.cloudinary.com/dstmsi8qv/image/upload/v1652867380/Supply%20Chain/Github%20Readme/trading_mechanism_icqvdz.png" width="500px"/>
</p>

- Goods delivery is tracked and verified.
- Consumers register, request products, and ownership is transferred on-chain.
- Ensures **no duplicate products** enter the market.

### 3. Reputation System
<p align="center">
  <img src="https://res.cloudinary.com/dstmsi8qv/image/upload/v1652867379/Supply%20Chain/Github%20Readme/reputation_system_wumzif.png" width="500px"/>
</p>

- Adds **trust and transparency**.
- Only real buyers can post immutable reviews.
- Prevents manipulation of ratings.

---

## 🧰 Development Setup

### ✅ Requirements
- [Node.js](https://nodejs.org/en) (≥ 10.16)
- [npm](https://www.npmjs.com/) (≥ 5.6)
- [Git](https://git-scm.com/)
- [Truffle](https://www.trufflesuite.com/truffle) `npm install -g truffle`
- [Metamask](https://metamask.io) browser extension
- [Ganache](https://trufflesuite.com/ganache/)

### 📥 Clone the Repository

```bash
git clone https://github.com/lakshya-20/supply-chain
cd supply-chain

### ⚙️ Smart Contract Setup

cd src/Smart-Contract
npm install -g truffle
truffle compile
truffle migrate --reset
truffle test

🌐 Client Setup
	1.	Create .env file:
    REACT_APP_NFT_STORAGE_APIKEY=<your-nft.storage-apikey>
  
  2.	Install Dependencies & Run:
    npm install
    npm start
