<!--
RAW MARKDOWN — optimized README based on your Transfero responsibilities + your personal ML project (4+ years).
Paste directly into README.md.
-->

<h1 align="center">👋 Hi, I'm <strong>Lukas Rozado</strong></h1>
<p align="center">
  <strong>Data Analyst</strong> — Data Engineering for financial services: resilient ETL pipelines, multi-chain ingestion, and analytical modeling.  
  Currently @ Transfero — building end-to-end data solutions (ingestion → transformation → DW → reporting).
</p>

<p align="center">
  <img alt="stack" src="https://img.shields.io/badge/stack-Python%20%7C%20SQL%20%7C%20Azure%20Functions%20%7C%20PostgreSQL-blue" />
  <img alt="contact" src="https://img.shields.io/badge/contact-lukasrozado%40gmail.com-blue" />
</p>

---

## 🚀 TL;DR
I design and operate **resilient ETL/ELT pipelines** for financial data, focused on **high availability, idempotency, and performance**.  
I integrate multiple sources (including **blockchains**) using Azure Functions and transform Data Lake JSON into **Data Warehouse models** optimized for financial reporting and reconciliation.

---

## 🔎 What I do at Transfero
### Resilient ETL architecture
- Stream-based ingestion using **Python generators**, enabling low-memory processing of unlimited data streams.  
- **Idempotent** loading with UPSERT logic and composite keys.  
- **Retry**, error isolation, and checkpoint integrity achieving **>99.9% pipeline reliability**.  
- Parameterized ingestion framework used across multiple projects/clients.

### Multi-chain ingestion & serverless architecture
- Data ingestion from **10+ blockchain networks** through Azure Functions.  
- **Checkpointing** with Azure Blob Storage for safe continuation.  
- Secure authentication via **Managed Identity** and Azure Key Vault (auditability + compliance).

### Data Lake → Data Warehouse modeling
- Normalization of semi-structured JSON into optimized **PostgreSQL DW** tables.  
- High-volume ingestion using `COPY`, handling **millions of rows efficiently**.  
- Semantic layer creation for financial dashboards, reconciliation processes, and analytics.

### Ownership & impact
- Increased reliability and consistency of Transfero’s ingestion ecosystem.  
- Improved FinOps/compliance with structured logging, checkpoints, and secure identity.  
- Delivering clean, trusted datasets for business teams and real-time reporting.

---

## 🛠 Core Tech Stack
**Languages & Libraries:** Python,SQL, Pandas, Psycopg2  
**Data & Storage:** PostgreSQL, Azure Blob Storage  
**Cloud:** Azure Functions, Key Vault, Managed Identity  
**DevOps:** Git, GitHub Actions CI, structured logging, monitoring basics

---
