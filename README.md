<div align="center">

# Hi there, I'm Jay 👋
### AI & Backend Engineer • Distributed Systems Enthusiast

<p align="center">
  <a href="https://github.com/Jayouss">
    <img src="https://komarev.com/ghpvc/?username=Jayouss&label=Profile%20Views&color=0e75b6&style=flat" alt="Visitor Count" />
  </a>
</p>

<p align="center">
  Passionate about architecting high-performance backend systems, decoupling microservices, and implementing cutting-edge <b>Agentic AI & Retrieval-Augmented Generation (RAG)</b> pipelines.
</p>

---

</div>

### 🚀 About Me

* 🔭 Building production-ready **AI & Backend** platforms with **Python** & **TypeScript**.
* 🧠 Specialized in **Agentic Workflows**, **Hybrid Vector Search (pgvector)**, and **Sub-Millisecond Semantic Caching**.
* ⚙️ Strong focus on clean architecture, API gateway security, rate limiting, and automated CI/CD pipelines.
* 📍 Based in Indonesia 🇮🇩

---

### 🛠️ Tech Stack & Skills

<p align="left">
  <!-- Languages -->
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" />
  <img src="https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white" />
  <br/>
  <!-- Backend & AI -->
  <img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white" />
  <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white" />
  <img src="https://img.shields.io/badge/Express-000000?style=for-the-badge&logo=express&logoColor=white" />
  <img src="https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=chainlink&logoColor=white" />
  <br/>
  <!-- Databases & Caching -->
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/pgvector-336791?style=for-the-badge&logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white" />
  <br/>
  <!-- DevOps & Cloud -->
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" />
  <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=github-actions&logoColor=white" />
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" />
  <img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black" />
</p>

---

### 🌟 Featured Flagship Projects

#### 1. 🧠 [DocuGraph AI — Enterprise Decoupled Agentic RAG Platform](https://github.com/Jayouss/docugraph-ai)
> A production-ready, decoupled AI microservices platform combining **TypeScript (Node.js)** API Gateway with **Python (FastAPI)** AI Core.

* ⚡ **Decoupled Architecture**: Node.js handles auth, token-bucket rate limiting, and WebSocket streaming; Python executes vector indexing and agent reasoning.
* 🔍 **Hybrid Search**: Blends dense vector cosine similarity (pgvector) with sparse BM25 keyword matching and cross-encoder reranking.
* 💸 **Sub-Millisecond Semantic Cache**: Intercepts semantically identical queries in **<1ms**, eliminating redundant LLM API calls and cutting token expenses.
* 🤖 **ReAct Agentic Workflow**: Dynamic tool selection (knowledge base search, precision calculator, and deterministic fallback synthesis).
* 🐳 **Production-Ready**: Complete with Docker Compose orchestration, unit test coverage, and automated GitHub Actions CI.

<br/>

#### 2. ⚡ [HookPulse — Resilient Webhook Relay & Event Delivery Engine](https://github.com/Jayouss/hookpulse)
> High-throughput, fault-tolerant webhook delivery platform built with **TypeScript (Node.js)** for guaranteed at-least-once event delivery.

* 🔁 **Exponential Backoff with Jitter**: Intelligent retry scheduling that scales intervals to prevent thundering herd crashes on downstream endpoints.
* 🔐 **Cryptographic Signatures**: Generates industry-standard `HMAC-SHA256` digest headers (`X-HookPulse-Signature`) with constant-time equality checks against timing attacks.
* 🛡️ **Idempotency Protection**: Enforces strict idempotency keys to ensure duplicate network events never cause duplicate processing.
* 📦 **Dead Letter Queue (DLQ) & Manual Replay**: Safely isolates exhausted events with complete attempt audit logs and one-click programmatic replay (`POST /api/v1/events/:id/replay`).
* 🧪 **Automated Testing & CI/CD**: 100% passing test suite and automated GitHub Actions workflow.

<br/>

#### 3. 🛡️ [PromptShield — High-Performance LLM Security Gateway](https://github.com/Jayouss/promptshield)
> Sub-millisecond reverse proxy and security firewall built with **Python (FastAPI)** protecting enterprise LLM applications against prompt injections and data leaks.

* 🛑 **Prompt Injection & Jailbreak Defense**: Detects instruction overrides, DAN roleplay exploits, and system prompt exfiltration based on OWASP Top 10 for LLMs.
* 🎭 **Zero-Latency PII Masking**: Automatically detects and redacts Emails, Credit Cards, API Keys, and National IDs before prompts hit OpenAI/Anthropic.
* ⏱️ **Ultra-Low Latency (<0.1ms)**: Pre-compiled regex automata and lightweight token counters add virtually zero overhead to AI pipelines.
* 🔌 **Drop-In OpenAI Compatible**: Works as a drop-in replacement proxy (`POST /v1/chat/completions`) for existing LLM applications.
* 🧪 **Attack Simulation Suite**: Complete with test harnesses and live adversarial attack verification.

<br/>

#### 4. 💼 [CareerPulse — Intelligent ATS Resume Scorer & Application Tailor](https://github.com/Jayouss/careerpulse)
> Open-source career acceleration engine built with **Python (FastAPI + CLI)** decoding ATS algorithms and auto-synthesizing tailored job applications.

* 📊 **Hybrid ATS Scoring**: Blends 60% hard keyword recall across 100+ tech taxonomies with 40% dense semantic cosine similarity to eliminate false screening rejections.
* 🔍 **Skill Gap Identification**: Instantly analyzes job descriptions against candidate profiles to pinpoint missing critical requirements.
* ✉️ **High-Converting Cold Outreach**: Auto-generates personalized emails to hiring managers highlighting relevant GitHub architecture and matching proficiencies.
* 🎯 **Google XYZ-Formula Bullets**: Synthesizes impact-driven experience bullets: *"Accomplished [X] as measured by [Y] by doing [Z]"*.
* 💻 **Dual Interface**: Runs as a high-throughput REST API with interactive Swagger docs or directly in the terminal via a developer CLI tool.

---

### 📊 GitHub Activity & Metrics

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=Jayouss&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" alt="Jay's GitHub Stats" />
  <br/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Jayouss&layout=compact&theme=tokyonight&hide_border=true&count_private=true" alt="Top Languages" />
</div>

---

<div align="center">
  <i>"Simplicity is prerequisite for reliability."</i> — Edsger W. Dijkstra
</div>
