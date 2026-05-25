<div align="center">

# Sumit Kumar 🚀 — AI/ML • RAG • Agentic Systems

### Machine Learning Engineer IV @ Avalara · 8+ years building production AI

*Healthcare → Pharma analytics → Global trade compliance*

Turning research patterns into production systems with the controls that separate a demo from a deployment — auth, audit logs, regression gates, rollback, honest evals.

<br>

![Role](https://img.shields.io/badge/MLE_IV-Avalara-0d47a1?style=for-the-badge)
![Experience](https://img.shields.io/badge/EXPERIENCE-8%2B_YEARS-success?style=for-the-badge)
![Education](https://img.shields.io/badge/M.Sc.-IIT_KHARAGPUR-orange?style=for-the-badge)
![Location](https://img.shields.io/badge/BENGALURU-INDIA-lightgrey?style=for-the-badge)

</div>

---

## 👋 About me

I design and ship **production AI systems** at scale.

- 🏢 **Currently** — Machine Learning Engineer IV at Avalara, building agentic Harmonized System (HS) code classification with LangGraph + RAG + Qdrant for global trade compliance
- 💼 **Previously** — Oracle, Adani AI Labs, and ZS Associates, across healthcare analytics, pharma research, and enterprise AI
- 🎓 **Education** — M.Sc. Mathematics and Computing, IIT Kharagpur

---

<div align="center">

### 🔥 Featured

# 📘 [ai-ml-portfolio](https://github.com/sumit-mle/ai-ml-portfolio)

**Ten production-grade AI projects, end-to-end, every one with verified evals**

A single repo with the frameworks that ship in 2026 — anchored to real enterprise use cases and measured against committed JSON results.

![Projects](https://img.shields.io/badge/PROJECTS-10-blue?style=for-the-badge)
![Tests](https://img.shields.io/badge/TESTS-60%2B-success?style=for-the-badge)
![Evals](https://img.shields.io/badge/VERIFIED_EVALS-10-orange?style=for-the-badge)
![Python](https://img.shields.io/badge/PYTHON-3.13_%7C_3.14-yellow?style=for-the-badge&logo=python&logoColor=white)

</div>

| # | Project | Headline result |
|---|---------|-----------------|
| 01 | **Contract Review RAG** (CUAD) | 8 retrieval techniques side-by-side; LangChain 1.00 vs LlamaIndex 0.08 verbatim quoting |
| 02 | **Pharma Agentic RAG with Reflection** | 9/9 questions, 1.00 citation recall, 1.00 honest-abstain |
| 03 | **GraphRAG over real SEC EDGAR** (Neo4j) | 612 typed relations from 12 filings; **graph wins 1.00 vs vector 0.00** on multi-hop |
| 04 | **Sales Research Crew** (CrewAI) | 1.00 facts accuracy on real Microsoft / Costco / Pfizer / NextEra / JPMorgan briefings |
| 05 | **Legacy Modernization Agent** | 8/8 tests pass before AND after; libcst transformer + bounded repair loop |
| 06 | **Enterprise MCP Server** | 13/13 security tests; auth + scopes + sqlglot SQL gate + PII + JSONL audit |
| 07 | **Voice Helpdesk Agent** | OpenAI Realtime speech-to-speech with server-side identity gate; 5/5 scenarios |
| 08 | **Vendor Compliance Browser Agent** | 3/3 vendors including MFA + missing-doc detection at 3.7s avg |
| 09 | **RAG Regression Harness** | pytest 3/3 green; baseline + tolerance gating, Kendall-tau drift detection |
| 10 | **Marketing Analytics NL→SQL Agent** | LangGraph + DuckDB; 5/5 BIRD-style execution-correctness |

<div align="center">

**~7,500 lines of Python · 60+ tests · 10 working evals**

*Every result above is a JSON file in the repo — no "trust me" numbers.*

</div>

---

## 📊 Production track record

Highlights from work that's already in production at Fortune-500 scale:

| Where | What | Impact |
|-------|------|--------|
| **Avalara** | Agentic HS code classification with LangGraph + RAG | Production hybrid DL + LLM platform serving compliance APIs |
| **Avalara** | DistilBERT fine-tuning on AWS SageMaker, NVIDIA Triton inference | Low-latency GPU inference at scale |
| **Avalara** | LLM-as-a-judge eval pipelines + automated regression testing | Caught hallucination + reasoning regressions before prod |
| **Oracle Cerner** | NLP on 500K+ service tickets (BERT + clustering) | **50% manual workload reduction · 30% faster resolution** |
| **Oracle Cerner** | Patient readmission prediction (XGBoost on 50K+ EMR records) | Production hospital ops optimization |
| **Oracle Cerner** | Anomaly detection on hospital ops (Isolation Forest) | Live abnormal-pattern detection |
| **ZS Associates** | NASH disease detection (XGBoost / RF / LR) | **85% AUC** in healthcare analytics |
| **ZS Associates** | Poisson-Gamma clinical trial enrollment forecasting | Real-time recruitment monitoring |

The portfolio repo above shows the *same patterns* — agentic RAG, eval harnesses, parser-level safety gates, drift detection — applied as standalone projects you can actually run and inspect.

---

## 🛠 What I work with

| Layer | Tools |
|-------|-------|
| **Agents** | LangGraph · CrewAI · browser-use · OpenAI Realtime · OpenAI Agents SDK |
| **RAG** | LangChain · LlamaIndex · Qdrant · FAISS · Neo4j (native vector + Cypher k-hop) · sqlglot |
| **MCP** | FastMCP 3.x · stdio + streamable-HTTP transports |
| **Voice** | OpenAI Realtime (`gpt-realtime`) · Web Audio API · FastAPI WebSockets |
| **Browser** | Playwright (deterministic) · browser-use (autonomous) |
| **Transformers / DL** | HuggingFace Transformers · DistilBERT · BERT · PyTorch · TensorFlow · NVIDIA Triton |
| **Cloud / Infra** | AWS · SageMaker · Docker · CI/CD |
| **Eval** | LLM-as-a-judge · BIRD-style execution correctness · Kendall-tau drift · pytest CI gates |
| **Data / DB** | DuckDB · Neo4j 5 + APOC · Qdrant · SQLite · Postgres · Snowflake · Spark |
| **Languages** | Python · SQL · TypeScript · R · C |

---

## 📌 What you'll find in my repos

Three things I think hard about and try to get right in every project:

1. **Production controls early.** Token auth, scope-based authorization, parser-level SQL gates, PII tag-based masking, append-only JSONL audit logs, bounded repair loops with `give_up` states. These are the things every demo skips and every enterprise needs.
2. **Honest evaluation.** Each project has a `results/` folder with the actual JSON output of its eval. Side-by-side framework comparisons with the same questions. Findings written up — including the embarrassing ones (e.g. LlamaIndex paraphrasing where we needed verbatim).
3. **Real data over toy data.** CUAD legal contracts. Real SEC EDGAR filings. Live PubMed via NCBI E-utilities. NYC TLC taxi traffic. Each project is anchored to a use case someone would actually pay to have solved.

---

<div align="center">

## 📫 Connect

📧 **sumit.kgpiit@gmail.com** &nbsp;·&nbsp; 📍 Bengaluru, India  
🌐 [**ai-ml-portfolio**](https://github.com/sumit-mle/ai-ml-portfolio)

<!-- Optional: paste your LinkedIn URL on the next line, or delete -->
<!-- 💼 https://www.linkedin.com/in/your-handle/ -->

*Open an issue or DM if anything in here would be useful for your team — happy to walk through any of it.*

</div>
