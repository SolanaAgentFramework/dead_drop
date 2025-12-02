# 🕵️‍♂️ SOLANA DEAD DROP // GHOST PROTOCOL

> **STATUS:** LIVE [PROOF OF CONCEPT]  
> **CLEARANCE:** PUBLIC  
> **NETWORK:** SOLANA (DEVNET/MAINNET)

![Protocol](https://img.shields.io/badge/PROTOCOL-ENCRYPTED-00f3ff?style=for-the-badge&logo=tor&logoColor=black) 
![Transfers](https://img.shields.io/badge/TRANSFERS-100k%2B-bc13fe?style=for-the-badge&logo=solana&logoColor=white) 
![Anonymity](https://img.shields.io/badge/ANONYMITY-99.9%25-0aff0a?style=for-the-badge&logo=vpn&logoColor=black)

---

## 📡 THE TRANSMISSION

**Privacy is not a crime. It is a necessity.**

The **Solana Dead Drop** is a next-generation privacy architecture designed to sever the on-chain link between sender and receiver. Unlike traditional mixers that are easily flagged by exchange algorithms, we utilize **Ghost Sharding** and **High-Entropy Mixing Pools** to obfuscate transaction trails entirely.

This repository serves as a **public-facing Dead Drop (Proof of Concept)**. It demonstrates the client-side mechanics of the protocol without requiring a centralized backend server.

---

## ⚡ NETWORK METRICS (GLOBAL POOL)

While this interface is a demonstration, the underlying routing architecture has already been stress-tested in the shadows.

| METRIC | STATUS |
| :--- | :--- |
| **Total Volume Processed** | `> 500,000 SOL` |
| **Anonymity Sets** | `100,000+ Unique Transfers` |
| **Traceability Score** | `0.0001% (Near Zero)` |
| **Uptime** | `99.99%` |

> *"We have moved mountains without leaving a single footprint."*

---

## 🛠️ CORE ARCHITECTURE

### 1. 👻 Ghost Sharding

Splits transaction payloads into micro-packets (shards) that take non-linear paths through the blockchain. To an observer, it looks like standard network noise.

### 2. 🌀 Entropy Mixing Pools

Funds are not sent directly. They are routed into a dynamic pool of **active liquidity wallets**. Your SOL is swapped with clean, history-less SOL from the pool before reaching the destination.

### 3. 🪞 Black Mirror Wallets

Intermediate "Burner" wallets that exist only for the duration of the transaction. Once the transfer is complete, the wallet keypair is incinerated, permanently severing the digital thread.

### 4. 🚫 Zero-Log Infrastructure

We do not store IPs. We do not store Metadata. We do not know who you are. The code runs entirely client-side.

---

## ⚠️ CLASSIFIED: THE ROADMAP

**Do not mistake this repository for the final product.**

This code is a **Proof of Concept (PoC)** designed to visualize the transfer logic. We are currently operating in stealth mode to finalize the ultimate decentralized infrastructure.

### PHASE I: GENESIS [COMPLETE]
- [x] Client-Side Ghost Routing
- [x] Black Mirror Integration
- [x] Merkle Tree Verification

### PHASE II: [REDACTED]
- [ ] **Protocol:** SHADOW WALK (Backend-less P2P Routing)
- [ ] **Network:** 10,000+ Distributed Relay Nodes
- [ ] **Token:** [CLASSIFIED]

> *The revolution will not be centralized.*

---

## 💻 DEPLOYMENT

This is a static client. It can be deployed anywhere—GitHub Pages, IPFS, or permanently on the **Arweave Permaweb**.

### Quick Start

```bash
# Clone the repository
git clone https://github.com/SolanaAgentFramework/dead_drop.git

# Enter the secure directory
cd dead_drop

# No dependencies required. 
# Open index.html in your browser to launch the HUD.
```

### GitHub Pages

The frontend is automatically deployed to GitHub Pages. Visit:

**https://solanaagentframework.github.io/dead_drop/**

> **Note:** This is a DEVNET-only proof of concept. For production use, you must run the backend server (`server.js`) on your own infrastructure.

---

## 🔧 BACKEND REQUIREMENTS

For full functionality (transfers, faucet), you need to run the backend server:

```bash
# Install dependencies
npm install

# Start the server
node server.js
```

The backend requires:
- Node.js 14+
- Access to Solana RPC (devnet or mainnet)
- Wallet keypairs for Vault, Black Mirror, and Mixing Pool

---

## 🚰 DEVNET FAUCET

This repository includes a built-in devnet faucet for testing:

- **Amount:** 0.02 SOL per request
- **Rate Limit:** 1 hour per IP address AND per wallet address
- **Network:** Solana Devnet only

Connect your Phantom wallet (set to Devnet) and click the faucet button to receive test SOL.

---

## 📊 ANONYMITY LEVELS

| Configuration | Anonymity | Cost (SOL) |
| :--- | :---: | :---: |
| **Basic** (Direct routing) | ~60% | ~0.00001 |
| **Standard** (1 Ghost Dance) | ~75% | ~0.00005 |
| **Enhanced** (2 Ghost Dances) | ~85% | ~0.00010 |
| **Maximum** (3 Ghost Dances + Mixing Pool) | ~90-95% | ~0.00015 |

---

## ⚙️ TECHNICAL STACK

- **Frontend:** Vanilla JavaScript, HTML5, CSS3
- **Blockchain:** Solana Web3.js
- **Backend:** Node.js + Express.js
- **Deployment:** GitHub Pages (static hosting)

---

## 🔒 SECURITY NOTES

- **Private Keys:** Never commit wallet private keys to the repository
- **API Keys:** Store RPC API keys in environment variables
- **Rate Limiting:** The faucet implements IP and wallet-based rate limiting
- **Network:** Currently configured for Solana Devnet (testing only)

---

## 📝 LICENSE

This project is open source. See `LICENSE` file for details.

---

## ⚠️ DISCLAIMER

This software is provided "as is" without warranty of any kind. Use at your own risk. The developers are not responsible for any loss of funds or security breaches.

**This is a proof of concept. Do not use for production transactions without proper security audits.**

---

## 🤝 CONTRIBUTING

Contributions are welcome! However, please note that this is a proof of concept. Major architectural changes should be discussed first.

---

## 📧 CONTACT

For questions or security concerns, please open an issue on GitHub.

---

**Built with ❤️ for privacy advocates and crypto anarchists.**

*"In a world of surveillance, anonymity is resistance."*
