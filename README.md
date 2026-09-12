<div align="center">

# Hi, I'm Nguyễn Đình Dương 👋

### AI Engineer · LLM & Agentic Systems · AI Platform Engineering

I build production-oriented AI systems across **RAG, AI agents, Document AI, MCP integrations, and scalable backend platforms**.

Currently working as an **AI Engineer at Viettel Network**, where I design and build enterprise AI products from architecture and implementation through evaluation, deployment, and production operations.

<br/>

<a href="https://www.linkedin.com/in/nguyen-dinh-duong-074242248/">
  <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white" />
</a>
<a href="https://duongnguyen.info">
  <img src="https://img.shields.io/badge/Portfolio-121212?style=flat&logo=firefox&logoColor=white" />
</a>
<a href="mailto:2901nguyendinhduong@gmail.com">
  <img src="https://img.shields.io/badge/Email-EA4335?style=flat&logo=gmail&logoColor=white" />
</a>

</div>

---

## About Me

- 🧠 Building **production-grade LLM applications, RAG systems, and AI agents**
- 🏗️ Interested in **AI platform architecture, backend systems, and enterprise AI**
- 📄 Experienced with **Document AI, OCR/VLM pipelines, structured extraction, and automated validation**
- 🔌 Building AI integrations using **MCP, tool calling, REST APIs, and event-driven workflows**
- 🚀 Comfortable taking products from **system design → implementation → evaluation → deployment → observability**
- 🎓 Global ICT graduate from **Hanoi University of Science and Technology (HUST)**

My main interest is not just making an AI demo work — I enjoy turning AI capabilities into **reliable software systems that can actually be operated in production**.

---

## Selected Engineering Work

### 🏢 Enterprise AI Systems @ Viettel Network

> Source code and implementation details for these systems are private due to company confidentiality.

#### DocAI — Enterprise AI Workflow Automation Platform

Technical owner and lead developer of an enterprise platform for automating document-heavy business workflows.

I designed and implemented the core platform across:

- configurable document processing workflows
- OCR / VLM / LLM-based structured extraction
- cross-document validation and rule execution
- visual template and rule configuration
- human-in-the-loop review
- enterprise REST APIs and webhook integration
- MCP-based tools for AI-agent interaction
- backend, frontend, monitoring, and production operations

Recent acceptance testing achieved:

`99.32% extraction` · `100% classification` · `95.65% validation` · `4.76% manual intervention`

**Core technologies**

`Python` `FastAPI` `Next.js` `PostgreSQL` `Redis` `MinIO` `Docker` `Kubernetes` `Prometheus` `Grafana` `vLLM`

---

#### netMind — Enterprise AI Assistant

Contributing to Viettel Network's internal enterprise AI assistant, focusing on:

- RAG and agentic question-answering workflows
- document ingestion and retrieval
- MCP / external tool integration
- permission-aware agent execution
- Notebook-style research workflows
- AI-generated reports, presentations, and grounded content

**Core technologies**

`Python` `FastAPI` `LangGraph` `Qdrant` `PostgreSQL` `MinIO` `Keycloak` `OpenFGA` `Langfuse`

---

#### DocProcess — Document Processing Engine

Designed a reusable document-processing layer for AI applications such as Document AI, RAG, and data-protection workflows.

Key engineering areas:

- asynchronous / event-driven processing
- queue-backed worker architecture
- isolated processing pipelines for different document workloads
- modular document-format processors
- horizontal worker scaling
- failure handling and observability

In load testing, the system completed **100 concurrent processing tasks with zero failures**, while the optimized flow reduced processing time by **up to 90%** compared with the previous pipeline.

---

#### Data Masking Agent

Built an AI-assisted data-protection workflow for identifying and masking sensitive information before documents are sent to external AI services.

The system combines:

- keyword and regex detection
- semantic detection
- OCR-based document processing
- reversible masking
- in-place document transformation
- gateway-level integration

---

## Featured Personal & Academic Projects

### 🎓 CourseBot — AI Tutor Platform

**Solo Graduation Thesis · A+ / 9.5 · Best Presentation Award — Thesis Defense 2026**

An AI tutor platform that allows instructors to upload course materials and provides students with answers grounded strictly in those sources.

The AI pipeline includes:

