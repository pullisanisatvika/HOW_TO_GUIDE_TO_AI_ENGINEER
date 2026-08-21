# AI Engineer Skills

> Skills identified from my analysis of **895 AI Engineering job postings** across Los Angeles, New York, London, Amsterdam, and Berlin.

## Key Findings

- **93.1%** of AI-First roles require skills beyond GenAI.
- **82.5%** of jobs require Python.
- **64.3%** of AI-First roles require ML knowledge.
- **35.9%** mention RAG.
- Production skills such as Docker, CI/CD, Kubernetes, and cloud are common.
- AI Engineering is primarily a **software engineering role with an AI specialization**.

---

## 1. Python

Python is the primary programming language for AI Engineering.

### Skills to Build

- Python fundamentals
- Object-Oriented Programming (OOP)
- Data structures
- Async programming
- API integration
- Error handling
- Testing
- Clean and maintainable code

**Market Signal:** Python appeared in **738/895 jobs (82.5%)**.

**Priority:** High

---

## 2. Backend Development & APIs

AI applications need backend services to connect models, databases, tools, and users.

### Skills to Build

- FastAPI
- REST APIs
- API design
- Authentication
- Async APIs
- Database integration
- Backend architecture

**Priority:** High

---

## 3. LLM Fundamentals

Before relying on AI frameworks, I need to understand how LLM-powered applications work.

### Skills to Build

- Prompt engineering
- Tokens and context windows
- Structured outputs
- Function calling
- Tool calling
- Streaming responses
- Model parameters
- Model selection
- Latency optimization
- Cost optimization
- OpenAI API
- Anthropic API

**Priority:** High

---

## 4. Retrieval-Augmented Generation (RAG)

RAG is the most common GenAI pattern found in my job-market analysis.

### Skills to Build

- Embeddings
- Chunking strategies
- Semantic search
- Vector search
- Document ingestion
- Retrieval
- Reranking
- Metadata filtering
- Hybrid search
- RAG evaluation

### Tools to Explore

- pgvector
- Pinecone
- Weaviate

**Market Signal:** RAG appeared in **321 jobs (35.9%)**.

**Priority:** High

---

## 5. AI Agents

Agents are another major pattern in modern AI Engineering.

### Skills to Build

- Tool calling
- Agent workflows
- State management
- Memory
- Workflow orchestration
- Multi-step workflows
- Human-in-the-loop systems
- Error handling
- Agent evaluation

**Priority:** High

---

## 6. AI Frameworks

Framework demand from the analyzed jobs:

| Framework | Jobs | Percentage |
|---|---:|---:|
| LangChain | 168 | 18.8% |
| LangGraph | 72 | 8.0% |
| LlamaIndex | 52 | 5.8% |
| CrewAI | 28 | 3.1% |
| AutoGen | 17 | 1.9% |

### Initial Focus

1. **LangChain**
2. **LangGraph**
3. **LlamaIndex**

My goal is to understand the underlying AI patterns rather than depend entirely on a specific framework.

---

## 7. Databases

AI applications require both traditional databases and vector search.

### Skills to Build

- SQL
- PostgreSQL
- pgvector
- Redis
- Vector databases
- Database design
- Indexing
- CRUD operations

**Priority:** High

---

## 8. Machine Learning Fundamentals

AI Engineers need practical ML knowledge, but most roles do not require research-level ML expertise.

### Skills to Build

- Machine Learning fundamentals
- Supervised vs. unsupervised learning
- Training vs. inference
- Train / validation / test splits
- Neural network basics
- Transformers
- Embeddings
- Model evaluation
- PyTorch fundamentals
- Fine-tuning fundamentals

**Market Signal:** **64.3%** of AI-First roles require some ML knowledge.

**Priority:** High

---

## 9. AI Evaluation & Observability

Building an AI system is not enough. I also need to measure whether it works reliably.

### Skills to Build

- Golden datasets
- LLM-as-a-judge
- RAG evaluation
- Retrieval evaluation
- Agent evaluation
- Hallucination detection
- Tracing
- Logging
- Monitoring
- Latency tracking
- Cost tracking

