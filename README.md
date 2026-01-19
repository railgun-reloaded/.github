# RAILGUN RELOADED Developer Guide

[![DEV SUPPORT](https://img.shields.io/badge/DEV_SUPPORT-BE0)](https://discord.gg/railgun)

> At RAILGUN, we're building the future of **private DeFi** — and that future can't exist without the vision and contributions of **our developer community**. 🔒
>
> **Jump in!** 👉 Check out the options above or dive into one of the core RAILGUN repositories to start making an impact today 🚀

---

### 📝 Docs

| Website                                           | Description                     |
| ------------------------------------------------- | ------------------------------- |
| [docs.railgun.org](https://docs.railgun.org/wiki) | RAILGUN Developer Documentation |

---

### 🔄 Data Sync

| Name            | Description                            | Repo                                                                   | Latest Release                                                                                     |
| --------------- | -------------------------------------- | ---------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------- |
| Subsquid Client | Subsquid-based data synchronization    | [subsquid-client](https://github.com/railgun-reloaded/subsquid-client) | ![Latest Release](https://img.shields.io/github/v/release/railgun-reloaded/subsquid-client?label=) |
| Scanner         | Event scanner for RAILGUN transactions | [scanner](https://github.com/railgun-reloaded/scanner)                 | ![Latest Release](https://img.shields.io/github/v/release/railgun-reloaded/scanner?label=)         |
| Snapshot        | Snapshot provider for blockchain state | [snapshot](https://github.com/railgun-reloaded/snapshot)               | ![Latest Release](https://img.shields.io/github/v/release/railgun-reloaded/snapshot?label=)        |

---

### 🗂️ Artifacts

| Name         | Description                                                     | Repo                                                                               | Latest Release                                                                                           |
| ------------ | --------------------------------------------------------------- | ---------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------- |
| IPFS Network | Decentralized way to fetch RAILGUN and PPOI artifacts from IPFS | [ipfs-artifact-fetcher](https://github.com/railgun-reloaded/ipfs-artifact-fetcher) | ![Latest Release](https://img.shields.io/github/v/release/railgun-reloaded/ipfs-artifact-fetcher?label=) |

---

### 🔒 Cryptography

| Name         | Description                                                        | Repo                                                             | Latest Release                                                                                  |
| ------------ | ------------------------------------------------------------------ | ---------------------------------------------------------------- | ----------------------------------------------------------------------------------------------- |
| Crypto Lite  | Minimal dependency implementation (eddy, Edwards, Poseidon, bn254) | [crypto-lite](https://github.com/railgun-reloaded/crypto-lite)   | ![Latest Release](https://img.shields.io/github/v/release/railgun-reloaded/crypto-lite?label=)  |
| Cryptography | Full cryptographic implementation (needs audit)                    | [cryptography](https://github.com/railgun-reloaded/cryptography) | ![Latest Release](https://img.shields.io/github/v/release/railgun-reloaded/cryptography?label=) |

---

### 👛 Wallet

| Name   | Description                                              | Repo                                                 | Latest Release                                                                            |
| ------ | -------------------------------------------------------- | ---------------------------------------------------- | ----------------------------------------------------------------------------------------- |
| Wallet | Client-side wallet SDK for managing private transactions | [wallet](https://github.com/railgun-reloaded/wallet) | ![Latest Release](https://img.shields.io/github/v/release/railgun-reloaded/wallet?label=) |

#### Core Dependencies

| Name                        | Description                                       | Repo                                                                         | Latest Release                                                                                        |
| --------------------------- | ------------------------------------------------- | ---------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------- |
| Hierarchical Derivation     | Wallet operations (addresses, HD, key derivation) | [wallet-node](https://github.com/railgun-reloaded/wallet-node)               | ![Latest Release](https://img.shields.io/github/v/release/railgun-reloaded/wallet-node?label=)        |
| 0zk Addresses               | RAILGUN address encoding and decoding             | [0zk-addresses](https://github.com/railgun-reloaded/0zk-addresses)           | ![Latest Release](https://img.shields.io/github/v/release/railgun-reloaded/0zk-addresses?label=)      |
| UTXO Manager                | UTXO solver (NEEDS REPO, TO BE WORKED ON)         | TBD                                                                          | N/A                                                                                                   |
| Merkle Tree Balance Manager | Balance management using Merkle trees             | [merkletree-manager](https://github.com/railgun-reloaded/merkletree-manager) | ![Latest Release](https://img.shields.io/github/v/release/railgun-reloaded/merkletree-manager?label=) |

<details open>
<summary><strong>📁 Wallet sub-modules</strong></summary>

```
Wallet
├─ 📁 Base Wallet
│   ├─ 📁 Software Wallet
│   ├─ 📁 Multi-Signature
│   └─ 📁 Hardware Wallet
│
└─ 📁 Balance Scanning
    ├─ 📁 Note Commitment Indexer
    ├─ 📁 Nullifier Indexer
    ├─ 📁 Ciphertext indexer
    └─ 📁 Fee Calculation
```

</details>

---

### 🧮 Provers

| Name   | Description         | Repo                                                 | Latest Release                                                                            |
| ------ | ------------------- | ---------------------------------------------------- | ----------------------------------------------------------------------------------------- |
| Prover | Base proving system | [prover](https://github.com/railgun-reloaded/prover) | ![Latest Release](https://img.shields.io/github/v/release/railgun-reloaded/prover?label=) |

<details open>
<summary><strong>📁 Prover sub-modules</strong></summary>

```
Prover
├─ 📁 Base
├─ 📁 WASM
└─ 📁 Mobile
```

</details>

---

### 🌐 Messaging Layer

| Name      | Description                               | Repo                                                    | Latest Release                                                                            |
| --------- | ----------------------------------------- | ------------------------------------------------------- | ----------------------------------------------------------------------------------------- |
| messaging | Base messaging system layer based on waku | [messaging](https://github.com/railgun-reloaded/prover) | ![Latest Release](https://img.shields.io/github/v/release/railgun-reloaded/prover?label=) |

<details open>
<summary><strong>📁 Messaging Layer sub-modules</strong></summary>

```
Messaging
├─ 📁 Waku Base
├─ 📁 Waku Multi-Signature
└─ 📁 Waku Broadcasters
```

</details>

---

### 📜 Contracts

| Name          | Description                         | Repo                                                                   | Latest Release                                                                                     |
| ------------- | ----------------------------------- | ---------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------- |
| Contract      | Contract interaction with ethers.js | [contract-ethers](https://github.com/railgun-reloaded/contract-ethers) | ![Latest Release](https://img.shields.io/github/v/release/railgun-reloaded/contract-ethers?label=) |
| Contract ABIs | Contract ABIs for RAILGUN contracts | [contract-abis](https://github.com/railgun-reloaded/contract-abis)     | ![Latest Release](https://img.shields.io/github/v/release/railgun-reloaded/contract-abis?label=)   |

---

### ⚡ Circuits

| Name        | Description                | Repo                                                           | Latest Release                                                                                 |
| ----------- | -------------------------- | -------------------------------------------------------------- | ---------------------------------------------------------------------------------------------- |
| Circuits-v2 | Zero-knowledge circuits v2 | [circuits-v2](https://github.com/railgun-reloaded/circuits-v2) | ![Latest Release](https://img.shields.io/github/v/release/railgun-reloaded/circuits-v2?label=) |

---

### 🔧 Misc

| Name          | Description                     | Repo                                                               | Latest Release                                                                                   |
| ------------- | ------------------------------- | ------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------ |
| TSConfig      | Shared TypeScript configuration | [tsconfig](https://github.com/railgun-reloaded/tsconfig)           | ![Latest Release](https://img.shields.io/github/v/release/railgun-reloaded/tsconfig?label=)      |
| ESLint Config | Shared ESLint configuration     | [eslint-config](https://github.com/railgun-reloaded/eslint-config) | ![Latest Release](https://img.shields.io/github/v/release/railgun-reloaded/eslint-config?label=) |

---
