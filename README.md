<div align="center">

<!-- Typing SVG Header -->
[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=700&size=28&pause=1000&color=6E40C9&center=true&vCenter=true&width=700&lines=AI+%26+Automation+Engineer;RAG+%7C+LangChain+%7C+n8n+Specialist;I+turn+your+data+into+intelligent+products)](https://git.io/typing-svg)

<br/>

<!-- Social / Contact Badges -->
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/chiransh-g-b8b1ab85/)
[![Email](https://img.shields.io/badge/Email-Contact-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:gulatichiransh@gmail.com)

</div>

---

## 👋 About Me

I'm an **AI & Automation Engineer** specialising in turning unstructured data and manual workflows into intelligent, automated systems. I build production-ready pipelines — not demos.

My work sits at the intersection of **LLMs, RAG systems, and workflow automation** (n8n, LangChain). Whether you need a document Q&A chatbot, an automated content intelligence pipeline, or an AI-powered internal tool — I architect, build, and ship it.

> *"Few projects, high quality — every repo here is something I'd put in front of an enterprise client."*

---

## 🛠️ Tech Stack

<div align="center">

**AI / ML**

![LangChain](https://img.shields.io/badge/LangChain-🦜_RAG_Pipelines-2C2C2C?style=flat-square)
![OpenAI](https://img.shields.io/badge/OpenAI-GPT--4_/_Whisper-412991?style=flat-square&logo=openai&logoColor=white)
![HuggingFace](https://img.shields.io/badge/HuggingFace-Embeddings-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![ChromaDB](https://img.shields.io/badge/ChromaDB-Vector_DB-7C3AED?style=flat-square)
![Sentence Transformers](https://img.shields.io/badge/Sentence_Transformers-Semantic_Search-orange?style=flat-square)

**Automation & Workflows**

![n8n](https://img.shields.io/badge/n8n-Workflow_Automation-EA4B71?style=flat-square)
![Python](https://img.shields.io/badge/Python-3.12+-3776AB?style=flat-square&logo=python&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-Microservices-000000?style=flat-square&logo=flask&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-AI_Web_UIs-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)

**Infrastructure & DevOps**

![Docker](https://img.shields.io/badge/Docker-Containerisation-2496ED?style=flat-square&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-CI%2FCD-2088FF?style=flat-square&logo=github-actions&logoColor=white)
![Google APIs](https://img.shields.io/badge/Google_APIs-Sheets_%7C_Drive-4285F4?style=flat-square&logo=google&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-Reverse_Proxy-009639?style=flat-square&logo=nginx&logoColor=white)

**Code Quality**

![MyPy](https://img.shields.io/badge/mypy-Type_Safe-blue?style=flat-square)
![Black](https://img.shields.io/badge/black-Formatted-000000?style=flat-square)
![Pytest](https://img.shields.io/badge/pytest-Tested-0A9EDC?style=flat-square&logo=pytest&logoColor=white)
![Bandit](https://img.shields.io/badge/bandit-Security_Scanned-yellow?style=flat-square)

</div>

---

## 🚀 Featured Projects

> These two projects demonstrate my skill set end-to-end.

---

### 🧠 Production RAG System — LangChain × ChromaDB × OpenAI

[![Repo](https://img.shields.io/badge/GitHub-rag--langchain--chroma--production-181717?style=flat-square&logo=github)](https://github.com/chiransh/rag-langchain-chroma-production)
![Python](https://img.shields.io/badge/Python-3.12+-blue?style=flat-square&logo=python)
![LangChain](https://img.shields.io/badge/LangChain-🦜-green?style=flat-square)
![ChromaDB](https://img.shields.io/badge/ChromaDB-Vector_DB-blueviolet?style=flat-square)
[![CI](https://github.com/chiransh/rag-langchain-chroma-production/actions/workflows/ci.yml/badge.svg)](https://github.com/chiransh/rag-langchain-chroma-production/actions)

**Ask questions over your own documents — get answers grounded in your data, not hallucinations.**

A clean, modular RAG pipeline built to enterprise standards. Designed to be swapped into any stack (Pinecone, pgvector, FastAPI — all drop-in replaceable).

```
Documents (PDF/DOCX/CSV/TXT)
  ↓ LangChain Loader + Chunker
  ↓ Sentence Transformer Embeddings
  ↓ ChromaDB Vector Store
  ↓ Similarity Search + Prompt Assembly
  ↓ GPT-4 → Grounded Answer
  ↓ Streamlit UI / Python API
```

| What it shows | Detail |
|---|---|
| 🏗️ RAG architecture | Indexing → Retrieval → Augmentation → Generation |
| 🔍 Vector search | ChromaDB with persistent storage, cosine similarity |
| 🤖 LLM integration | OpenAI GPT-4 via LangChain, prompt engineering |
| 🧪 Test coverage | Pytest suite, Codecov, CI on every push |
| 📦 Production quality | MyPy, Black, Bandit, flake8 — zero compromise |

<details>
<summary>📋 Business use cases this unlocks</summary>

- **Internal knowledge base Q&A** — HR policies, SOPs, legal docs
- **Financial & legal document analysis** — contracts, reports
- **Customer support automation** — product catalogues, FAQs
- **Healthcare research** — clinical guidelines, research papers
- **Education** — curriculum-aligned AI tutors

</details>

---

### ⚡ Agentic AI Instagram Reel Extractor — n8n × Whisper × GPT

[![Repo](https://img.shields.io/badge/GitHub-n8n--instagram--reel--ai--extractor-181717?style=flat-square&logo=github)](https://github.com/chiransh/n8n-instagram-reel-ai-extractor)
![n8n](https://img.shields.io/badge/n8n-Workflow_Automation-EA4B71?style=flat-square)
![Docker](https://img.shields.io/badge/Docker-Self_Hosted-2496ED?style=flat-square&logo=docker)
![OpenAI](https://img.shields.io/badge/Whisper_%7C_GPT--4.1-412991?style=flat-square&logo=openai)
![Google Sheets](https://img.shields.io/badge/Google_Sheets-API-34A853?style=flat-square&logo=google-sheets)

**A fully self-hosted agentic pipeline that scrapes, transcribes, categorises, and stores social media content — hands-free.**

Form submission → scrape → transcribe → AI extract → structured database. Zero manual steps.

```
Google Form (Reel URL submitted)
  ↓ n8n polls Google Sheets every 5 min
  ↓ Instaloader (Flask microservice) scrapes video + description
  ↓ faster-whisper transcribes audio locally
  ↓ GPT-4.1-mini extracts + categorises via structured JSON prompt
  ↓ n8n Switch node routes to correct Google Sheets tab
```

| What it shows | Detail |
|---|---|
| 🔄 n8n workflow design | Multi-step agentic pipeline with error handling |
| 🐳 Docker orchestration | Multi-container setup, Nginx reverse proxy |
| 🎙️ Audio AI | faster-whisper transcription, CPU-optimised |
| 🤖 Prompt engineering | Structured JSON output, category classification |
| 🔗 API integration | Google Forms, Sheets, OpenAI — all connected |

<details>
<summary>📋 Business use cases this unlocks</summary>

- **Market & competitor intelligence** — automated social monitoring
- **Sentiment analysis** — brand tracking at scale
- **Content research** — structured database from any video source
- **Small business monitoring** — replace agency fees with automation
- **Cyber / brand risk detection** — flag mentions in real time

</details>

---

## 📊 GitHub Stats

<div align="center">

<img height="160" src="https://github-readme-stats.vercel.app/api?username=chiransh&show_icons=true&theme=tokyonight&hide_border=true&count_private=true&include_all_commits=true" />
<img height="160" src="https://github-readme-stats.vercel.app/api/top-langs/?username=chiransh&layout=compact&theme=tokyonight&hide_border=true&langs_count=6" />

</div>

<div align="center">

[![GitHub Streak](https://streak-stats.demolab.com?user=chiransh&theme=tokyonight&hide_border=true)](https://git.io/streak-stats)

</div>

---

## 💼 What I Can Build For You

I specialise in **AI-powered automation** for businesses that want to move fast without breaking things.

| I'm great for... | Examples |
|---|---|
| **RAG / Document Q&A systems** | Internal chatbots, contract analysis, knowledge bases |
| **LLM pipeline engineering** | Data extraction, classification, summarisation at scale |
| **n8n workflow automation** | Scraping, processing, routing, alerting — end-to-end |
| **AI microservices** | Flask/FastAPI wrappers around ML models, self-hosted |
| **Prototype → Production** | Taking an AI idea from concept to working system |

**Clean code. Tested. Documented. Delivered on time.**

---

<div align="center">

*Profile README • Updated June 2026*

</div>
