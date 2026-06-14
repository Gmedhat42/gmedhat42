<h1 align="center">George Medhat Fawzy</h1>
<h3 align="center">AI Engineer · Multi-Agent Systems · Production Automation</h3>

<p align="center">
  Building autonomous AI systems that replace manual work — agents that reason, plan, and act end-to-end.<br/>
  Based in Cairo, Egypt · Currently at <strong>EDECS</strong>
</p>

<p align="center">
  <a href="https://linkedin.com/in/gmedhat42"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
  <a href="mailto:gmedhat42@gmail.com"><img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white"/></a>
</p>

---

## What I Build

I specialize in **multi-agent orchestration** and **AI-powered automation pipelines** — systems where LLMs don't just answer questions, they autonomously execute entire workflows.

- **Multi-agent systems** — LangGraph ReAct loops, orchestrator → specialist routing, autonomous tool selection
- **Context engineering** — surgical retrieval as part of chain-of-thought, not pre-baked RAG
- **Streaming infrastructure** — Redis Streams, SSE, cursor-based reconnection, zero event loss
- **Production observability** — Langfuse end-to-end tracing, LLM-as-judge evaluation with promptfoo

---

## Featured Projects

### 🏗️ Keplon — AI Construction Platform
> Production multi-agent system at EDECS

- Orchestrator routes to domain-specialist agents (contracts, insurance, tendering) via a unified LangGraph ReAct loop
- Handles **10 GB per request**, reasons over **1,000-page documents**
- Agents survive pod restarts mid-reasoning without losing intermediate state
- Central tool registry: clause retrieval, multi-document search, Word/Excel generation, sub-agent invocation
- Real-time delegation via Redis Streams + SSE with cursor-based reconnection

---

### 📈 Zibi — AI DeFi Analytics Agent
> Real-time conversational analytics over DefiLlama, CoinGlass, and 1inch

- Routes queries to correct live API endpoints across **120 endpoints / 30 categories**
- **~90% accuracy** vs ~25% baseline — measured with promptfoo LLM-as-judge
- API responses stored server-side by result ID — LLM never sees raw data
- Local computation: RSI, SMA, EMA, Bollinger Bands, Monte Carlo — math never delegated to the LLM
- SSE streaming with Redis fan-out and volatility-tiered caching

---

### 🤖 Vendor Document Automation
> Arabic OCR → structured extraction pipeline

- Replaced manual processing of scanned Arabic invoices, contracts, and procurement files
- OCR tuned for right-to-left layouts, mixed Arabic/English, and degraded scan quality
- Structured output feeds directly into downstream procurement systems

---

### 💬 AskEDECS — Internal Knowledge Chatbot
> Company-wide RAG chatbot in daily production use

- RAG over EDECS's full knowledge base (procedures, policies, guidelines)
- Tuned chunking and retrieval for heterogeneous internal documents
- Hallucination-resistant — answers always grounded in source

---

### 🧠 Knowledge Graphs for Hallucination Correction *(Thesis)*
> [Repo](https://github.com/Gmedhat42/KG_hallucination_Correction)

- Research into using Neo4j knowledge graphs to detect and correct LLM hallucinations
- Grounding LLM outputs against structured factual graphs as a post-generation verification layer

---

### 🔍 Data Scraping Suite

| Project | Description |
|---|---|
| [Google-Maps-Scraper](https://github.com/Gmedhat42/Google-Maps-Scraper) | Retrieves all restaurants & cafes in any district — name, rating, address — fully automated given any location input |
| [Hatla2ee_Scarping](https://github.com/Gmedhat42/Hatla2ee_Scarping) | Full used-car listings dataset scraped from Hatla2ee — powers the Egyptian car price prediction model |
| [Sylndr-Scraping](https://github.com/Gmedhat42/Sylndr-Scraping) | Used-car listings scraper for Sylndr marketplace |
| [Underdog-Scraping](https://github.com/Gmedhat42/Underdog-Scraping) | Sports data scraper for Underdog Fantasy platform |

---

## Stack

### 🤖 AI & Agents
<p>
  <img src="https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white"/>
  <img src="https://img.shields.io/badge/LangGraph-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white"/>
  <img src="https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white"/>
  <img src="https://img.shields.io/badge/Anthropic_Claude-CC785C?style=for-the-badge&logo=anthropic&logoColor=white"/>
  <img src="https://img.shields.io/badge/Google_Gemini-4285F4?style=for-the-badge&logo=google&logoColor=white"/>
  <img src="https://img.shields.io/badge/Ollama-000000?style=for-the-badge&logo=ollama&logoColor=white"/>
</p>

### 🐍 Languages
<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white"/>
  <img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white"/>
  <img src="https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white"/>
</p>

### ⚙️ Infra & Deployment
<p>
  <img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white"/>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white"/>
  <img src="https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white"/>
  <img src="https://img.shields.io/badge/AWS_EKS-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white"/>
  <img src="https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white"/>
</p>

### 📊 Observability & Eval
<p>
  <img src="https://img.shields.io/badge/Langfuse-000000?style=for-the-badge&logo=langfuse&logoColor=white"/>
  <img src="https://img.shields.io/badge/Neo4j-008CC1?style=for-the-badge&logo=neo4j&logoColor=white"/>
  <img src="https://img.shields.io/badge/Pydantic-E92063?style=for-the-badge&logo=pydantic&logoColor=white"/>
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white"/>
</p>

---

## GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=gmedhat42&show_icons=true&theme=dark&hide_border=true&count_private=true" height="165"/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=gmedhat42&layout=compact&theme=dark&hide_border=true&count_private=true" height="165"/>
</p>

<p align="center">
  <img src="https://streak-stats.demolab.com/?user=gmedhat42&theme=dark&hide_border=true"/>
</p>

---

## Education

**B.Sc. Computer Engineering** — German University in Cairo (GUC), 2021–2026  
Thesis: *Using Knowledge Graphs for Hallucination Correction*
