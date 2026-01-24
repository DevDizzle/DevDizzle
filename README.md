# Hi, I'm Evan Parra 👋

### Seasoned AI Engineer & Full-Stack Developer
**[evanparra.ai](https://evanparra.ai) | [GammaRips](https://gammarips.com)**

I specialize in building end-to-end AI systems, from serverless data pipelines to production-grade ML models. My work focuses on automating complex workflows using **Google Cloud Platform (GCP)**, **Vertex AI**, and **Large Language Models**.

---

## 🏛️ Featured Enterprise Architecture: UrbanNexus
**Governed Multi-Agent Smart City Orchestrator**
**[View Repository](https://github.com/DevDizzle/smart-city)**

UrbanNexus is an enterprise-grade decision engine designed to solve the "Black Box" problem in autonomous AI. It moves beyond simple chatbots by implementing a rigorous **"Advocate vs. Critic"** architecture, ensuring that AI-generated infrastructure proposals are safe, compliant, and hallucination-free.

**Enterprise Value & Governance:**
* **Constitutional AI Patterns:** Implements a strict "Supervisor-Worker" hierarchy where specific agents (Privacy Counsel, OT Security) act as adversarial critics to vet proposals against ingested regulatory documents (NIST, CJIS, Sunshine Laws).
* **Protocol Engineering:** Uses **Google's Agent Development Kit (ADK)** to enforce deterministic state machines. Agents cannot proceed to a "Decision" state without passing specific validation gates defined in code.
* **Auditability:** Designed for regulated industries, the system produces a full, immutable audit trail of the reasoning process, moving from unstructured reasoning to structured, defensible JSON outputs.

**Stack:** Google ADK, Gemini Pro, Vertex AI Search (RAG), FastAPI, Next.js (TypeScript), Firestore.

---

## 🏢 Production System & Venture: GammaRips
**[Live Platform](https://gammarips.com)**

I founded and built this company, architecting a fully production-grade AI financial analysis platform on Google Cloud. The system generates actionable trading signals for the Russell 1000 by automating the ingestion of financial data, analyzing it using custom ML models, and surfacing structured Call/Put setups.

**The Code Behind the Platform:**
* **[profitscout-engine](https://github.com/DevDizzle/profitscout-engine):** The serverless backend built on GCP. Handles data ingestion, pipeline orchestration, and signal generation.
* **[profitscout-models](https://github.com/DevDizzle/profitscout-models):** The ML pipeline using Vertex AI for feature engineering and training.
* **[profitscout-gpt](https://github.com/DevDizzle/profitscout-gpt):** FastAPI backend serving AI-driven financial research and summaries.

---

## 🛠 Selected Projects

### 🧠 [SciPaper-Hub (PaperRec)](https://github.com/DevDizzle/SciPaper-Hub)
**RAG & Vector Search**
A research paper recommendation engine powered by arXiv.
* **Tech:** Gemini Embeddings, Vertex AI Vector Search, Cloud Run.
* **Features:** Harvests papers from CS domains (AI, CV, RO), embeds abstracts, and serves semantic search results via API.

### 🩺 [MaculaCutis](https://github.com/DevDizzle/MaculaCutis)
**Computer Vision in Healthcare**
A dermatology second-opinion MVP designed to assist clinicians.
* **Tech:** Vertex AI AutoML Vision, SHAP (Explainable AI), Firebase.
* **Features:** Triage prototype for dermoscopic images with explainability overlays.

### 👁️ [YOLOv9 Object Detection Guide](https://github.com/DevDizzle/yolov9-object-detection-guide)
**Computer Vision Resource**
A comprehensive guide and codebase for fine-tuning YOLOv9 on custom datasets, covering everything from data preparation to inference.

---

## 💻 Tech Stack

| Domain | Tools |
| :--- | :--- |
| **AI & Orchestration** | **Google ADK**, Vertex AI, Gemini, OpenAI API, TensorFlow/Keras, PyTorch, YOLO |
| **Cloud & DevOps** | Google Cloud Platform (GCP), Cloud Run, Cloud Functions, BigQuery, Docker |
| **Backend** | Python, FastAPI, Node.js, Firebase |
| **Frontend** | React, Next.js, TypeScript, Tailwind CSS, Astro |

---

### 📫 Connect with Me
* **Hire Me:** [evanparra.ai](https://evanparra.ai)
* **LinkedIn:** [linkedin.com/in/eraphaelparra](https://linkedin.com/in/eraphaelparra)
* **Email:** [admin@evanparra.ai](mailto:admin@evanparra.ai)
