⚡ Batch Sender 2026
High-Efficiency Multi-Asset Distribution Protocol on Base

Batch Sender is a professional-grade, high-concurrency dApp built for the Base network, enabling users to distribute ETH and ERC20 tokens to hundreds of recipients in a single atomic transaction.
Designed for maximum gas efficiency, security, and UX, it meets modern 2026 smart contract and frontend standards.

🚀 Core Features
🔹 Multi-Asset Transfers

Send native ETH or any ERC20 token

Unified interface for all batch operations

🔹 Dynamic Amount Allocation

Each recipient can receive a unique value

No need for multiple fixed-amount transactions

🔹 Optimized for Gas Efficiency

Solidity 0.8.20+

Uses calldata and loop optimizations

Saves up to 40% gas compared to naive batch transfers

🔹 Atomic Execution

All transfers succeed or entire transaction reverts

No partial payouts, no inconsistent state

🔹 Enterprise-Grade Security

OpenZeppelin libraries

ReentrancyGuard

Checks-Effects-Interactions pattern

Safe ERC20 transfer handling

🧠 How It Works

User selects ETH or ERC20

Provides recipient addresses and amounts

(ERC20 only) Approves the contract once

Executes one atomic batch transaction

Any excess ETH is automatically refunded

🛠 Tech Stack (2026 Ready)
Blockchain

Base (Layer 2 Ethereum)

Smart Contracts

Solidity ^0.8.20

OpenZeppelin Contracts

Gas-optimized batch logic

Frontend

React 19

TypeScript

Vite

Web3 & Wallets

Wagmi + Viem

RainbowKit

WalletConnect (Reown)

Deployment

Vercel – Frontend

BaseScan – Contract verification

📂 Project Structure
├── contracts/              # Audited Solidity Smart Contracts
├── src/
│   ├── wagmi.ts            # Web3 Provider & Chain Config
│   ├── App.tsx             # Batch Transfer Logic & UI
│   └── index.css           # Custom UI Styling
├── package.json            # Dependencies
├── tsconfig.json           # Strict TypeScript Config
└── README.md

⚙️ Installation & Setup
1️⃣ Clone the Repository
git clone https://github.com/mumair738/batchsender.git
cd batch-sender

2️⃣ Install Dependencies
npm install

3️⃣ Environment Configuration

Create a .env file and add your WalletConnect Project ID:

VITE_WALLETCONNECT_ID=your_project_id_here

4️⃣ Run Locally
npm run dev

🔐 Security & Design Principles

✅ Atomic Transactions – No partial execution

✅ Excess ETH Refund – Overpayment returned automatically

✅ Approval-Then-Send – Users retain full ERC20 custody

✅ Reentrancy Protection

✅ Strict Input Validation

🧪 Recommended Use Cases

Airdrops

Payroll distributions

DAO rewards

NFT mint refunds

Community incentives

Treasury payouts

📜 License

This project is licensed under the MIT License.
Feel free to fork, modify, and deploy responsibly.
