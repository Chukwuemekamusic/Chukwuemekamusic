# Hi, I'm Joseph 👋

I'm a **Python backend engineer** and **blockchain developer** based in Aberdeen, UK — with an MSc (Distinction) in Information Technology and a background in Electrical Engineering.

I build production-grade backend systems and smart contract protocols. My focus is on async architectures, distributed processing, and DeFi — writing code that's reliable under load, not just working in development.

---

## 🛠 What I Work With

**Python & Backend**
`FastAPI` `Celery` `SQLAlchemy (async)` `PostgreSQL` `Redis` `Docker` `Pydantic` `pytest`

**Blockchain**
`Solidity` `Foundry` `DeFi Protocols` `EIP-2535 (Diamond)` `UUPS` `Account Abstraction` `Viem` `Ethers.js`

**Frontend & Full-Stack**
`React` `Next.js` `TypeScript` `Node.js` `Django`

**Data & AI**
`pandas` `NumPy` `Matplotlib` `Scikit-learn` `LangChain`

---

## 🚀 Selected Projects

### [ReportFlow — Async Report Generation API](https://github.com/Chukwuemekamusic/reportflow)
> Python · FastAPI · Celery · Redis · PostgreSQL · MinIO · WebSocket · Docker

API-first backend service that decouples heavy report generation from the HTTP request lifecycle using an async Celery job queue. Multi-tenant, fully containerised, production-architecture focus.

- Three-queue Celery pipeline (high / default / low priority) with custom base task class and granular progress tracking
- Real-time WebSocket progress streaming via Redis pub/sub
- Three report types: Sales Summary PDF, CSV Export, multi-section PDF with Matplotlib charts
- Retry/backoff, dead letter queue, idempotency keys, and rate limiting

---

### [Isolated Lending Market Protocol](https://github.com/Chukwuemekamusic/ism_protocol)
> Solidity · Foundry · TypeScript · Next.js · Base L2

Full-stack DeFi lending protocol with isolated markets to eliminate cross-asset contagion risk.

- MEV-resistant Dutch auction liquidation + dual-source oracle (Chainlink + Uniswap V3 TWAP)
- Kinked interest rate model with WAD math (1e18 precision) and utilization-based dynamic rates
- ~95% gas reduction per market deployment via EIP-1167 minimal proxy pattern
- 58+ unit, integration, invariant, and fork tests in Foundry
- TypeScript liquidation bot with real-time position monitoring; live on Base Sepolia

---

### [MatchDay Bet Bot — Towns Protocol](https://github.com/Chukwuemekamusic/matchday-bet-bot)
> Solidity (UUPS) · Foundry · TypeScript · Towns SDK

On-chain parimutuel betting bot deployed on Base, integrated with the Towns Protocol.

- Automated match resolution with real-time sync between off-chain APIs and on-chain state
- Verification and reconciliation logic for failed or delayed transactions

---

### [Decentralised Crowdfunding Platform](https://my-crowdfunding.vercel.app)
> Next.js · TypeScript · Solidity · IPFS · MetaMask

Full-stack dApp for creating and managing crowdfunding campaigns with gas-optimized contracts, IPFS image storage (Pinata), and a responsive frontend with real-time blockchain interaction.

---

## 📫 Get in Touch

- Email: [joseph.emeka.dev@gmail.com](mailto:joseph.emeka.dev@gmail.com)
- LinkedIn: [joseph-anyaegbunam](https://www.linkedin.com/in/joseph-anyaegbunam-b1a430253/)
- Portfolio: [joseph-anyaegbunam.dev](https://joseph-anyaegbunam.dev)
