# 🏛️ VoxDAO — On-Chain Governance Protocol

> Give your community a voice — onchain.
> Create DAOs, vote on proposals, manage 
> treasury. All transparent. All on Base.

![Base](https://img.shields.io/badge/Built%20on-Base-0052FF?style=for-the-badge)
![Solidity](https://img.shields.io/badge/Solidity-0.8.20-363636?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)

---

## 🎯 Problem It Solves

Communities have no simple way to make
collective decisions onchain.

VoxDAO fixes this — create a DAO, add 
members, vote on proposals, and execute 
decisions fully onchain on Base.

No middleman. No off-chain voting.
Just pure onchain governance.

---

## ✨ Features

- 🏛️ **Create DAOs** — Name, description, quorum
- 👥 **Member System** — Roles + voting power
- 📋 **Proposals** — Submit governance proposals
- 🗳️ **Voting** — Yes / No / Abstain
- 💰 **Treasury** — Collective ETH management
- ⚡ **Execute** — Auto execute passed proposals
- 📡 **100% Onchain** — Permanent + transparent

---

## 📋 Contract Details

| Detail | Info |
|--------|------|
| **Network** | Base Mainnet |
| **Contract** | `0xff7677d8bb35c55da4d81831c84594f25656040c` |
| **Verified** | ✅ BaseScan |
| **Compiler** | Solidity 0.8.20 |
| **License** | MIT |

🔗 [View on BaseScan](https://basescan.org/address/0xff7677d8bb35c55da4d81831c84594f25656040c)

---

## 🛠️ Core Functions

```solidity
createDAO(name, desc, quorum, power)
joinDAO(daoId, power)
createProposal(daoId, title, desc, days)
vote(proposalId, choice)
execute(proposalId)
deposit(daoId)
spend(daoId, to, amount)
```

---

## 🗺️ Roadmap

- [x] Smart contract deployed on Base
- [x] Contract verified on BaseScan
- [ ] Frontend UI — in progress
- [ ] DAO directory
- [ ] Member management
- [ ] Voting interface

---

## 👨‍💻 Builder

Built by [@Huzaifa_0101](https://twitter.com/Huzaifa_0101)
Active on Base since Feb 2024 | 1900+ onchain transactions

---

## 📄 License

MIT License — free to use and build upon.
