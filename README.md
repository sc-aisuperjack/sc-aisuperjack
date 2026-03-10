# AI Superjack, Stefanos Cunning

AI engineer building production-style demos and boilerplates across agentic systems, RAG, MCP, MongoDB intelligence, and data-driven AI workflows.

My work focuses on practical AI engineering rather than hype. I build systems that are structured, testable, grounded, and easy to review, with an emphasis on real architecture patterns such as orchestration, document ingestion, retrieval pipelines, provider abstraction, evaluation, and traceable outputs.

## What this GitHub is about

This portfolio brings together a growing set of AI projects that explore how modern AI applications should actually be built.

The main themes across my repositories are:

- agentic orchestration and workflow design
- retrieval-augmented generation with grounded answers
- MCP and tool-ready architectures
- MongoDB-connected AI systems
- document and data ingestion pipelines
- evaluation, traceability, and practical utility
- Streamlit and FastAPI demos that are easy to run and inspect

This is not a collection of toy chatbots. It is a portfolio of applied AI engineering work.

## Featured repositories

### [ai-superjack-foundry](https://github.com/sc-aisuperjack/ai-superjack-foundry)
Flagship production-style boilerplate for grounded, voice-enabled agentic AI applications.

Built with Streamlit, FastAPI, MongoDB, Redis, versioned APIs, document ingestion, retrieval flows, voice input and output, and multi-provider support including mock, OpenAI, Anthropic, and Gemini. Designed to demonstrate the shape of a serious AI platform rather than a single-purpose demo.

Core concepts:
- agentic application architecture
- RAG and grounding
- voice workflows
- document upload and chunking
- provider abstraction
- Redis and MongoDB integration
- API versioning and traces

### [ai-superjack-mcp-mongo](https://github.com/sc-aisuperjack/ai-superjack-mcp-mongo)
MongoDB-focused MCP boilerplate exploring how model context protocols and database-connected tooling can work together in a structured AI system.

This repo is aimed at building clean foundations for AI workflows that need direct access to MongoDB-backed resources, tool execution, and future-ready agent integrations.

Core concepts:
- MCP-oriented architecture
- MongoDB connectivity
- tool and resource patterns
- AI boilerplate foundations

### [agentic-os](https://github.com/sc-aisuperjack/agentic-os)
Agentic system template for orchestrator and worker services.

This project is about scalable agentic patterns rather than one-off prompting. It is designed for extensible automation workflows, task routing, tool use, and service decomposition that can be containerised and evolved into larger systems.

Core concepts:
- orchestrator and worker design
- modular agent workflows
- scalable service patterns
- automation-ready architecture

### [pdfragchat](https://github.com/sc-aisuperjack/pdfragchat)
Multi-document PDF RAG system with evaluation and page-aware citations.

This project converts PDFs to Markdown without relying on an LLM, chunks content for retrieval, stores embeddings, supports grounded multi-document chat, and evaluates retrieval quality with metrics such as MRR, Hit at k, Recall, Precision, and MAP.

Live demo: https://pdfragchat.streamlit.app/

Core concepts:
- PDF ingestion
- Markdown conversion
- chunking and embeddings
- page-aware citations
- multi-document RAG
- retrieval evaluation

### [mongolens](https://github.com/sc-aisuperjack/mongolens)
MongoDB export analysis and grounded insight generation.

MongoLens connects to MongoDB data, exports collections, generates profiling and analysis, and enables grounded Q and A backed by exported content. It is designed to bridge raw database exports and explainable insight workflows.

Live demo: https://mongolens.streamlit.app/

Core concepts:
- MongoDB inspection
- export and profiling workflows
- grounded answers over data
- RAG over structured exports

### [guestpulses](https://github.com/sc-aisuperjack/guestpulses)
Review intelligence for hospitality and experience-focused businesses.

GuestPulses processes CSV and Excel review datasets, maps columns, extracts sentiment and emotional signals, classifies hospitality categories, and produces structured insight outputs for business use.

Live demo: https://guestpulses.streamlit.app/

Core concepts:
- sentiment and emotion analysis
- hospitality review intelligence
- CSV and Excel ingestion
- classification and exportable insights

### [grabapic](https://github.com/sc-aisuperjack/grabapic)
Utility for downloading and organising images from URL lists.

A practical supporting tool for dataset building, content workflows, and automation scenarios where batch image collection is needed quickly and reliably.

Core concepts:
- image downloading workflows
- dataset support utilities
- content pipeline tooling

## What I build

I build AI systems that deal with the hard parts properly.

That includes:

- agentic workflows with orchestrators, workers, tools, and gateways
- RAG systems with real ingestion, chunking, embeddings, grounding, and citations
- document pipelines for PDFs, database exports, CSV, and Excel
- MongoDB-connected intelligence workflows
- MCP-ready foundations for tool-using AI applications
- evaluation and observability patterns to make results measurable and reviewable
- demos and boilerplates that are useful for learning, extending, and technical review

## Current stack

My public work regularly uses:

- Python
- Streamlit
- FastAPI
- MongoDB
- Redis
- LangChain
- OpenAI APIs
- Anthropic and Gemini provider patterns
- vector stores and retrieval pipelines
- Docker and Docker Compose
- structured API contracts and service layers

## Live demos

- PDF RAG Chat: https://pdfragchat.streamlit.app/
- GuestPulses: https://guestpulses.streamlit.app/
- MongoLens: https://mongolens.streamlit.app/

## How to run most repos

### 1. Create a virtual environment

```bash
python -m venv .venv
````

### 2. Activate it

Windows:

```bash
.venv\Scripts\activate
```

macOS or Linux:

```bash
source .venv/bin/activate
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

Some repos use a `pyproject.toml` setup instead, so check the repo-specific instructions where relevant.

### 4. Configure environment variables

Copy `.env.example` to `.env` and set required values such as API keys or connection strings.

Typical examples include:

* `OPENAI_API_KEY`
* `MONGODB_URI`
* `REDIS_URL`

### 5. Run the app

For Streamlit apps:

```bash
streamlit run app.py
```

For FastAPI backends:

```bash
uvicorn apps.api_gateway.main:app --reload
```

### 6. Run tests

```bash
pytest -q
```

## Why this portfolio is different

A lot of AI repos are either prompt wrappers or tutorial clones.

My goal is different. I want these repositories to show applied engineering decisions:

* how data is ingested
* how knowledge is grounded
* how providers are abstracted
* how workflows are orchestrated
* how outputs can be traced and evaluated
* how AI demos can be turned into stronger platform foundations

## Connect

* Website: [https://aisuperjack.com](https://aisuperjack.com)
* LinkedIn: [https://www.linkedin.com/in/stefanoscunning/](https://www.linkedin.com/in/stefanoscunning/)

