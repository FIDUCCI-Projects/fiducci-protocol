# FIDUCCI | Tokenization as a Service (TaaS) 🛡️⚖️

### Institutional-Grade RWA Infrastructure on Arbitrum.

<p align="left">
  <a href="https://soliditylang.org/">
    <img src="https://img.shields.io/badge/Solidity-%23363636.svg?style=for-the-badge&logo=solidity&logoColor=white" alt="Solidity">
  </a>
  <a href="https://arbitrum.io/">
    <img src="https://img.shields.io/badge/Arbitrum-28A0F0?style=for-the-badge&logo=Arbitrum&logoColor=white" alt="Arbitrum">
  </a>
  <a href="https://chain.link/cre">
    <img src="https://img.shields.io/badge/Chainlink_CRE-375BD2?style=for-the-badge&logo=Chainlink&logoColor=white" alt="Chainlink CRE">
  </a>
  <a href="https://front-end-lemon-two.vercel.app/">
  <img src="https://img.shields.io/badge/Live_dApp-Vercel-black?style=for-the-badge&logo=vercel" alt="Live dApp">
  </a>
</p>

> 🔗 **Live Demo:** [https://front-end-lemon-two.vercel.app/](https://front-end-lemon-two.vercel.app/)
> 
> 🎥 **[Watch our Pitch Video Here]([LINK_AL_VIDEO_AQUI])**

FIDUCCI is a decentralized "Trust Stack" designed to bridge high-value Real World Assets (RWA) with on-chain liquidity. By combining professional legal frameworks (Mexican Land Trusts) with cutting-edge Web3 technology (Arbitrum, Chainlink CRE, and FHE), we completely close the legal and technical Trust Gap. We do not tokenize property titles; we enable the tokenization of mathematically verified economic rights and isolated economic flows for a diverse range of institutional-grade physical assets.

---

## 🏗️ Core Architecture: The "Trust Stack"

![FIDUCCI Architecture](https://github.com/FIDUCCI-Projects/fiducci-docs/blob/main/architecture/arquitectura.jpg)

Our infrastructure is built on four fundamental pillars to ensure institutional adoption:

| Pillar | Technology | Purpose |
| :--- | :--- | :--- |
| **Legality** | **Mexican Fideicomiso (Legal Trust)** | 1:1 Legal backing, bankruptcy-remote isolation, and regulatory compliance for diverse asset classes. |
| **Solidity** | **Arbitrum L2** | Scalable, low-latency, and secure execution layer for institutional-grade token issuance. |
| **Verifiability** | **Chainlink CRE** | Decentralized verification engine connecting on-chain logic with off-chain legal data and real-world asset valuation. |
| **Privacy** | **FHE (Fully Homomorphic Encryption)** | Data protection for sensitive investor information and encrypted economic flow distribution. |

---
### 🛠️ Technical Breakdown

| Component | Stack | Responsibility |
| :--- | :--- | :--- |
| **Smart Contracts** | Solidity / Arbitrum | Logic for issuance and management of RWA tokens. |
| **Oracle Logic** | Chainlink CRE | Bridges legal valuation with on-chain execution. |
| **Mocked Backend** | Node.js / Express | Simulates real-world cadastral and bank APIs for testing. |
| **Frontend** | React / Vercel | Dashboard for institutional investors to manage assets. |

---

## ⚙️ How it Works: The Trust Loop

1. **Asset Onboarding:** A $6M USD land asset in Puebla is locked into a Mexican Land Trust (Fideicomiso).
2. **Economic Rights Isolation:** Specific economic rights are isolated legally and mirrored on-chain via **Arbitrum**.
3. **Chainlink CRE Verification:** Our workflow triggers a verification of the legal trust status and asset valuation via **Intelimetrica APIs**.
4. **Token Issuance:** Once verified by CRE, the protocol allows the issuance of tokens representing the isolated economic flows.
5. **Encrypted Distribution:** Investor data and distribution flows are handled via **FHE** to ensure institutional privacy.

---

## 🇲🇽 Genesis Case: Benchmarking Scale

To stress-test our TaaS engine, we are using a **$6M USD Land Development** in Puebla, Mexico, as our primary benchmark. 

- **Asset Value:** $6,000,000 USD
- **Strategy:** Tokenizing the mathematically verified economic rights and expected economic flows of a **20-hectare raw land development**.
- **Oracle Pipeline:** Automated workflows connecting the state's Notarial/Cadastral and Trust data with Arbitrum via Chainlink CRE.
  
---

## 📜 Deployed Contracts (Arbitrum Sepolia)

The FIDUCCI "Trust Stack" is live on the **Arbitrum Sepolia Testnet**. We have modularized our deployment to ensure a verifiable link between legal assets and on-chain economic rights.

### ⚡ Operational Core & Oracle Bridge
* **Protocol Bridge (Active):** [`0x894cdA6feBf63Ac3e4ae94e639D5D61eB9745d83`](https://sepolia.arbiscan.io/address/0x894cdA6feBf63Ac3e4ae94e639D5D61eB9745d83)
  *This contract handles real-time verification and valuation reports via Chainlink CRE. It is the primary entry point for our "On Report" workflows.*

### 🔍 Technical Deep Dive
For a full list of auxiliary contracts (Tokens, Vaults, and Escrows) and detailed deployment scripts, please refer to our dedicated contracts repository:

👉 [**Go to rebeka_contracts README**](https://github.com/FIDUCCI-Projects/rebeka_contracts)

> 💡 **Note to Judges:** To audit the Solidity implementation of our Trust logic, valuation engines, and automated workflows, we recommend reviewing the source code in the repository linked above. Contracts are currently in the final integration phase for the live demo.

---

## 🔍 For Hackathon Judges: Where to Look

To save you time evaluating our "Trust Stack", here is where our core integrations live across our ecosystem:

* **Chainlink CRE (Runtime Environment):** Explore the decentralized workflows bridging off-chain legal status with our smart contracts in the [`cre_automation`](https://github.com/FIDUCCI-Projects/cre_automation) repository. This is our core engine for verifiable trust.
* **Arbitrum Smart Contracts:** Navigate to the [`rebeka_contracts`](https://github.com/FIDUCCI-Projects/rebeka_contracts) repository for the Solidity logic governing the issuance and management of isolated Economic Rights.
* **Frontend (dApp):** The complete institutional investor dashboard UI, built to interact with our Arbitrum deployment, is located in the [`FrontEnd`](https://github.com/FIDUCCI-Projects/FrontEnd) repository.
---

## 🛠️ Technical Stack & Integrations

- **Network:** [Arbitrum One / Sepolia Testnet](https://arbitrum.io/).
- **Execution:** Solidity-based Smart Contracts (Planned migration to **Arbitrum Stylus** for enhanced performance).
- **Oracle Framework:** **Chainlink Runtime Environment (CRE)**.

---

## 📂 Repository Directory

This repository (`fiducci-protocol`) serves as the central hub for the ecosystem. Our infrastructure is modularized across these specialized repositories:

* [**FrontEnd**](https://github.com/FIDUCCI-Projects/FrontEnd) - The frontend dApp and institutional investor dashboard. **Live at:** [front-end-lemon-two.vercel.app](https://front-end-lemon-two.vercel.app/)
* [**cre_automation**](https://github.com/FIDUCCI-Projects/cre_automation) - Off-chain logic and **Chainlink CRE** integration workflows.
* [**rebeka_contracts**](https://github.com/FIDUCCI-Projects/rebeka_contracts) - Core Solidity Smart Contracts on Arbitrum handling isolated economic rights.
* [**rebeka_mocked_back**](https://github.com/FIDUCCI-Projects/rebeka_mocked_back) - Backend services and API mocking infrastructure for legal/valuation data.
* [**fiducci-docs**](https://github.com/FIDUCCI-Projects/fiducci-docs) - **Documentation Hub** containing legal, technical, and architectural blueprints.

---

## 📚 Technical & Legal Documentation

Detailed documentation for the FIDUCCI protocol can be found in our [Documentation Hub](https://github.com/FIDUCCI-Projects/fiducci-docs):

* 🏗️ [**Architecture Diagrams**](https://github.com/FIDUCCI-Projects/fiducci-docs/tree/main/architecture) - Visual breakdown of the "Trust Stack".
* ⚖️ [**Legal Framework**](https://github.com/FIDUCCI-Projects/fiducci-docs/tree/main/legal) - Detailed analysis of the Mexican Land Trust (Fideicomiso) integration.
* 📄 [**Technical Whitepaper**](https://github.com/FIDUCCI-Projects/fiducci-docs/tree/main/whitepaper) - Deep dive into protocol mechanics and economic flow isolation.

---

## 🚀 Roadmap

- [x] **Phase 1:** Legal Design & Technical Architecture.
- [x] **Phase 2:** MVP Deployment on Arbitrum Sepolia.
- [x] **Phase 3:** **Chainlink CRE Integration (Hackathon Milestone! 🏆)**.
    - *Includes real-time valuation engine powered by **Intelimetrica APIs**.*
- [ ] **Phase 4:** **Stylus Migration** for high-performance execution.
- [ ] **Phase 5:** Genesis Case Pilot Launch ($6M USD Asset in Puebla).

---

## 👥 The Founding Team

- **RoM** - Strategy & Product Lead (Legal-Tech Architect).
- **Artur** - Lead Backend & Smart Contract Developer (Chainlink Expert).
- **Robin** - Front-End Developer & UI/UX Designer.

---

*Disclaimer: FIDUCCI is currently in the development phase. Information provided here is for technical and educational purposes only for the Chainlink Convergence Hackathon 2026.*
