<div align="center">
  <h1>🪙 Wav5Coin Token Application</h1>
  <p><b>Internet Computer (ICP) Blockchain paina Motoko canisters upayoginchi build chesina Decentralized Cryptocurrency & Token Management System.</b></p>
  
  <p>
    <img src="https://img.shields.io/badge/Web3-ICP-F15A24?style=for-the-badge&logo=internetcomputer&logoColor=white" alt="ICP">
    <img src="https://img.shields.io/badge/Motoko-Smart_Contracts-29B6F6?style=for-the-badge" alt="Motoko">
    <img src="https://img.shields.io/badge/React-Frontend-61DAFB?style=for-the-badge&logo=react&logoColor=white" alt="React">
    <img src="https://img.shields.io/badge/License-MIT-green?style=for-the-badge" alt="License">
  </p>
</div>

---

## 🚀 Overview
**Wav5Coin** is a decentralized cryptocurrency project built on the **Internet Computer Protocol (ICP)**. It uses custom Motoko backend canisters to manage token balances, payouts, and transfers, paired with a React frontend web interface.

---

## ✨ Key Features

* **🪙 Token Management:** Decentralized ledger implementation for tracking balances, names, and user accounts.
* **⚡ Canister Architecture:** High-performance backend canisters deployed on the Internet Computer network.
* **🧪 CLI & Terminal Testing:** Built-in support for DFX canister calls to test payouts, balances, and ledger states directly.

---

## 🛠️ Tech Stack

* **Blockchain / Backend:** Internet Computer Protocol (ICP), Motoko
* **Frontend:** React.js, JavaScript, HTML5, CSS3
* **Tools:** DFX CLI, Node.js, Git

---

## ⚙️ Quick Start & Local Deployment

To run and test the project locally using DFX:

```bash
# Navigate to project directory
cd wav5coin

# Clean any old replica data
rm -rf .dfx

# Start local replica in background
dfx start --clean --background

# Wait for initialization
sleep 10

# Deploy canisters
dfx deploy

# Create environment configuration
node setup-env.js

# Start frontend application
npm start
