<!-- <img align="right" src="https://avatars.githubusercontent.com/u/258988699?v=4" width="120" alt="Sunny Sharma's GitHub profile photo" /> -->

# Sunny Sharma

### Applied GenAI & Data Engineer

I build AI applications on a foundation of **four years in production data engineering**. My work connects Python, SQL, reliable data pipelines, retrieval, and tool-using agents to practical business workflows.

Currently developing independent GenAI projects and pursuing **Applied AI, GenAI Engineering, and AI Data Engineering roles in Delhi NCR**.

[LinkedIn](https://www.linkedin.com/in/sunny-sharma2022/) · [Email](mailto:sunny_sharma2022@outlook.com) · [Explore my repositories](https://github.com/sunshine-engineer?tab=repositories)

<br clear="right" />

## Start here

These are independent portfolio projects. My commercial production experience is in data engineering; project links below show the implementation, tests, and current scope of my AI work.

| Project | What it does | Engineering evidence |
| --- | --- | --- |
| **[Document QA & RAG](https://github.com/sunshine-engineer/Intelligent-Document-QA-Chatbot)** | Answers questions over PDFs with file/page citations using LangChain, FAISS, Ollama embeddings, and Groq. | Index-integrity manifests, modular query services, Docker Compose, automated tests, and a versioned offline evaluation fixture. [Quality gates](https://github.com/sunshine-engineer/Intelligent-Document-QA-Chatbot/blob/main/docs/quality-gates.md) |
| **[AutoDocsGenAI](https://github.com/sunshine-engineer/AutoDocsGenAI)** | Builds a documentation ingestion and retrieval pipeline from official sources using Python, PostgreSQL, and pgvector. | Deterministic chunking, persisted lineage, idempotent imports, migrations, retrieval evaluation, and CI. Generation and review remain in development. [Architecture](https://github.com/sunshine-engineer/AutoDocsGenAI/blob/main/docs/architecture.md) |
| **[Agentic AI Demo](https://github.com/sunshine-engineer/AgenticAI_Demo)** | Demonstrates bounded tool use, supervisor/specialist workflows, LangGraph checkpoints, and MCP in a support-operations scenario. | Explicit approval policy, validation, loop limits, traces, and offline tests. Uses dummy data and in-memory state. [Code and tests](https://github.com/sunshine-engineer/AgenticAI_Demo) |
| **[AI SQL Assistant](https://github.com/sunshine-engineer/ai-sql-assistant)** | Provides a natural-language interface to SQLite, MySQL, and PostgreSQL through LangChain, Groq, and SQLAlchemy. | Schema discovery, input checks, read-only SQLite access, and response-time tracking. Application-level SQL checks are prototype safeguards, not a security boundary. [Screenshots and design](https://github.com/sunshine-engineer/ai-sql-assistant#readme) |

**For a quick review:** start with Document QA for applied RAG, AutoDocsGenAI for data architecture, or Agentic AI Demo for orchestration and tool policies.

## Production foundation

At Everlytics, I progressed from Data Engineering Intern to Data Engineer and Senior Data Engineer, working on warehouse migrations, ETL delivery, and production support.

- Contributed to a Teradata-to-SingleStore migration spanning **100+ TB**, and migrated or optimized **100+ Informatica workflows**.
- Coordinated Airflow workflows across batch, CDC, and streaming ingestion, with validation, dependencies, monitoring, and release handover.
- Owned a scheduled file-to-SingleStore pipeline end to end: archive validation, landing/staging loads, SCD Type 2 dimensions, fact loading, rejected-record handling, and task-level email alerts.
- Investigated failed loads and data discrepancies, tuned SQL and workflows, and communicated delivery risks and recovery actions to stakeholders.

That experience shapes how I build AI systems: inspect failures, preserve data lineage, make workflows testable, and document operational limits.

## Technical toolkit

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat&logo=langchain&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Airflow](https://img.shields.io/badge/Airflow-017CEE?style=flat&logo=apacheairflow&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)

| Area | Tools and practices |
| --- | --- |
| Applied AI | RAG, embeddings, FAISS, pgvector, prompt/context design, tool calling, LangChain, LangGraph, Groq, Ollama |
| Data systems | Python, SQL, Airflow, Informatica, PostgreSQL, SingleStore, Teradata, ETL, CDC, dimensional loading |
| Quality and delivery | Pytest, GitHub Actions, Docker, type checking, retrieval evaluation, logging, LangSmith, root-cause analysis |

## What I am working toward

- Better retrieval and answer-quality evaluation on representative documents.
- Clear API boundaries and reproducible deployment for portfolio AI applications.
- Reliable agent execution with explicit permissions, bounded state, and measurable failure handling.

## Live project signals

[![RAG quality workflow](https://img.shields.io/github/actions/workflow/status/sunshine-engineer/Intelligent-Document-QA-Chatbot/quality.yml?branch=main&label=RAG%20quality)](https://github.com/sunshine-engineer/Intelligent-Document-QA-Chatbot/actions/workflows/quality.yml)
[![AutoDocs CI](https://img.shields.io/github/actions/workflow/status/sunshine-engineer/AutoDocsGenAI/ci.yml?branch=main&label=AutoDocs%20CI)](https://github.com/sunshine-engineer/AutoDocsGenAI/actions/workflows/ci.yml)
[![Latest RAG commit](https://img.shields.io/github/last-commit/sunshine-engineer/Intelligent-Document-QA-Chatbot?label=RAG%20updated)](https://github.com/sunshine-engineer/Intelligent-Document-QA-Chatbot/commits/main/)

These badges reflect repository activity and workflow status. The project documentation explains what each check covers.

## Let's connect

Interested in engineers who can connect enterprise data experience with applied AI? I would welcome a conversation about your team's work.

**[Connect on LinkedIn](https://www.linkedin.com/in/sunny-sharma2022/)** or **[email me](mailto:sunny_sharma2022@outlook.com)** for my latest resume and project walkthroughs.
