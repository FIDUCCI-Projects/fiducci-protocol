# FIDUCCI | Tokenization as a Service (TaaS) 🛡️⚖️

### Institutional-Grade RWA Infrastructure on Arbitrum.

[![Chainlink Hackathon 2026](https://img.shields.io/badge/Chainlink-Hackathon_2026-blue)](https://devpost.com)
[![Arbitrum Sepolia](https://img.shields.io/badge/Arbitrum-Sepolia_Testnet-28A0F0)](https://sepolia.arbiscan.io/)
[![Live dApp](https://img.shields.io/badge/Live_dApp-Vercel-black?logo=vercel)](https://front-end-lemon-two.vercel.app/)

> 🔗 **Live Demo:** [https://front-end-lemon-two.vercel.app/](https://front-end-lemon-two.vercel.app/)
> 
> 🎥 **[Watch our Pitch Video Here]([LINK_AL_VIDEO_AQUI])**

FIDUCCI is a decentralized "Trust Stack" designed to bridge high-value Real World Assets (RWA) with on-chain liquidity. By combining professional legal frameworks (**Mexican Land Trusts**) with cutting-edge Web3 technology (**Chainlink CRE** and **FHE**), we completely close the legal and technical Trust Gap. We do not tokenize property titles; we enable the tokenization of mathematically verified **economic rights** and **isolated economic flows** for large-scale real estate assets.

---

## 🏗️ Core Architecture: The "Trust Stack"

![FIDUCCI Architecture]([LINK_A_LA_IMAGEN_DE_ARQUITECTURA_AQUI])

Our infrastructure is built on four fundamental pillars to ensure institutional adoption:

| Pillar | Technology | Purpose |
| :--- | :--- | :--- |
| **Legality** | Mexican Fideicomiso (Land Trust) | 1:1 Legal backing, bankruptcy-remote isolation, and regulatory compliance. |
| **Solidity** | Arbitrum L2 + Stylus | Scalable, low-latency, and secure execution layer for institutional-grade token issuance. |
| **Verifiability** | Chainlink CRE & Functions | Real-time verification via institutional APIs (Intelimetrica/Tinsa) connecting on-chain logic with off-chain legal data. |
| **Privacy** | FHE (Fully Homomorphic Encryption) | Data protection for sensitive investor information and encrypted economic flow distribution. |

---

## 🇲🇽 Genesis Case: Benchmarking Scale

To stress-test our TaaS engine, we are using a **$6M USD Land Development** in Puebla, Mexico, as our primary benchmark. 

- **Asset Value:** $6,000,000 USD
- **Strategy:** Tokenizing the mathematically verified economic rights and expected economic flows of a **20-hectare raw land development**. The physical asset remains completely legally isolated and protected by the Fideicomiso, while the economic rights become liquid and on-chain enforceable.
- **Oracle Pipeline:** Automated workflows connecting the state's Notarial/Cadastral and Trust data with Arbitrum.

---

## 📜 Smart Contracts (Testnet)

The FIDUCCI protocol core logic is currently deployed and verifiable on the **Arbitrum Sepolia Testnet**:

* **Main Beneficiary Rights Contract:** [`0x894cdA6feBf63aC3e4ae94e639D5D61eB9745d83`](https://sepolia.arbiscan.io/address/0x894cdA6feBf63aC3e4ae94e639D5D61eB9745d83)

---

## 🔍 For Hackathon Judges: Where to Look

To save you time evaluating our "Trust Stack", here is where our core integrations live across our ecosystem:

* **Chainlink CRE & Functions:** Explore the oracle integration bridging off-chain legal valuation with our smart contracts in the [`cre_automation`](https://github.com/FIDUCCI-Projects/cre_automation) repository.
* **Arbitrum Smart Contracts:** Navigate to the [`rebeka_contracts`](https://github.com/FIDUCCI-Projects/rebeka_contracts) repository for the logic governing the isolated Economic Rights issuance.
* **Frontend (dApp):** The complete institutional investor dashboard UI is located in the [`FrontEnd`](https://github.com/FIDUCCI-Projects/FrontEnd) repository.

---

## 🛠️ Technical Stack & Integrations

- **Network:** [Arbitrum One / Sepolia Testnet](https://arbitrum.io/) (Planned migration to Stylus for high-performance compute).
- **Oracle Framework:** [Chainlink Functions](https://chain.link/) & Chainlink Runtime Environment (CRE).
- **Data Oracles:** Real-time integration with data providers like **Intelimetrica** APIs for localized market data.
- **Smart Contracts:** Solidity-based vault and economic rights distribution logic.

---

## 📂 Repository Directory

This repository (`fiducci-protocol`) serves as the central hub and presentation layer for the FIDUCCI ecosystem. The core infrastructure is modularized across the following specialized repositories within our organization:

* [**FrontEnd**](https://github.com/FIDUCCI-Projects/FrontEnd) - The frontend dApp and institutional investor dashboard (UI/UX).
* [**cre_automation**](https://github.com/FIDUCCI-Projects/cre_automation) - Off-chain logic, Data Oracles, and **Chainlink CRE** integration workflows.
* [**rebeka_contracts**](https://github.com/FIDUCCI-Projects/rebeka_contracts) - The core Solidity Smart Contracts deployed on Arbitrum handling the isolated economic rights.
* [**rebeka_mocked_back**](https://github.com/FIDUCCI-Projects/rebeka_mocked_back) - Backend services and API mocking infrastructure.
* [**fiducci-docs**](https://github.com/FIDUCCI-Projects/fiducci-docs) - Comprehensive Whitepaper, Legal Framework, and Architecture Diagrams.

---

## 🚀 Roadmap

- [x] **Phase 1:** Legal Design & Technical Architecture.
- [x] **Phase 2:** MVP Deployment on Arbitrum Sepolia.
- [x] **Phase 3:** Chainlink CRE Integration & Beta Testing.
- [ ] **Phase 4:** Genesis Case Pilot Launch ($6M USD Asset).

---

## 👥 The Founding Team

- **RoM** - Strategy & Product Lead (Legal-Tech Architect).
- **Artur** - Lead Backend & Smart Contract Developer (Chainlink Expert).
- **Robin** - Front-End Developer & UI/UX Designer.

---

*Disclaimer: FIDUCCI is currently in the development phase. Information provided here is for technical and educational purposes only for the Chainlink Convergence Hackathon 2026.*