```text
User Query
   ↓
Intent & Scope Router
   ↓
Policy Guardrails
   ↓
Query Rewriting
   ↓
Vector Retrieval
   ↓
Evidence Evaluation
   ↓
Weak-Evidence Refusal
   ↓
LLM Generation
   ↓
Citations & Quality Metrics
````

I independently built the complete system, including:

* RAG with source citations
* LLM-based scope routing
* evidence judging
* streaming responses
* teacher management dashboard
* student embeddable chat widget
* authentication and RBAC
* document ingestion workers
* production Docker deployment
* HTTPS and CI/CD

**Stack**

`FastAPI` `React` `PostgreSQL` `Redis` `Qdrant` `MinIO` `Docker` `OpenAI`

> Repository is currently private.

---

### 🔎 Vector Database & RAG Benchmark

A benchmarking and evaluation project for comparing vector-search technologies for RAG workloads.

Evaluated systems including:

`Qdrant` · `Milvus` · `Elasticsearch` · `pgvector`

Focus areas:

* ingestion throughput
* query latency
* retrieval behavior
* ground-truth evaluation
* automated metrics
* architectural trade-offs for production RAG

---

### 📚 [StudySpace](https://github.com/duongnguyen291/StudySpace)

A full-stack learning platform combining:

* Pomodoro-based study workflows
* AI-assisted learning
* adaptive quizzes
* course and study-session management

**Stack:** `Next.js` `FastAPI` `MongoDB`

---

### 🤖 [Teacher Assistant](https://github.com/duongnguyen291/teacher-assistant)

A RAG-based teaching assistant for answering questions from course materials.

Built with:

`Docling` · `Qdrant` · `DeepSeek` · `Gemini`

---

### 🤟 [Sign Language Recognition](https://github.com/duongnguyen291/Sign-Language-Recognition)

Real-time sign-language recognition using computer vision and machine learning.

Compared CNN and Random Forest approaches and achieved approximately **97% classification accuracy**.

**Stack:** `Python` `OpenCV` `CNN`

---

## Technical Stack

### AI / LLM Systems

<p>
<img src="https://img.shields.io/badge/RAG-5C2D91?style=flat" />
<img src="https://img.shields.io/badge/AI_Agents-111827?style=flat" />
<img src="https://img.shields.io/badge/MCP-000000?style=flat" />
<img src="https://img.shields.io/badge/Document_AI-FF8C00?style=flat" />
<img src="https://img.shields.io/badge/OCR_%26_VLM-7C3AED?style=flat" />
<img src="https://img.shields.io/badge/vLLM-4B5563?style=flat" />
<img src="https://img.shields.io/badge/LangGraph-1C3C3C?style=flat" />
</p>

### Backend & Data

<p>
<img src="https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white" />
<img src="https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white" />
<img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white" />
<img src="https://img.shields.io/badge/Redis-DC382D?style=flat&logo=redis&logoColor=white" />
<img src="https://img.shields.io/badge/Qdrant-DC244C?style=flat" />
<img src="https://img.shields.io/badge/Milvus-00A1EA?style=flat" />
<img src="https://img.shields.io/badge/Elasticsearch-005571?style=flat&logo=elasticsearch&logoColor=white" />
<img src="https://img.shields.io/badge/MinIO-C72E49?style=flat&logo=minio&logoColor=white" />
</p>

### Platform & DevOps

<p>
<img src="https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white" />
<img src="https://img.shields.io/badge/Kubernetes-326CE5?style=flat&logo=kubernetes&logoColor=white" />
<img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat&logo=githubactions&logoColor=white" />
<img src="https://img.shields.io/badge/Prometheus-E6522C?style=flat&logo=prometheus&logoColor=white" />
<img src="https://img.shields.io/badge/Grafana-F46800?style=flat&logo=grafana&logoColor=white" />
<img src="https://img.shields.io/badge/Linux-FCC624?style=flat&logo=linux&logoColor=black" />
</p>

### Frontend

<p>
<img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white" />
<img src="https://img.shields.io/badge/Next.js-000000?style=flat&logo=nextdotjs&logoColor=white" />
<img src="https://img.shields.io/badge/React-20232A?style=flat&logo=react&logoColor=61DAFB" />
</p>

---

## Education & Recognition

**Hanoi University of Science and Technology — HUST**
B.Eng. in Global ICT · CPA **3.78 / 4.0**

* 🏆 **Best Presentation Award — Thesis Defense 2026**
* 🎓 **Vietcombank Scholarship for Outstanding Students** — 2024–2025, 2025–2026
* 🤖 **AI Ambassador — Viettel AI Race 2025**
* 🎓 **HUST Academic Excellence Scholarship** — multiple semesters
* 🥇 **Top 1 — Student Creative Ideas Challenge, SOICT**

---

## What I'm Interested In

I'm particularly interested in engineering problems around:

```text
LLM Applications
├── Retrieval-Augmented Generation
├── Agentic Workflows
├── Tool / MCP Integration
├── Document Intelligence
└── Evaluation & Guardrails

AI Platforms
├── Backend Architecture
├── Async / Event-driven Processing
├── Model Integration
├── Observability
├── Scalability
└── Production Reliability
```

---

<div align="center">

### Let's Connect

I'm always interested in discussing **AI engineering, LLM systems, RAG, AI agents, and AI platform architecture**.

<a href="mailto:2901nguyendinhduong@gmail.com">Email</a>
 ·  <a href="https://www.linkedin.com/in/nguyen-dinh-duong-074242248/">LinkedIn</a>
 ·  <a href="https://duongnguyen.info">Portfolio</a>

</div>
