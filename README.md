✨ Batch Sender
⚡ Next-Gen Multi-Asset Distribution Protocol on Base

Batch Sender is a high-performance, gas-optimized batch transfer dApp built for the Base Network.
It enables instant, atomic distribution of ETH and ERC20 tokens to hundreds of wallets in a single transaction — designed for 2026 standards, scalability, and security.

One transaction. Unlimited reach. Zero compromise.

🌐 Why Batch Sender?

Managing mass payouts shouldn’t be slow, expensive, or risky.
Batch Sender is engineered to power:

🚀 Airdrops & token launches

🏛 DAO payrolls & treasury payouts

🎁 Community rewards & incentives

🔁 Refunds & mass settlements

All with maximum efficiency and trustless execution.

💎 Feature Highlights
🪙 Multi-Asset Power

Batch send ETH and any ERC20 token

One interface, multiple assets

🎯 Precision Distribution

Unique amount per recipient

No fixed-value limitations

⚙️ Ultra Gas Efficient

Solidity ^0.8.20

calldata-optimized loops

Up to 40% gas savings vs traditional batch senders

🔐 Trustless & Atomic

All transfers succeed or everything reverts

No partial payouts, no broken states

🛡 Battle-Tested Security

OpenZeppelin contracts

ReentrancyGuard

Checks-Effects-Interactions pattern

Safe ERC20 handling

🧠 How It Works
Approve (ERC20 only)
        ↓
Upload Recipients + Amounts
        ↓
Execute One Atomic Transaction
        ↓
Instant Distribution + Auto ETH Refund


Excess ETH is automatically refunded

Funds never leave user custody prematurely

🧬 2026-Ready Tech Stack
🔗 Blockchain

Base (Ethereum L2)

🧱 Smart Contracts

Solidity 0.8.20+

OpenZeppelin

Gas-optimized batch logic

🎨 Frontend

React 19

TypeScript

Vite

🔐 Wallet & Web3

Wagmi + Viem

RainbowKit

WalletConnect (Reown)

🚀 Deployment

Vercel (Frontend)

BaseScan (Verified Contracts)

🗂 Project Architecture
├── contracts/              # Audited Solidity Contracts
├── src/
│   ├── wagmi.ts            # Web3 & Chain Configuration
│   ├── App.tsx             # Batch Logic & UI
│   └── index.css           # Custom Styling
├── package.json            # Dependency Graph
├── tsconfig.json           # Strict TypeScript Rules
└── README.md

⚙️ Quick Start
1️⃣ Clone
git clone https://github.com/your-username/batch-sender
cd batch-sender

2️⃣ Install
npm install

3️⃣ Configure Environment
VITE_WALLETCONNECT_ID=your_project_id_here

4️⃣ Run Locally
npm run dev

🔒 Security Philosophy

🔁 Atomic Execution – No partial transfers

💸 Auto Refunds – Excess ETH returned instantly

🧾 Approval-Based ERC20 Flow

🔐 Reentrancy Protection

📏 Strict Input Validation

🎯 Ideal For

Token Airdrops

DAO Treasury Operations

Payroll & Grants

Launch Campaigns

Community Incentives

📜 License

MIT License — Open, permissionless, and developer-friendly.

🚀 Batch Sender

Ship faster. Pay smarter. Scale trustlessly.
