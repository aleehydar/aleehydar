# Ali Haidar

Final-semester CS student at FAST-NUCES (graduating May 2026). 
I've spent the last year building and deploying real AI systems 
while finishing my degree.

## What I've built

**Pakistan Legal AI** — Agentic RAG system for Pakistani 
constitutional law. HyDE retrieval + CrossEncoder reranking over 
FAISS + LLM that routes autonomously between a RAG search tool and 
a Python tax calculator. Zero hallucination rate on source 
documents. FastAPI with real-time SSE streaming, Dockerized.

**BizScout Pakistan** — 5-agent LangGraph system that validates 
business ideas for Pakistani entrepreneurs. Market, competitor, 
regulatory, financial, and risk agents run in parallel; a risk 
agent synthesizes everything into a viability score and GO / NO GO 
recommendation. Full report in under 2 minutes. Live on AWS EC2.

**ClinicFlow** — TinyLlama 1.1B fine-tuned with QLoRA on Pakistani 
medical cases. 4-bit quantization brought memory from 40GB to 4GB, 
training only 1–2% of parameters. Generates structured SOAP notes 
in under 700ms. Live on EC2.

**MLOps Pipeline** — RandomForest → ONNX → FastAPI → Docker → 
GitHub Actions → EC2. 27 pytest cases block bad deployments. 
Prometheus tracking latency, error rate, and data drift against 
training baseline.

**Camouflage Object Detection** *(FYP)* — YOLOv8 nano running 
real-time inference on Raspberry Pi 5. Confidence threshold set to 
0.25 — a deliberate call given the cost of false negatives in 
military applications.

## Stack

Python · PyTorch · LangGraph · LangChain · QLoRA/PEFT · FAISS · 
Groq · HuggingFace · YOLOv8 · FastAPI · Docker · AWS EC2 · 
GitHub Actions · ONNX · Prometheus

## Certifications

Anthropic — Model Context Protocol (MCP)  
Kaggle — Python, Intro to ML, Intermediate ML  

## Currently

Freelancing on RAG pipelines, fine-tuning, and ML infrastructure 
for clients in healthcare and legal. Open to ML Engineer / AI 
Developer roles — remote or Islamabad / Rawalpindi / Lahore.
