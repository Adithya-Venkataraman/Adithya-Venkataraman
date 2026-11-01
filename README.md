# Adithya Venkataraman

Software engineer focused on Python backend systems, distributed architecture, and applied AI engineering.

I build event-driven pipelines, RAG systems, and production-oriented ML applications. My work tends to involve getting reliability and correctness out of systems that have a lot of moving parts — async workers, concurrent caching layers, multi-agent orchestration, retrieval pipelines with actual guardrails.

Currently interning at [Agent Labs (Time Rich)](https://timerich.ai/), working on backend automation with Cloudflare Workers and Supabase. Co-authoring a research paper on citation-bound RAG for cross-jurisdictional privacy compliance.

---

## Stack

**Backend:** Python · FastAPI · Flask · PostgreSQL · Redis · Celery · Docker  
**Distributed Systems:** Apache Kafka · TimescaleDB · pgvector · Async Processing  
**AI / ML:** LangChain · LangGraph · FAISS · Sentence Transformers · PyTorch · XGBoost · MLflow · SHAP · Optuna · Ollama  
**Other:** Git · SQL · C · Java · Linux

---

## Projects

### [DOCUMIND](https://github.com/Adithya-Venkataramn/ai-knowledge-worker) — Multi-Agent AI Knowledge Platform
Multi-agent system built with LangGraph. Specialized agents handle RAG, code execution, web search, and evaluation. Hybrid BM25 + semantic search with pgvector and Cohere reranking. Async document ingestion via Celery and Redis.  
`Python` `LangGraph` `FastAPI` `PostgreSQL` `pgvector` `Redis` `Celery` `Docker`

### [DRIFT](https://github.com/Adithya-Venkataraman/algo-trading-platform) — Algorithmic Trading Platform
Event-driven trading pipeline using Kafka and TimescaleDB. XGBoost + LSTM classifier with 14 engineered indicators, Optuna tuning, MLflow tracking. Backtested 5 years of BTC-USD data: **21.81% return · 51.9% win rate · 9.54% max drawdown**. SHAP explainability and Evidently AI drift detection included.  
`Python` `Kafka` `XGBoost` `PyTorch` `MLflow` `TimescaleDB` `Docker`

### [LEXAI](https://github.com/Sakaido4u/legal-ai-bot) — Legal AI Compliance Bot
Jurisdiction-aware RAG pipeline over 1,600+ regulatory chunks (GDPR · DPDP · CCPA). FAISS retrieval, MMR reranking, per-sentence citation validation, re-prompting guardrails, and cross-jurisdiction risk scoring via Ollama.  
`Python` `FastAPI` `FAISS` `Sentence Transformers` `PostgreSQL` `Ollama`

### [GATEWAY](https://github.com/Adithya-Venkataraman/rate-limiter-gateway) — Rate-Limiting API Gateway
Async API gateway with round-robin load balancing and Redis-backed sliding-window and token-bucket rate limiting. Atomic Lua scripts prevent race conditions under concurrent load.  
`Python` `FastAPI` `Redis` `Docker`

---

## Research

**Citation-Bound RAG for Cross-Jurisdictional Privacy Compliance** *(Co-author)*  
Evaluated retrieval faithfulness, citation accuracy, and system failure modes across GDPR, India's DPDP Act, and CCPA. Benchmarked retrieval methods and ablations.  
[Link when available]

---

## Experience

**Software Engineering Intern — Agent Labs (Time Rich)** *(September 2026 – Present)*  
Backend automation using ThriveCart webhooks, Cloudflare Workers, and Supabase/PostgreSQL. Secure RPC design with SECURITY DEFINER, RLS-preserving grants, and PGlite-based migration testing.

---

## Education

B.E. Computer Science Engineering — JSS Academy of Technical Education, Bengaluru  
Expected 2027 · CGPA: 8.68

---

## Contact

[LinkedIn](https://linkedin.com/in/adithya989) · [Email](mailto:adithyav0505@email.com)
