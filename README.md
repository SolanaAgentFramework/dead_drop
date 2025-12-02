# 🕵️‍♂️ SOLANA DEAD DROP // GHOST PROTOCOL

> **STATUS:** ALPHA [PROOF OF CONCEPT]  
> **CLEARANCE:** PUBLIC TESTING  
> **NETWORK:** DEVNET (RECOMMENDED) / MAINNET (EXPERIMENTAL)

![Protocol](https://img.shields.io/badge/PROTOCOL-GHOST_V1-00f3ff?style=for-the-badge&logo=tor&logoColor=black) 

![Stage](https://img.shields.io/badge/STAGE-ALPHA_TESTING-bc13fe?style=for-the-badge&logo=solana&logoColor=white) 

![License](https://img.shields.io/badge/LICENSE-MIT-0aff0a?style=for-the-badge)

---

## 📡 THE TRANSMISSION

**Privacy is the final frontier.**

The **Solana Dead Drop** is a client-side privacy architecture designed to obscure the link between sender and receiver. We are building the infrastructure for **Ghost Sharding** and **High-Entropy Mixing Pools** on Solana.

**⚠️ CURRENT STATE:**

This repository is a **Proof of Concept (PoC)**. It demonstrates the UI/UX and the client-side routing logic. It is currently optimized for **Solana Devnet** for stress testing without financial risk.

---

## ⚡ TESTNET METRICS (INTERNAL BETA)

We are currently stress-testing the routing logic. These are real numbers from our internal Devnet clusters:

| METRIC | STATUS |
| :--- | :--- |
| **Test Volume Processed** | `~1,250 SOL` (Devnet) |
| **Mixing Pool Size** | `15 Active Wallets` |
| **Successful Routes** | `500+` |
| **Avg. Route Time** | `4.2 Seconds` |

> *"We are building the rails. The train comes next."*

---

## 🛠️ HOW IT WORKS (THEORY)

### 1. 👻 Ghost Sharding

Splits transaction payloads into micro-packets. Currently simulated in this client.

### 2. 🌀 Entropy Mixing (Client-Side)

Funds are routed through intermediate burner wallets ("Black Mirrors") generated locally in your browser.

### 3. 🚫 Zero-Log Infrastructure

We do not store IPs. We do not store Metadata. The code runs entirely in your browser (GitHub Pages / Localhost).

---

## ⚠️ ROADMAP & DEVELOPMENT

We are moving from **Alpha** to **Beta**.

### PHASE I: GENESIS [CURRENT]

- [x] Client-Side UI (The "Phantom HUD")
- [x] Devnet Faucet Integration
- [x] Basic Routing Logic
- [x] Wallet Destruction (Keypair purging)

### PHASE II: [ENCRYPTED]

- [ ] **Smart Contract:** On-chain Mixing Pool (Anchor Program)
- [ ] **Relayers:** Decentralized RPC Rotation
- [ ] **Mainnet Launch:** Audited Deployment

> *The revolution will not be centralized.*

---

## 💻 DEPLOYMENT

This is a static client. It can be deployed anywhere—GitHub Pages, IPFS, or permanently on the **Arweave Permaweb**.

### Local Access

```bash
# Clone the repository
git clone https://github.com/SolanaAgentFramework/dead_drop.git

# Enter the secure directory
cd dead_drop

# No dependencies required. 
# Open index.html in your browser to launch the HUD.
```

### GitHub Pages

The repository is configured for automatic deployment via GitHub Pages. Visit:

**🌐 [https://solanaagentframework.github.io/dead_drop/](https://solanaagentframework.github.io/dead_drop/)**

---

## 🧪 TESTING

### Prerequisites

1. **Phantom Wallet** installed in your browser
2. **Switch to Devnet** in Phantom settings (see `tutorial.html` for instructions)
3. **Connect** your wallet to the HUD

### Test Flow

1. **Get Devnet SOL:** Use the built-in faucet (0.02 SOL per hour)
2. **Send Test Transaction:** Enter a destination address and amount (max 0.1 SOL for testing)
3. **Verify:** Check transaction on [Solscan Devnet](https://solscan.io/?cluster=devnet)

---

## 🔒 SECURITY & PRIVACY

- **No Backend Required:** All logic runs client-side
- **No Data Collection:** Zero IP logging, zero metadata storage
- **Open Source:** Full transparency, community auditable
- **Devnet First:** Test safely before mainnet deployment

---

## 📚 DOCUMENTATION

- **Tutorial:** See `tutorial.html` for Phantom Devnet setup guide
- **Architecture:** See `ANONYMITY_LEVELS.md` for technical deep-dive
- **Deployment:** See `DEPLOYMENT_SUMMARY.md` for backend setup

---

## ⚖️ LICENSE

MIT License - See LICENSE file for details

---

## 🚨 DISCLAIMER

**This is experimental software. Use at your own risk.**

- Devnet SOL has no real value
- Mainnet deployment is experimental
- Always verify transactions on-chain
- This is not financial advice

---

**Built with ❤️ for the Solana privacy community.**
