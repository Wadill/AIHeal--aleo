# **AIHeal**

Welcome to **AIHeal**, a decentralized AI-powered healthcare platform built on **Aleo** — putting patients back in control of their medical data with encrypted *Intelligent Health NFTs*, real-time AI diagnostics, and verifiable sharing with doctors — all protected by zero-knowledge privacy.

**Repository:** [https://github.com/Wadill/Synapse](https://github.com/Wadill/Synapse)  
*(Note: Repo name will be updated to AIHeal soon)*  
**Live Demo:** https://synapse-puce-iota.vercel.app/  
*(Demo will be migrated to AIHeal domain/branding)*

## LIVE on MAINNET!  
Contract: 0x1F0441f4aD7ddAf44187F780afc6AacdC270Bba7

---

## **What It Does**

AIHeal lets patients own their lifetime medical records as **updatable, encrypted Intelligent Health NFTs** on Aleo.

1. Upload records  
2. AI analyzes privately (leveraging Aleo's zero-knowledge execution)  
3. Receive instant diagnostics & personalized insights  
4. Share selectively & verifiably with doctors or emergency responders

All with **native privacy**, **minimal fees**, and **fast finality** thanks to Aleo's zk design.

---

## **The Problem It Solves**

Centralized healthcare systems:  
❌ leak data  
❌ lock patients out  
❌ cost too much  

AIHeal fixes this with **Aleo’s zero-knowledge proofs**, **private execution**, and **programmable privacy primitives** to deliver:

- True data ownership  
- HIPAA-grade (and beyond) privacy by design  
- Instant, global interoperability without exposure  
- Consumer-scale UX with full confidentiality

---

## **Features**

- **Encrypted medical records** stored on IPFS + decrypted only via zero-knowledge authorized access  
- **Intelligent Health NFTs (ERC-721A compatible)** representing lifetime medical records  
- **Real-time AI diagnostics** (skin, ECG, blood panels) via off-chain/private AI workers  
- **Zero-knowledge verifiable credentials** for doctor authentication & patient identity  
- **Emergency QR access** (“break-glass” selective disclosure)  
- **The Graph-powered dashboard** with rich visualizations  
- **Wearables sync** (Apple Health, Google Fit, Oura support coming)

---

## **Technologies Used**

**Frontend:**

- Next.js 14, TypeScript, Tailwind CSS  
- Framer Motion, Recharts  

**Blockchain:**

- Aleo (zero-knowledge Layer 1)  
- Leo programming language (for private logic where applicable)  

**Encryption & Privacy:**

- Aleo’s native zero-knowledge proofs  
- Lit Protocol (for selective decryption where needed)  

**Storage:**

- IPFS  
- NFT.Storage  
- web3.storage  

**Smart Contracts:**

- Solidity (for NFT compatibility), Hardhat  
- ERC-721A  
- Leo circuits (for private computations)  

**Wallet & Indexing:**

- wagmi, viem, RainbowKit  
- The Graph  

**AI:**

- Hugging Face  
- Custom biomedical models (hybrid on/off-chain with private inference paths)

---

## **How We Built It**

- Started with a privacy-first architecture suited for Aleo  
- Deployed **Intelligent Health NFT** + access control contracts  
- Built encrypted upload flow → IPFS → privately referenced CID → on-chain proof  
- Created off-chain **AI workers** listening for events, running inference privately, and committing zk-verified results  
- Integrated **zero-knowledge credentials** for verifiable doctor/patient proofs without revealing data  
- Indexed user metadata (non-sensitive) with **The Graph** for instant dashboards  
- Deployed on Aleo testnet → ready for mainnet

---

## **Roadmap**

### **Wave 1 (Done)** – Testnet MVP

- Encrypted records  
- Intelligent Health NFTs  
- Basic AI diagnostics  

### **Wave 2 – Mainnet + First 1,000 Users**

- Full AI engine (3 medical models)  
- Zero-knowledge doctor verification marketplace  
- Apple Health / Oura sync  
- Cross-chain health credentials (via Aleo bridges)  

### **Wave 3 – Category Leader**

- Insurance & clinical trials marketplace (private matching)  
- Hospital integrations (India/LATAM pilot)  
- AIHeal Predict (long-term risk scoring with zk proofs)  
- `$AIHEAL` token + DAO  

### **Wave 4 – Global Standard**

- 1M+ users  
- Major wearable & insurer partnerships  
- The Web3 private EHR layer  

---

## **Challenges We Ran Into**

- Aligning off-chain AI inference latency with Aleo’s proof generation & finality  
- Keeping transaction + proof costs low for frequent medical record updates  
- Achieving real **HIPAA-grade privacy** while enabling useful sharing (solved natively via Aleo zk + selective disclosure)

---

## **What We Learned**

Aleo is one of the strongest platforms for real consumer health applications that require **true privacy by default**.

- Aleo’s zero-knowledge execution + Lit Protocol = genuine end-to-end medical privacy  
- Designing with privacy-first constraints leads to better architecture, UX, and future scalability

---

## **Installation**

```bash
git clone https://github.com/Wadill/Synapse.git
cd Synapse
npm install

cp .env.example .env.local
# Add your WalletConnect ID & private key

npm run dev
```

*(Repo & package updates to AIHeal coming soon)*

---

## **Contributing**

Contributions welcome!

1. Fork  
2. Create a branch  
3. Submit a PR  

For major changes, open an issue first.

---

## **License**

MIT License — see `LICENSE`

---

## **Acknowledgments**

- Aleo team & the zero-knowledge community  
- Lit Protocol team  
- The Graph team  
- Global Web3 health community  
- Early supporters & testers

---

# **Your health. Your data. Your AIHeal.**
```