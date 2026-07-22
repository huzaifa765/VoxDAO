# 🏛️ VoxDAO — On-Chain Governance Protocol

> Give your community a voice — onchain.
> Create DAOs, vote on proposals, manage treasury.
> All transparent. All permanent. All on Base.

![Base](https://img.shields.io/badge/Built%20on-Base-0052FF?style=for-the-badge)
![Solidity](https://img.shields.io/badge/Solidity-0.8.20-363636?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)

---

## 🎯 Problem It Solves

Communities have no simple way to make
collective decisions onchain.

VoxDAO fixes this — create a DAO, add members,
submit proposals, vote, and execute decisions
fully onchain on Base. No middleman.
No off-chain voting. Pure onchain governance.

---

## ✨ Features

- 🏛️ **Create DAOs** — Name, description, quorum rules
- 👥 **Member System** — Join DAOs, roles, voting power
- 📋 **Proposals** — Submit governance proposals
- 🗳️ **Voting** — Yes / No / Abstain with voting power
- 💰 **Treasury** — Deposit and spend ETH collectively
- ⚡ **Execute** — Auto execute passed proposals
- 🌙 **Dark / Light Mode** — User preference toggle
- 📡 **100% Onchain** — Everything permanent on Base

---

## 📋 Contract Details

| Detail | Info |
|--------|------|
| **Network** | Base Mainnet |
| **Contract** | `0xff7677d8bb35c55da4d81831c84594f25656040c` |
| **Verified** | ✅ BaseScan |
| **Compiler** | Solidity 0.8.20 |
| **License** | MIT |
| **Live App** | [vox-dao-protocol.netlify.app](https://vox-dao-protocol.netlify.app) |

🔗 [View on BaseScan](https://basescan.org/address/0xff7677d8bb35c55da4d81831c84594f25656040c)

---

## 🛠️ Core Functions

```solidity
createDAO(name, description, quorum, votingPower)
joinDAO(daoId, votingPower)
createProposal(daoId, title, description, days)
vote(proposalId, choice) // 1=Yes 2=No 3=Abstain
execute(proposalId)
deposit(daoId)
spend(daoId, to, amount)
```

---

## 🗺️ Roadmap

- [x] Smart contract deployed & verified on Base
- [x] Frontend UI with dark/light mode
- [x] DAO creation and management
- [x] Proposal voting system
- [x] Treasury management
- [ ] Token-based voting
- [ ] Multi-sig treasury
- [ ] DAO analytics dashboard

---

## 👨‍💻 Builder

Built by [@Huzaifa_0101](https://twitter.com/Huzaifa_0101)
Active on Base since Feb 2024 | 1900+ onchain transactions
## How to Use

1. Connect your wallet on Base Mainnet
2. Navigate to **Proposals** tab
3. Create a new proposal with title and description
4. Community members can vote Yes or No
5. Results are recorded permanently onchain

## Contract

| Contract | Address |
|----------|---------|
| VoxDAO | `0xff7677d8bb35c55da4d81831c84594f25656040c` |

🔗 [View on BaseScan](https://basescan.org/address/0xff7677d8bb35c55da4d81831c84594f25656040c)

## Governance Model

- One wallet one vote
- Proposals created onchain
- Voting period: open until closed
- Results permanent on Base
- ## Why VoxDAO

- Decentralized governance on Base
- No central authority
- Transparent voting history
- Community owned decisions
- ## Proposal Types

- Community decisions
- Protocol upgrades
- Treasury allocation
- Partnership approvals
- Any onchain governance matter
---

## 📄 License

MIT License — free to use and build upon.
