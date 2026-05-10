<h1 align="center">👋 Hi, I'm <strong>Lukas Rozado</strong></h1>
<p align="center">
  <strong>Data Engineer | Cloud Architecture & ML Pipelines</strong> — I build institutional-grade data pipelines, canonical ledgers, and resilient analytical systems.
</p>

<p align="center">
  <img alt="stack" src="https://img.shields.io/badge/Python-3.10+-blue" />
  <img alt="stack" src="https://img.shields.io/badge/SQL-PostgreSQL-lightgrey" />
  <img alt="stack" src="https://img.shields.io/badge/Cloud-Azure-blue" />
  <img alt="stack" src="https://img.shields.io/badge/Architecture-Event%20Driven-green" />
</p>

---

## About Me
I specialize in **Data Engineering and Systems Architecture**, transforming raw, unstructured, and fragmented data into highly reliable, canonical Data Warehouses. My focus is on **performance-first engineering**: solving aggressive API rate limits, ensuring I/O database optimization, and building secure, cloud-native ingestion pipelines for the financial sector.

I don't just move data from A to B; I design systems that guarantee absolute integrity, idempotency, and strict data governance.

---

## Core Architectural Domains
Over the past years, I have architected and deployed complex data systems across multiple domains:

### Institutional Financial Pipelines
- **Enterprise Crypto Data Lakes:** End-to-end architecture for ingestion of transactional data to multiple accounts for crypto exchange. I implemented an asynchronous extraction engine with an intelligent Rate Limiter that monitors API headers to prevent bans. The system uses Azure Key Vault for secret management and a high-performance PostgreSQL loader via COPY commands and temporary tables, ensuring idempotency and integrity at scale.
- **Multi-Chain Ledger Integrators:** Resilient pipeline for consolidating transactional data across multiples blockchains and contracts (EVM and Solana). I replaced third-party indexers with raw RPC extraction using 'Reverse Check' algorithms, optimizing block scanning. The core differentiator is the Auto-Reconciliation engine, which continuously audits the PostgreSQL database against network nodes, ensuring strict uniqueness and 100% integrity in balances
- **Custody & BaaS Integration:** Development of a programmatic integration pipeline to centralize multi-bank financial settlement data (Banking-as-a-Service). The architecture was designed to ensure maximum security in communication between isolated systems. It uses corporate authentication via Azure Active Directory and tokens to orchestrate the capture of thousands of payments, converting them into immutable records in the Data Warehouse.
- **Institutional Digital Asset Custody Integrator:** Distributed integration architecture for managing institutional custody of crypto assets. I implemented an abstraction layer to orchestrate global master APIs, ensuring the segregated capture of transactional data by operating region. The system focuses on high security in secrets traffic and schema standardization to comply with international FinOps audits.

### E-sports Quant Trading & ML Engine (5+ years)
A massive end-to-end personal project focused on predictive modeling and quantitative analysis.
- **Automated Data Engineering:** Daily web scraping, feature engineering (42+ variables), and real-time data pipelines.
- **Machine Learning:** Statistical models, ensemble ML (Scikit-Learn), and continuous experiment cycles.
- **Production:** Full deployment lifecycle including backtesting, signal logging, and metric monitoring.

> *This project reflects my technical depth, persistence, and ability to architect, deploy, and maintain a complex algorithmic system long-term.*

---

## Technical Stack & Engineering Practices

### **Languages & Frameworks**
- **Python:** Advanced Asyncio, ThreadPoolExecutor, Pandas, SQLAlchemy, Polars.
- **SQL (PostgreSQL):** High-performance bulk loading (`COPY` commands, `io.StringIO`), temporary tables, indexing, and query optimization.
- **Cloud (Microsoft Azure):** Azure Functions, Blob Storage (Checkpointing), Azure Key Vault (Dynamic Auth), Managed Identities.
- **ML & Analytics:** Scikit-learn, Metabase, PowerBI.

### **Engineering Standards**
- **Idempotency & Resilience:** Upsert patterns, robust retry/backoff strategies.
- **API Security:** Zero-hardcoded credentials, secure token injection, header monitoring.
- **Observability:** Custom structured logging and pipeline state management.
- **Clean Architecture:** Modular project structures and OOP design.

---

<p align="center">
  <i>"I enjoy solving real problems with pragmatic, clean, and reliable data solutions."</i><br>
  🔗 <strong>Portfolio:</strong> <a href="https://lukasrozado.github.io/">lukasrozado.github.io</a> | 💼 <strong>LinkedIn:</strong> <a href="https://www.linkedin.com/in/lukasrozado">in/lukasrozado</a>
</p>
