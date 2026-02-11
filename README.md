# Evan Parra 👋

### ML Engineer | Building Production AI & Generative Systems on GCP

I build end-to-end ML systems that ship to production. My focus is autonomous pipelines, generative AI, model evaluation, and LLM-powered applications on **Google Cloud Platform**.

**MS in Artificial Intelligence (FAU, 2025) | Google Certified ML Engineer**

---

## 🔧 What I Build

| Area | Focus |
|------|-------|
| **Generative AI** | Diffusion models, fine-tuning (LoRA/QLoRA), multi-modal pipelines, content safety |
| **ML Pipelines** | End-to-end data ingestion → feature engineering → model deployment |
| **Evaluation & Safety** | Hallucination detection, factual accuracy, brand safety, A/B benchmarking |
| **LLM Applications** | RAG systems, prompt chaining, MCP tool servers, agent orchestration |
| **MLOps** | CI/CD for ML, model versioning, monitoring, cost optimization |
| **Data Engineering** | BigQuery, ETL/ELT pipelines, multi-source integration |

---

## 🚀 Production Systems

### [Financial ML Platform](https://github.com/DevDizzle/profitscout-engine)
Autonomous trading signal system processing ~10GB daily market data. Full MLOps lifecycle from ingestion to deployment.

- LLM-augmented ETL with prompt chaining
- MCP server for AI agent tool-calling
- CI/CD: GitHub Actions → Cloud Build → Cloud Run
- 50% inference cost reduction via dynamic model routing

**Stack:** Python, BigQuery, Vertex AI, Cloud Run, Pub/Sub, MCP

### [MCP Financial Tools Server](https://github.com/DevDizzle/profitscout-mcp)
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
End-to-end guide for fine-tuning YOLOv9 on custom datasets.

**Stack:** PyTorch, YOLO, Computer Vision

---

## 💻 Tech Stack

```
Generative AI:  Diffusers, PEFT/LoRA, Whisper, Stable Diffusion, CLIP
ML/AI:          Vertex AI, Gemini, TensorFlow, PyTorch, Scikit-Learn
Evaluation:     Sentence-Transformers, Detoxify, W&B, custom frameworks
Cloud:          GCP (BigQuery, Cloud Run, Pub/Sub, Cloud Functions, Vertex AI)
MLOps:          GitHub Actions, Cloud Build, Docker, Model Registry
Data:           Python, SQL, Pandas, dbt, Airflow
Backend:        FastAPI, Python, Node.js
Frontend:       Next.js, React, TypeScript
```

---

## 📜 Certifications

- **Google Professional Machine Learning Engineer** (2025)
- **Google Advanced Data Analytics Certificate**
- **MS Artificial Intelligence** — Florida Atlantic University

---

## 📫 Connect

- **LinkedIn:** [linkedin.com/in/evanparra](https://linkedin.com/in/evanparra)
- **Portfolio:** [evanparra.ai](https://evanparra.ai)
- **Email:** eraphaelparra@gmail.com
- **GitHub:** You're here

---

*Currently open to ML Engineer, GenAI Engineer, and Data Engineer opportunities. Remote or US-based.*
