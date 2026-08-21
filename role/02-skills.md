AI Engineer Skills

Skills identified from my analysis of 895 AI Engineering job postings across Los Angeles, New York, London, Amsterdam, and Berlin.

Key Findings

* 93.1% of AI-First roles require skills beyond GenAI.
* 82.5% of jobs require Python.
* 64.3% of AI-First roles require ML knowledge.
* 35.9% mention RAG.
* Production skills such as Docker, CI/CD, Kubernetes, and cloud are common.
* AI Engineering is primarily an applied software engineering role with an AI specialization.

⸻

Core Skill Areas

1. Python

Python is the primary language for AI Engineering.

Skills to build:

* Python fundamentals
* OOP
* Data structures
* Async programming
* API integration
* Error handling
* Testing
* Clean and maintainable code

Market signal: Python appeared in 738/895 jobs (82.5%).

Priority: High

⸻

2. Backend & APIs

AI systems need backend services to connect models, databases, tools, and applications.

Skills to build:

* FastAPI
* REST APIs
* API design
* Authentication
* Async APIs
* Database integration
* Backend architecture

Priority: High

⸻

3. LLM Fundamentals

Before relying on frameworks, I need to understand the underlying LLM concepts.

Skills to build:

* Prompt engineering
* Tokens and context windows
* Structured outputs
* Function/tool calling
* Streaming
* Model parameters
* Model selection
* Latency and cost optimization
* OpenAI / Anthropic APIs

Priority: High

⸻

4. Retrieval-Augmented Generation (RAG)

RAG is the most common GenAI pattern found in the job analysis.

Skills to build:

* Embeddings
* Chunking
* Semantic search
* Vector search
* Document ingestion
* Retrieval
* Reranking
* Metadata filtering
* Hybrid search
* RAG evaluation

Tools:

* pgvector
* Pinecone
* Weaviate

Market signal: RAG appeared in 321 jobs (35.9%).

Priority: High

⸻

5. AI Agents

Agents are another major AI Engineering pattern.

Skills to build:

* Tool calling
* Agent workflows
* State management
* Memory
* Workflow orchestration
* Human-in-the-loop systems
* Error handling
* Agent evaluation

Priority: High

⸻

6. AI Frameworks

Framework	Jobs	Share
LangChain	168	18.8%
LangGraph	72	8.0%
LlamaIndex	52	5.8%
CrewAI	28	3.1%
AutoGen	17	1.9%

Initial focus:

1. LangChain
2. LangGraph
3. LlamaIndex

The goal is to understand the underlying AI patterns rather than depend on a specific framework.

⸻

7. Databases

Skills to build:

* SQL
* PostgreSQL
* pgvector
* Redis
* Vector databases
* Database design
* Indexing

Priority: High

⸻

8. Machine Learning Fundamentals

AI Engineers need practical ML knowledge, but most roles do not require research-level ML expertise.

Skills to build:

* ML fundamentals
* Neural network basics
* Transformers
* Embeddings
* Training vs. inference
* Model evaluation
* PyTorch fundamentals
* Fine-tuning fundamentals

Market signal: 64.3% of AI-First roles require some ML knowledge.

⸻

9. AI Evaluation

Building an AI system is not enough. I also need to measure its quality and reliability.

Skills to build:

* Golden datasets
* LLM-as-a-judge
* RAG evaluation
* Retrieval evaluation
* Agent evaluation
* Hallucination detection
* Tracing
* Logging
* Monitoring
* Latency and cost tracking

Priority: High

⸻

10. Production & DevOps

AI Engineers are expected to ship production systems.

Skills to build:

* Docker
* CI/CD
* Kubernetes basics
* Environment management
* Secrets management
* Logging
* Monitoring

Market signals:

* Docker — 277 jobs
* CI/CD — 262 jobs
* Kubernetes — 260 jobs

⸻

11. Cloud

Cloud demand from the analyzed jobs:

Cloud	Jobs
AWS	359
Azure	214
GCP	205

I will focus on learning one cloud platform deeply before expanding to others.

Skills to build:

* Compute
* Storage
* IAM
* Networking basics
* Databases
* Containers
* Serverless
* Deployment
* Monitoring

⸻

12. Frontend

Frontend is useful for building complete AI products.

Skills to build:

* JavaScript / TypeScript
* React
* Next.js
* API integration
* Streaming responses
* AI chat interfaces

Priority: Medium

⸻

13. Fine-Tuning

Fine-tuning is an advanced skill rather than my first priority.

Skills to learn later:

* LoRA
* PEFT
* Dataset preparation
* Instruction tuning
* Model evaluation
* RAG vs. fine-tuning trade-offs

Priority: Medium / Advanced

⸻

Target AI Engineering Stack

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

⸻

Learning Priority

* Python
* Git & GitHub
* FastAPI & REST APIs
* LLM fundamentals
* Prompt engineering
* Embeddings
* Vector databases
* RAG
* LangChain
* Agents
* LangGraph
* AI evaluation
* PostgreSQL
* Redis
* Docker
* Cloud deployment
* CI/CD
* Kubernetes basics
* React / Next.js
* PyTorch fundamentals
* Fine-tuning

⸻

Goal

My goal is not to learn every AI tool or framework.

My goal is to become a software engineer capable of building, evaluating, deploying, and maintaining production AI systems.

The job-market analysis suggests the strongest foundation is:

Software Engineering + LLMs + RAG + Agents + Evaluation + Production

This skill map will guide the projects and learning documented in this repository.

Commit it to GitHub

Put that into:

role/02-skills.md

Then use a commit message like:

docs: add AI engineer skills roadmap from job market analysis

That gives your repository a much more natural GitHub/project-documentation style rather than making it look like study notes.