**Priority:** High

---

## 10. Production & DevOps

AI Engineers are expected to ship production systems, not just build notebooks.

### Skills to Build

- Docker
- CI/CD
- Kubernetes basics
- Environment management
- Secrets management
- Logging
- Monitoring

### Market Signals

| Skill | Jobs |
|---|---:|
| Docker | 277 |
| CI/CD | 262 |
| Kubernetes | 260 |

**Priority:** High

---

## 11. Cloud

Cloud platforms appear frequently across AI Engineering positions.

| Cloud Platform | Jobs |
|---|---:|
| AWS | 359 |
| Azure | 214 |
| GCP | 205 |

I will focus on learning one cloud platform deeply before expanding to others.

### Skills to Build

- Compute
- Storage
- IAM
- Networking basics
- Databases
- Containers
- Serverless services
- Application deployment
- Monitoring

**Priority:** High

---

## 12. Frontend Development

Frontend knowledge will help me build complete AI products.

### Skills to Build

- HTML / CSS
- JavaScript
- TypeScript
- React
- Next.js
- API integration
- Streaming AI responses
- AI chat interfaces

**Priority:** Medium

---

## 13. Fine-Tuning

Fine-tuning is useful, but my job-market analysis suggests it should not be my first priority.

### Skills to Learn Later

- Fine-tuning concepts
- LoRA
- PEFT
- Dataset preparation
- Instruction tuning
- Model evaluation
- RAG vs. fine-tuning trade-offs

**Priority:** Medium / Advanced

---

# Target AI Engineering Stack

```text
Frontend
React / Next.js
        ↓
Backend
Python / FastAPI / REST APIs
        ↓
AI Orchestration
LangChain / LangGraph / LlamaIndex
        ↓
LLMs
OpenAI / Anthropic / Open-Source Models
        ↓
Data & Retrieval
PostgreSQL / pgvector / Vector Databases / Redis
        ↓
Production
Docker / CI/CD / Kubernetes
        ↓
Cloud
AWS / Azure / GCP
```

---

# Learning Roadmap

## Phase 1 — Software Engineering Foundation

- [ ] Python
- [ ] Git & GitHub
- [ ] SQL
- [ ] PostgreSQL
- [ ] REST APIs
- [ ] FastAPI

## Phase 2 — LLM Fundamentals

- [ ] LLM fundamentals
- [ ] Prompt engineering
- [ ] OpenAI API
- [ ] Anthropic API
- [ ] Structured outputs
- [ ] Function / tool calling

## Phase 3 — RAG

- [ ] Embeddings
- [ ] Vector databases
- [ ] Chunking
- [ ] Retrieval
- [ ] Reranking
- [ ] RAG
- [ ] RAG evaluation

## Phase 4 — Agents

- [ ] LangChain
- [ ] Agent fundamentals
- [ ] Tool calling
- [ ] LangGraph
- [ ] Stateful workflows
- [ ] Agent evaluation

## Phase 5 — Production AI

- [ ] Docker
- [ ] Logging
- [ ] Monitoring
- [ ] AI observability
- [ ] Cloud deployment
- [ ] CI/CD
- [ ] Kubernetes basics

## Phase 6 — Full-Stack AI

- [ ] JavaScript / TypeScript
- [ ] React
- [ ] Next.js
- [ ] Connect frontend to AI backend
- [ ] Streaming AI interfaces

## Phase 7 — ML & Advanced AI

- [ ] ML fundamentals
- [ ] PyTorch fundamentals
- [ ] Transformers
- [ ] Fine-tuning
- [ ] LoRA / PEFT

---

# Goal

My goal is not to learn every AI tool or framework.

My goal is to become a **software engineer capable of building, evaluating, deploying, and maintaining production AI systems**.

Based on my job-market analysis, the strongest foundation is:

> **Software Engineering + LLMs + RAG + Agents + Evaluation + Production**

This skill map will guide the projects and learning documented throughout this repository.
