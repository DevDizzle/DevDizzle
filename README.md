# Evan Parra

### AI engineer · St. Augustine / Jacksonville, FL

I build production systems clients own and run in their own cloud — RAG over operational data, agent workflows, custom apps. The work that pulls me in is the cross-system flows their legacy ERP, BI, and CRM stack couldn't deliver: reporting, approvals, and exports the per-seat tools were never going to build. The licenses retire alongside.

The repos below are the public ones; embedded engagements happen privately.

**Practice (outside builds):** [evanparra.ai](https://evanparra.ai)

---

## What I Ship

**Founding engagement — Regional commercial electrical contractor (NE Florida, anonymized).** Embedded in the client's Azure tenant, replacing per-seat ERP workflows app by app — cost-to-complete forecasting, change orders, approvals, and the cross-system flows the per-seat tools were never going to build. **~$150K/yr in retired per-seat ERP cost (and growing).** The ERP stays the system of record; the seats don't.

**Cross-vertical proof — my own products, both live:**

- **[TextTimeline](https://texttimeline.com)** — legal document intelligence. Messy text exports become attorney-ready chronological timelines with 100% source citations. FAISS + BM25 hybrid retrieval, Cloud Run, Firestore, Gemini. *(Source private — paid product.)*
- **[GammaRips](https://gammarips.com)** — autonomous overnight options-flow scanner. 14 Cloud Run services, ~20 schedulers, multi-agent ADK publishing layer with deterministic compliance gating.

---

## 🔧 What I Build

| Area | Focus |
|------|-------|
| **Custom workflow apps** | Production systems in client clouds — cross-system reporting, multi-stage approvals, and exports legacy ERP, BI, and CRM tools couldn't build; per-seat licenses retire alongside |
| **Generative AI** | Diffusion models, fine-tuning (LoRA/QLoRA), multi-modal pipelines, content safety |
| **LLM Applications** | RAG systems, prompt chaining, MCP tool servers, agent orchestration |
| **ML Pipelines** | End-to-end data ingestion → feature engineering → model deployment |
| **Evaluation & Safety** | Hallucination detection, factual accuracy, brand safety, A/B benchmarking |
| **MLOps** | CI/CD for ML, model versioning, monitoring, cost optimization |
| **Data Engineering** | BigQuery, ETL/ELT pipelines, multi-source integration |

---

## 🚀 Public Production Systems

### [GammaRips Engine](https://github.com/DevDizzle/gammarips-engine)
Autonomous trading signal platform processing ~10GB daily market data. Full MLOps lifecycle from ingestion to deployment.

- LLM-augmented ETL with prompt chaining
- MCP server for AI agent tool-calling
- CI/CD: GitHub Actions → Cloud Build → Cloud Run
- 50% inference cost reduction via dynamic model routing

**Stack:** Python, BigQuery, Vertex AI, Cloud Run, Pub/Sub, MCP

### [GammaRips Webapp](https://github.com/DevDizzle/gammarips-webapp)
Customer-facing surface for GammaRips. Daily mechanically-held picks, subscription billing, compliance disclosures.

### [GammaRips Models](https://github.com/DevDizzle/gammarips-models)
ML core for the GammaRips signal stack. ~3x precision lift versus baseline, with a quarterly retraining cadence.

### [MCP Financial Tools Server](https://github.com/DevDizzle/gammarips-mcp)
Model Context Protocol server enabling AI agents to query real-time financial data. Production-deployed on Cloud Run with SSE transport.

**Stack:** Python, FastMCP, BigQuery, Cloud Run

---

## 🧪 Generative AI & Evaluation

### [GenAI Evaluation Framework](https://github.com/DevDizzle/genai-eval-framework)
Production evaluation framework for generative AI systems. NLI-based hallucination detection, factual accuracy verification, content safety scoring, and A/B model benchmarking with statistical significance testing.

- Hallucination detection via cross-encoder NLI + semantic similarity
- Brand safety scoring with configurable content rating (G/PG/PG-13/R)
- A/B comparison engine with paired t-test and effect size analysis
- HTML + JSON reporting for CI/CD integration

**Stack:** Transformers, Sentence-Transformers, Detoxify, Scikit-Learn, Pydantic

### [LoRA Fine-Tuning Lab](https://github.com/DevDizzle/lora-finetune-lab)
Parameter-efficient fine-tuning of LLMs using QLoRA. 4-bit quantization with PEFT adapters, full training pipeline with experiment tracking.

- QLoRA with BitsAndBytes NF4 quantization
- SFTTrainer from TRL with gradient accumulation
- Weights & Biases experiment tracking and evaluation
- Interactive inference with streaming output

**Stack:** Transformers, PEFT, TRL, Accelerate, BitsAndBytes, W&B

### [Diffusion Style Transfer](https://github.com/DevDizzle/diffusion-style-transfer)
Text-to-image generation with Stable Diffusion XL, IP-Adapter style conditioning, and content safety guardrails.

- SDXL base + refiner pipeline with safety-first architecture
- Brand consistency scoring via CLIP embeddings
- Content rating system (G/PG/PG-13) for family-friendly generation
- NSFW classification and automated content filtering

**Stack:** Diffusers, Transformers, OpenCLIP, PyTorch, Pillow

### [Whisper Multimodal Pipeline](https://github.com/DevDizzle/whisper-multimodal-pipeline)
Cross-modal AI pipeline: audio transcription → LLM analysis → structured output. Dual backend support with async orchestration.

- Whisper + Google Cloud Speech-to-Text dual backends
- Gemini-powered analysis: sentiment, entities, topics, action items
- Pydantic-validated structured JSON output
- Async pipeline with retry logic and batch processing

**Stack:** OpenAI Whisper, Google Generative AI, Pydantic, PyDub

---

## 📂 More Projects

### [Healthcare Graph RAG Agent](https://github.com/DevDizzle/healthcare-graph-rag-agent)
Knowledge-grounded clinical Q&A agent using Graph RAG with Google Cloud. Combines medical knowledge graphs with retrieval-augmented generation for accurate, citation-backed healthcare answers.

**Stack:** Python, ADK, Gemini, Spanner Graph, Vertex AI, Cloud Run

### [Autonomous Invoice Agent](https://github.com/DevDizzle/galatiq-invoice-agent)
Multi-agent system automating invoice lifecycle: Ingestion → Validation → Approval → Payment. Self-correction loops for data extraction.

**Stack:** Python, LangGraph, xAI Grok, FastAPI, Cloud Run

### [Serverless PII Vault](https://github.com/DevDizzle/serverless-pii-vault)
Secure file storage with user isolation and irreversible PII redaction using event-driven architecture.

**Stack:** Cloud Run, Cloud DLP, Vertex AI, FastAPI

### [RAG Paper Analyzer](https://github.com/DevDizzle/SciPaper-Chat)
Multi-document scientific paper Q&A with citation tracking. Vertex AI Vector Search + Gemini.

**Stack:** RAG, Vertex AI, Gemini, FastAPI, Firestore

### [YOLOv9 Detection Guide](https://github.com/DevDizzle/yolov9-object-detection-guide)
Computer vision research from M.S. AI coursework at Florida Atlantic University — end-to-end guide for fine-tuning YOLOv9 on custom datasets.

**Stack:** PyTorch, YOLO, Computer Vision

---

## 💻 Tech Stack

```
Generative AI:  Diffusers, PEFT/LoRA, Whisper, Stable Diffusion, CLIP
ML/AI:          Vertex AI, Gemini, TensorFlow, PyTorch, Scikit-Learn
Evaluation:     Sentence-Transformers, Detoxify, W&B, custom frameworks
Cloud:          GCP (BigQuery, Cloud Run, Pub/Sub, Cloud Functions, Vertex AI), Azure (client engagements)
MLOps:          GitHub Actions, Cloud Build, Docker, Model Registry
Data:           Python, SQL, Pandas, dbt, Airflow
Backend:        FastAPI, Python, Node.js
Frontend:       Next.js, React, TypeScript
```

---

## 📜 Credentials

- **M.S. Artificial Intelligence** — Florida Atlantic University
- **B.A. Economics** — Florida International University
- **Google Professional Machine Learning Engineer**
- **Google Advanced Data Analytics**
- **Lean Six Sigma Green Belt**
- **EVANPARRA.AI LLC** — SAM.gov registered (UEI FPLQTQK39ZE1), SBIR/STTR eligible (CLARA / DARPA proposal submitted Mar 2026)

---

## 📫 Connect

- **Practice:** [evanparra.ai](https://evanparra.ai)
- **Email:** evan@evanparra.ai
- **LinkedIn:** [linkedin.com/in/evanparra](https://linkedin.com/in/evanparra)

---

*Booking discovery engagements through [evanparra.ai](https://evanparra.ai). Based in NE Florida; embedded work in Azure or GCP tenants.*
5. Update pinned repos (§3)
6. Fix `gammarips-engine` homepage URL + add `lora-finetune-lab` topics (§4a-b)
