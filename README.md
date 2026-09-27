<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=180&section=header&text=Sairaj%20Narayankar&fontSize=42&fontColor=fff&animation=twinkling&fontAlignY=32&desc=Backend%20AI%20Engineer%20%7C%20LLM%20Infrastructure%20%7C%20RAG%20Systems&descAlignY=55&descSize=16"/>

<br/>

[![Typing SVG](https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=22&pause=1000&color=6EE7B7&center=true&vCenter=true&width=600&lines=Architecting+Resilient+AI+Backends+%E2%9A%A1;LLM+Metering+%7C+RAG+Pipelines+%7C+Multi-Agent+Loops;Backend+AI+Intern+%40+Flyrank+AI+%F0%9F%9A%80;Mumbai%2C+India+%F0%9F%87%AE%F0%9F%87%B3)](https://git.io/typing-svg)

<br/>

<a href="https://www.linkedin.com/in/sairajnarayankar" target="_blank">
  <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"/>
</a>
<a href="https://github.com/SairajNarayankar" target="_blank">
  <img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white"/>
</a>
<img src="https://img.shields.io/badge/Location-Mumbai%2C%20IN-FF6B6B?style=for-the-badge&logo=google-maps&logoColor=white"/>
<img src="https://img.shields.io/badge/System--Status-200%20OK%20--%20Open%20To%20Work-00C851?style=for-the-badge&logo=checkmarx&logoColor=white"/>

<br/><br/>

</div>

---

## ⚡ System Manifest

```python
from typing import List, Dict, Any
from pydantic import BaseModel, Field

class BackendAIEngineer(BaseModel):
    name: str = "Sairaj Narayankar"
    current_role: str = "Backend AI Engineering Intern @ Flyrank AI"
    location: str = "Mumbai, India [19.0760° N, 72.8777° E]"
    education: str = "B.Sc. Information Technology — University of Mumbai"
    
    primary_runtime: Dict[str, Any] = {
        "paradigm": "Async / Event-Driven / Fault-Tolerant",
        "focus": ["LLM Infrastructure", "Usage Metering Engines", "RAG Pipelines", "Agent Orchestration"],
        "code_guarantees": ["Idempotency", "Atomic Transactions", "Zero Floating-Point Money Drift"]
    }
    
    active_stack: List[str] = [
        "FastAPI", "Python 3.11+", "Async PostgreSQL", "SQLAlchemy",
        "ChromaDB", "Docker Compose", "LangChain/LangGraph", "Stripe CLI"
    ]
    
    async def process_task(self, query: str) -> str:
        """Ingests requirements, optimizes token efficiency, and ships resilient APIs."""
        return f"Executing {query} with p99 low-latency and deterministic fallbacks."
```

---

## 🏗️ Architectural Topology

Here is how I design production backend systems for AI-driven workloads:

```mermaid
graph TD
    Client[Client / Multi-Tenant Apps] -->|HTTP POST / JSON| Gateway[FastAPI Gateway & Auth]
    
    subgraph Core Engine Tier
        Gateway -->|Idempotency Check| Metering[Usage & Billing Engine]
        Gateway -->|Vector Query| RAG[Semantic Retrieval Engine]
    end

    subgraph Data & Persistence Tier
        Metering -->|Quota Rules & Tokens| Cache[(Redis / Memory Quota)]
        Metering -->|Atomic Usage Audit| DB[(PostgreSQL + Docker)]
        RAG -->|Dense Embeddings| Vector[(ChromaDB Vector Store)]
    end

    subgraph External System Tier
        Metering -->|Signed Webhooks| Stripe[Stripe API / Billing]
        RAG -->|Grounded Prompting| LLM[LLM Provider / OpenAI / Anthropic]
    end
```

---

## ⚙️ Core System Components

<table>
<tr>
<td width="50%">

### 🤖 LLM & Vector Compute
- **RAG Architecture** — Hybrid dense retrieval (ChromaDB) with TF-IDF/lexical failovers & semantic reranking.
- **Agent Orchestration** — Tool-calling loops, stateful graphs, and Model Context Protocol (MCP) integrations.
- **Metering & Quota Enforcers** — Real-time token tracking, input/output/reasoning pricing, and rate limiting.

</td>
<td width="50%">

### 🛡️ Resilient Backend Engineering
- **Async API Design** — High-concurrency FastAPI services with Pydantic validation & OpenAPI specs.
- **Persistence & Migration** — PostgreSQL with async SQLAlchemy ORM and Alembic schema versioning.
- **Payment & Webhook Security** — Stripe Checkout flows, raw-body HMAC signature validation, and replay protection.

</td>
</tr>
</table>

---

## 🛠️ Stack Telemetry

### 01. Artificial Intelligence & Vector Engines
![Python](https://img.shields.io/badge/Python_3.11+-3776AB?style=for-the-badge&logo=python&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)
![OpenAI API](https://img.shields.io/badge/OpenAI_API-412991?style=for-the-badge&logo=openai&logoColor=white)
![ChromaDB](https://img.shields.io/badge/ChromaDB-FF6B6B?style=for-the-badge&logoColor=white)
![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)

### 02. Async API Tier & Microservices
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white)
![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy_ORM-D71F00?style=for-the-badge&logo=python&logoColor=white)
![Stripe](https://img.shields.io/badge/Stripe_API-635BFF?style=for-the-badge&logo=stripe&logoColor=white)

### 03. Storage, Containers & Infrastructure
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=for-the-badge&logo=supabase&logoColor=white)
![Docker](https://img.shields.io/badge/Docker_Compose-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Google Cloud](https://img.shields.io/badge/Google_Cloud-4285F4?style=for-the-badge&logo=googlecloud&logoColor=white)
![Microsoft Azure](https://img.shields.io/badge/Azure-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white)

---

## 📦 Featured Production Systems

<table>
<tr>
<td width="50%">

### ⚡ LLM Usage Metering & Billing Engine
**FlyRank AI Internship Capstone — Backend Track**

Production-grade metering middleware and subscription billing service for SaaS AI platforms.

```yaml
guarantees:
  idempotency: Exactly-once usage event recording via unique keys
  pricing_model: Independent token tiers (Cached input / Output / Reasoning)
  quota_protection: HTTP 429 (Limit Exceeded) & HTTP 402 (Payment Required)
  currency_precision: Integer-cent integer math (Zero floating-point drift)
  security: Stripe HMAC signature verification & webhook replay defense
```

**Stack:** `FastAPI` `PostgreSQL` `SQLAlchemy` `Alembic` `Stripe CLI` `Docker` `pytest`

[![Repository](https://img.shields.io/badge/View_Source_Code-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/SairajNarayankar/LLM-Usage-Metering-billing-Service)

</td>
<td width="50%">

### 🔍 Cricket AI Predictive Engine & Hybrid RAG
**End-to-End Predictive & Semantic Retrieval System**

Complete pipeline integrating automated match scraping, ML inference, and dual-engine RAG search.

```yaml
metrics:
  classifier: Random Forest (Match outcome prediction)
  accuracy: 80.00%
  f1_score: 0.8571
guarantees:
  data_integrity: Strict chronological feature engineering (Zero data leakage)
  retrieval_failover: ChromaDB dense vector search with TF-IDF fallback
```

**Stack:** `Python` `scikit-learn` `ChromaDB` `SentenceTransformers` `BeautifulSoup` `pandas`

</td>
</tr>
</table>

---

## 🎓 Verified Credentials

<div align="center">

| System Certification | Issuing Organization | Year |
|----------------------|----------------------|------|
| 🏅 **Generative AI Engineering Professional Certificate** | IBM | 2026 |
| ☁️ **Microsoft Azure Fundamentals (AZ-900)** | Microsoft | 2025 |
| 🌏 **Google Cloud Gen AI Academy — APAC Cohort 1** | Google Cloud | 2026 |

</div>

---

## 📊 System Metrics & Activity

<div align="center">

<img height="180em" src="https://github-readme-stats.vercel.app/api?username=SairajNarayankar&show_icons=true&theme=tokyonight&include_all_commits=true&count_private=true&hide_border=true&bg_color=0d1117"/>
<img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=SairajNarayankar&layout=compact&langs_count=8&theme=tokyonight&hide_border=true&bg_color=0d1117"/>

<br/>

<img src="https://github-readme-streak-stats.herokuapp.com/?user=SairajNarayankar&theme=tokyonight&hide_border=true&background=0d1117" alt="GitHub Streak"/>

</div>

---

## 🔄 Active Worker Threads

```syslog
[RUNNING]  Implementing Model Context Protocol (MCP) server & tool integrations
[RUNNING]  Evaluating LangGraph multi-agent orchestration and loop persistence
[QUEUED]   Building automated LLM observability & token tracing pipelines
[QUEUED]   Refining case-study engineering write-ups for production AI systems
```

---

## 🤝 Let's Connect

<div align="center">

Interested in **AI Infrastructure, RAG Systems, Multi-Agent Architectures**, or **High-Concurrency Backends**? Let's connect and build something resilient.

<br/>

[![LinkedIn](https://img.shields.io/badge/Connect_on_LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/sairajnarayankar)
[![GitHub](https://img.shields.io/badge/Follow_on_GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/SairajNarayankar)

<br/>

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=100&section=footer"/>

</div>
