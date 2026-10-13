## **Rust Developer | Blockchain · Security Audits · Low Latency Systems**  
Engineering and auditing secure, high-performance Rust systems for DeFi, trading platforms, and blockchain infrastructure.

##### Looking for an experienced Rust developer or security auditor? Reach out: [@Pushkarm029](https://t.me/Pushkarm029)

---
### **Private Security Audits:**

| # | Language | Protocol | Type | Findings | Date | Firm |
|---|----------|----------|------|----------|------|------|
| 01 | Rust | ApeChurch | Solana | 3 Medium, 3 Low | Jul 2026 | Hashlock |
| 02 | Rust | Arcane Protocol - 2nd Audit | Solana | 1 Low | Jul 2026 | Hashlock |
| 03 | Rust | OmniBridge - Aptos | Near | 1 High, 2 Medium, 2 Low | Jul 2026 | AuditOne |
| 04 | Rust | DeLoreanLabs Staking | Solana | 4 High, 6 Medium, 7 Low | Jun 2026 | Hashlock |
| 05 | Rust | ZynkLabs | Solana | 1 Medium, 6 Low | Jun 2026 | Quill Audits |
| 06 | Solidity | IBC Group | DeFi | 1 High, 5 Low | Jun 2026 | Hashlock |
| 07 | Rust | via-network Stellar | Cross-chain Messaging | 3 High, 3 Medium, 21 Low | Apr 2026 | Hashlock |
| 08 | Rust | Arcane Protocol | Privacy / ZK Mixer | 1 Medium, 13 Low | Apr 2026 | Hashlock |
| 09 | Rust | Loadout Programs | Launchpad / Bonding Curve / Meteora DLMM | 4 High, 5 Medium, 19 Low | Mar 2026 | Hashlock |
| 10 | Solidity | Pool Orbit | On-chain Lottery / VRF | 4 High, 1 Medium, 1 Low | Mar 2026 | Hashlock |
| 11 | Rust | Polymesh | RWA / Regulated Securities Blockchain | 4 High, 6 Medium, 12 Low | Feb 2026 | Hashlock |
| 12 | Solidity | Optimism - Celo | OP Stack / Custom Gas Token L2 | 1 Medium | Feb 2026 | Hashlock |
| 13 | Rust | Mint Matrix | Solana | 4 High, 1 Low | Feb 2026 | Hashlock |
| 14 | Solidity | Umbrae Protocol | DeFi - DLMM | 1 High, 5 Medium, 2 Low | Jan 2026 | Hashlock |
| 15 | Solidity | Vana Protocol | DeFi | 4 Low | Dec 2025 | Hashlock |
| 16 | Rust | Tilted Social Gaming (Solana) | DeFi, Gaming | 8 Critical, 4 High, 3 Medium, 4 Low | Dec 2025 | DeCrypt0 |
| 17 | Rust | Beamable Network (Solana) | DePIN | 2 High, 2 Medium, 4 Low | Nov 2025 | Hashlock |
| 18 | Rust | ZkSync Era | Zero Knowledge EVM L2 | 1 Medium, 2 Low | Nov 2025 | Taran.Space |
| 19 | C++/Rust | Stealth | Blockchain Virtual Machine | 1 High, 2 Low | Aug 2025 | Taran.Space |
| 20 | Rust | Pyro.fun (Solana) | DeFi | 1 High | Jul 2025 | Quill Audits (Post Audit) |
| 21 | Rust | ZkSync Era | Zero Knowledge EVM L2 | 1 High, 2 Low | Jun 2025 | Taran.Space |
| 22 | Go | Stealth (Cosmos) | DeFi | 1 High, 1 Low | May 2025 | Taran.Space |
| 23 | Rust | Stealth (Polkadot - EVM) | Cross Chain Bridge | 1 Low | Apr 2025 | Taran.Space |
| 24 | Rust | Stealth (Polkadot) | DeFi | 1 High, 2 Medium | Mar 2025 | Taran.Space |
| 25 | Rust | Stealth (Polkadot) | Decentralized Identity (DeID) | 1 Medium | Mar 2025 | Taran.Space |
| 26 | Go | Stealth (Cosmos) | Virtual Machine | 2 Low | Jan 2025 | Taran.Space |
| 27 | Haskell | MayZ (Cardano) | DeFi | 2 High, 1 Medium | Nov 2024 | Independent |

