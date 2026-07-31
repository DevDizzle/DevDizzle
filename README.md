# Evan Parra

**AI engineer. St. Augustine / Jacksonville, FL.**

I ship production systems as one engineer. What makes that work is the harness: a spec-driven agentic SDLC with a skills library, adversarial review gates that can veto a change, and architecture rules enforced in lint instead of written in a wiki. Agents write most of the code. The harness is what makes it safe to keep.

Everything below came out of that loop. Most of the client work is private; these are the public ones.

**Written up:**

- [A solo engineer's production SDLC with AI agents](https://evanparra.ai/blog/solo-engineer-production-sdlc-with-ai-agents)
- [Lint as architecture enforcement](https://evanparra.ai/blog/lint-as-architecture-enforcement)
- [An independent AI code review gate](https://evanparra.ai/blog/independent-ai-code-review-gate)
- [Verify every write to the system of record](https://evanparra.ai/blog/verify-every-write-to-the-system-of-record)

Practice: [evanparra.ai](https://evanparra.ai)

## Current work

**Employed with a regional commercial electrical contractor, NE Florida.** Software engineer building custom apps inside the Azure tenant: forecasting, change orders, approvals, reporting. Their tenant, their repo, their code, and the team ships on the same harness I do.

**Products I run:**

- **[TextTimeline](https://texttimeline.com)**: legal document intelligence. Messy text exports become chronological timelines with a citation on every entry. FAISS + BM25 hybrid retrieval, Cloud Run, Firestore, Gemini. *(Source private, paid product.)*
- **[GammaRips](https://gammarips.com)**: overnight options-flow scanner. 14 Cloud Run services, ~20 schedulers, multi-agent ADK publishing layer with deterministic compliance gating.

## Public repos

**Trading and data platform**

- **[gammarips-engine](https://github.com/DevDizzle/gammarips-engine)**: signal platform over ~10GB/day of market data. LLM-augmented ETL, MCP tool server, GitHub Actions to Cloud Build to Cloud Run. *Python, BigQuery, Vertex AI, Pub/Sub.*
- **[gammarips-webapp](https://github.com/DevDizzle/gammarips-webapp)**: customer-facing surface. Daily picks, subscription billing, compliance disclosures.
- **[gammarips-mcp](https://github.com/DevDizzle/gammarips-mcp)**: MCP server so agents can query financial data. FastMCP on Cloud Run, SSE transport.

**Generative AI and evaluation**

- **[genai-eval-framework](https://github.com/DevDizzle/genai-eval-framework)**: hallucination detection via cross-encoder NLI plus semantic similarity, content safety scoring, and A/B model comparison with paired t-tests. HTML and JSON reports for CI. *Transformers, Sentence-Transformers, Detoxify, Pydantic.*
- **[lora-finetune-lab](https://github.com/DevDizzle/lora-finetune-lab)**: QLoRA fine-tuning with 4-bit NF4 quantization, PEFT adapters, TRL SFTTrainer, and W&B tracking. *Transformers, PEFT, TRL, Accelerate.*
- **[diffusion-style-transfer](https://github.com/DevDizzle/diffusion-style-transfer)**: SDXL base and refiner with IP-Adapter style conditioning, CLIP-based consistency scoring, NSFW filtering. *Diffusers, OpenCLIP, PyTorch.*
- **[whisper-multimodal-pipeline](https://github.com/DevDizzle/whisper-multimodal-pipeline)**: audio to transcription to Gemini analysis to Pydantic-validated JSON. Whisper and Google STT backends, async with retries.

**Agents and RAG**

- **[healthcare-graph-rag-agent](https://github.com/DevDizzle/healthcare-graph-rag-agent)**: clinical Q&A over a medical knowledge graph, citation-backed. *ADK, Gemini, Spanner Graph, Cloud Run.*
- **[galatiq-invoice-agent](https://github.com/DevDizzle/galatiq-invoice-agent)**: multi-agent invoice lifecycle (ingest, validate, approve, pay) with self-correction on extraction. *LangGraph, FastAPI, Cloud Run.*
- **[serverless-pii-vault](https://github.com/DevDizzle/serverless-pii-vault)**: event-driven file storage with user isolation and irreversible PII redaction. *Cloud DLP, Vertex AI, Cloud Run.*
- **[SciPaper-Chat](https://github.com/DevDizzle/SciPaper-Chat)**: multi-document paper Q&A with citation tracking. *Vertex AI Vector Search, Gemini, Firestore.*
- **[yolov9-object-detection-guide](https://github.com/DevDizzle/yolov9-object-detection-guide)**: end-to-end guide to fine-tuning YOLOv9 on custom datasets. Written during my M.S. coursework. *PyTorch.*

## Stack

```
GenAI:      Diffusers, PEFT/LoRA, Whisper, Stable Diffusion, CLIP
ML/AI:      Vertex AI, Gemini, PyTorch, TensorFlow, Scikit-Learn
Evaluation: Sentence-Transformers, Detoxify, W&B, custom frameworks
Cloud:      GCP (BigQuery, Cloud Run, Pub/Sub, Vertex AI), Azure on client work
MLOps:      GitHub Actions, Cloud Build, Docker, model registry
Data:       Python, SQL, Pandas, dbt, Airflow
Backend:    FastAPI, Python, Node.js
Frontend:   Next.js, React, TypeScript
```

## Background

- M.S. Artificial Intelligence, Florida Atlantic University
- B.A. Economics, Florida International University
- Google Professional Machine Learning Engineer
- Google Advanced Data Analytics

## Contact

- [evanparra.ai](https://evanparra.ai)
- evan@evanparra.ai
- [linkedin.com/in/evanparra](https://linkedin.com/in/evanparra)
