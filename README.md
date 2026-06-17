# Ali Haidar

Computer Science Graduate from FAST-NUCES. I've spent the last year building, optimizing, and deploying production-grade AI systems, agentic workflows, and MLOps pipelines.

Feel free to reach out via **p229377@pwr.nu.edu.pk** or **0341 5074527**. Based in Islamabad, Pakistan.

---

## 🚀 What I've Built

### **Pakistan Legal AI**
* **Core Architecture:** Agentic RAG system engineered for Pakistani constitutional law achieving a verified 0% hallucination rate on source documents.
* **Pipeline:** Implemented HyDE retrieval and CrossEncoder reranking (`ms-marco-MiniLM-L-6-v2`) over top-40 FAISS results. 
* **Routing:** Features autonomous routing between an LLM-driven RAG search tool and a deterministic Python tax calculator.
* **Deployment:** Built with FastAPI featuring real-time SSE (Server-Sent Events) streaming, fully containerized with Docker.

### **DocGraph**
* **Core Architecture:** Multi-container Graph-RAG and monitoring system.
* **Pipeline:** Engineered a system integrating Neo4j (Graph DB) and FAISS to handle complex structural data relationships.
* **Deployment:** Served via FastAPI with an Nginx and React frontend, featuring comprehensive production observability using Prometheus and Grafana dashboards.

### **BizScout Pakistan**
* **Core Architecture:** 5-agent LangGraph `StateGraph` system that automates business validation for Pakistani entrepreneurs.
* **Pipeline:** Market, competitor, regulatory, financial, and risk agents run with parallel and sequential execution, integrating Tavily web search and Groq (Llama 3.1).
* **Impact:** Synthesizes a comprehensive viability report and an actionable GO / NO GO recommendation in under 2 minutes.
* **Deployment:** Live on AWS EC2 via FastAPI + Streamlit with automated GitHub Actions CI/CD.

### **ClinicFlow**
* **Core Architecture:** TinyLlama 1.1B instruction fine-tuned on Pakistani medical cases using QLoRA (4-bit quantization + LoRA adapters) via TRL and Unsloth.
* **Optimization:** Slashed memory requirements by 90% (from 40GB to 4GB) by tuning only 1–2% of the parameters.
* **Impact:** Integrated Groq inference API to generate structured clinical SOAP notes in sub-700ms response times. 
* **Deployment:** Adapter weights published to HuggingFace Hub; architecture deployed on AWS EC2 using Docker and GitHub Actions CI/CD.

### **Employee Attrition Predictor (MLOps Pipeline)**
* **Core Architecture:** End-to-end Random Forest classification REST API.
* **Pipeline:** RandomForest → ONNX export → FastAPI → Multi-stage Docker image optimized to ~180MB.
* **CI/CD & Monitoring:** 27 automated pytest cases completely block bad deployments. Integrated Prometheus metrics tracking latency, error rates, and real-time production data drift against the training baseline.

### **Camouflage Object Detection** *(Final Year Project)*
* **Core Architecture:** Real-time military-grade object detection system optimized for edge hardware deployment.
* **Pipeline:** YOLOv8 nano fine-tuned for 100 epochs using transfer learning (COCO weights) and extensive data augmentation.
* **Optimization:** Tailored for edge inference on a Raspberry Pi 5. Confidence threshold intentionally tuned to 0.25 to aggressively minimize false negatives in critical defense scenarios.

---

## 🛠️ Technical Stack

* **Generative AI & NLP:** Graph-RAG, Knowledge Graphs (Neo4j), Multi-Agent Orchestration (LangGraph), LangChain, Groq, Llama 3.1, Tool-Calling, HyDE, CrossEncoder Reranking, Sentence Transformers.
* **LLM Fine-Tuning:** QLoRA, LoRA Adapters, PEFT, TRL, Unsloth, 4-bit Quantization, HuggingFace Hub.
* **ML/DL & Vision:** PyTorch, scikit-learn, XGBoost, YOLOv8, CNNs, Transfer Learning, Random Forest, Hyperparameter Tuning (GridSearchCV).
* **MLOps & DevOps:** Docker, Docker Compose, GitHub Actions CI/CD, pytest automated testing, Prometheus, Grafana, MLflow, ONNX, Nginx, Linux, AWS EC2.
* **Databases:** Neo4j, FAISS, PostgreSQL, MongoDB, Pinecone, Qdrant.
* **Backend & Tools:** Python, FastAPI, Node.js, SSE Streaming, WebSockets, BeautifulSoup4, Streamlit, React.

---

## 📜 Certifications

* **Anthropic** — Introduction to Model Context Protocol (MCP)
* **Kaggle** — Python, Intro to Machine Learning, Intermediate Machine Learning
* **GeeksforGeeks** — SQL & MongoDB Overview

---

## 💼 Currently

* Freelancing as an AI/ML Engineer building enterprise RAG pipelines, fine-tuning setups, and automated MLOps infrastructure for global clients.
* Open to **Machine Learning Engineer** / **AI Developer** roles — Remote, or Onsite in Islamabad / Rawalpindi / Lahore.