### **Public Security Contests:**
| # | Language | Protocol | Type | Findings | Report | Date |
|---|----------|----------|------|----------|--------|------|
| 01 | Move | Bluefin Perps (Sui) | Decentralized Exchange - Perpetuals | 1 High (Rank: 8/38) | Private ([HackenProof](https://hackenproof.com/hackers/pushkarm029)) | Jul 2025 |
| 02 | Solidity | CrestalNetwork | Web3-native AI agent platform | 2 Medium (Rank: 7/98) | [Sherlock](https://audits.sherlock.xyz/contests/755/report) | Mar 2025 |

### **Triage Work:**
| # | Protocol | Issues Triaged | Date | Firm |
|---|----------|----------------|------|------|
| 01 | Bluefin | 100 | Jun 2026 | Pashov Audit Group |
| 02 | Linea | 93 | Jun 2026 | Pashov Audit Group |
| 03 | Yelay | 74 | Jun 2026 | Pashov Audit Group |

---

### **Open Source**  
- **NautilusTrader**: Ported critical trading systems (Throttler, Risk Engine, Portfolio, Indicators) to Rust for low-latency trading. Built [nautilustrader.io](https://nautilustrader.io) and full [documentation portal](https://nautilustrader.io/docs).

- **ARK Builders**: Developed a file/folder storage system in Rust. Wrote JNI bindings to integrate with Java/Kotlin apps and implemented a custom LRU cache for frequently accessed data.

- **JaegerTracing**: Rebuilt Jaeger as an OpenTelemetry extension during the LFX mentorship. Implemented adaptive sampling for Jaeger V2 to optimize trace filtering for storage backends.

---

### **Commercial Projects**  
- **Leapwallet (TON DeFi)** : Implemented optimized token swap algorithms with multi-path routing for moki aggregator.

- **Stealth Data Firm** : Built a high-performance PostgreSQL proxy server in Rust with semantic query transformation, strict privilege management, and AWS S3 model storage integration.

---

### **Articles**  
- **[Valid Proofs, Broken Protocols: The ZK Bugs Engineers Actually Miss](https://audits.miragesystems.io/blog/valid-proofs-broken-protocols-zk-bugs-engineers-miss)**: Explains how valid ZK proofs can still leak witnesses, prove weaker statements, or authorize the wrong protocol action.
- **[Native Rust on Solana: 7 Security Mistakes That Drain Protocols](https://audits.miragesystems.io/blog/solana-native-rust-security-vulnerabilities)**: Analyzes critical vulnerability patterns in native Solana Rust programs.
- **[The Ability Mistakes That Will Drain Your Sui Move Protocol](https://audits.miragesystems.io/blog/sui-move-ability-security-mistakes)**: Explores critical security pitfalls in Sui Move’s ability system and exploit scenarios.
- **[Navigating the Cross-Chain Landscape: XCMP vs IBC](https://medium.com/@taran-space/navigating-the-cross-chain-landscape-xcmp-vs-ibc-b247de322e20)**: Compares Polkadot's XCMP and Cosmos's IBC cross-chain messaging models, their trust assumptions, and security trade-offs.
- **[XCMP in Polkadot: Security Measures Every Project Should Know](https://medium.com/@taran-space/xcmp-in-polkadot-security-measures-every-project-should-know-5bd928f8053f)** :  Explores cross-chain message security in Polkadot, common vulnerabilities, and best practices for secure XCMP design.

---

### **Contact**: 
- **Email:** [pushkarmishra029@gmail.com](mailto:pushkarmishra029@gmail.com)
- **𝕏:** [@Pushkarm029](https://x.com/Pushkarm029)
- **Telegram:** [@Pushkarm029](https://t.me/Pushkarm029)
- **LinkedIn:** [@Pushkarm029](https://linkedin.com/in/pushkarm029)
