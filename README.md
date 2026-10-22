<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=hamzafarha&show_icons=true&theme=tokyonight&hide_border=true&count_private=true&include_all_commits=true" />
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=hamzafarha&layout=compact&theme=tokyonight&hide_border=true" />

<p>
  <a href="https://github.com/hamzafarha"><img src="https://img.shields.io/badge/GitHub-Profile-181717?style=for-the-badge&logo=github" alt="GitHub profile"/></a>
  <a href="https://www.linkedin.com/in/hamzafarhani"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin" alt="LinkedIn"/></a>
  <a href="mailto:hamza.farhani@esprit.tn"><img src="https://img.shields.io/badge/Email-Contact-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
</p>

**I build practical AI systems — from machine learning pipelines to LLM-powered applications.**

</div>

## 👋 About Me

I'm a **Data Science Engineering student at [ESPRIT](https://www.esprit.tn/), Tunisia**, interested in turning data and AI research into useful, reliable software.

My focus spans the end-to-end AI lifecycle: data preparation, model training and evaluation, retrieval-augmented generation (RAG), agent workflows, APIs, testing, and deployment. I enjoy projects where solid ML foundations meet real software engineering.

- 🤖 **AI & GenAI:** LLM applications, RAG, tool-using agents, semantic search, and model fine-tuning
- 📊 **Machine Learning:** feature engineering, model evaluation, forecasting, classification, and explainability
- ⚙️ **MLOps & deployment:** reproducible pipelines, Docker, APIs, CI/CD, experiment tracking, and testing
- 🎓 **Currently exploring:** agentic systems, evaluation, and production-minded AI engineering
- 🌍 Based in Tunisia · French and English

## 🚀 Featured Projects

### 1. AI Recruitment Automation
[**Repository →**](https://github.com/hamzafarha/ai-recruitment-automation)

An AI-assisted recruitment workflow that processes CVs, extracts structured candidate profiles, retrieves evidence for job requirements, and generates evidence-backed screening reports. Human recruiters retain responsibility for the final decision.

**Highlights**
- LangGraph screening workflow and retrieval-augmented generation over CV evidence and HR rules
- QLoRA fine-tuning workflow for Qwen models, document parsing, OCR, embeddings, and reranking
- FastAPI, React, PostgreSQL, Qdrant, MLflow, and Docker-based services

`Python` `Transformers` `QLoRA` `LangGraph` `RAG` `Qdrant` `FastAPI` `PostgreSQL` `React` `MLflow`

### 2. QoSentry — AI Intelligence for Network Supervision
**Team project · AI Intelligence Layer**

A network-supervision platform where the AI layer supports SLA-breach prediction, anomaly detection, incident investigation, and explainability. The project combines predictive ML with retrieval-augmented generation to help turn network telemetry into actionable operational insights.

**Highlights**
- Predictive models for SLA-breach risk and anomaly detection
- LangGraph + Qdrant RAG workflow for incident-oriented knowledge retrieval and reporting
- SHAP-based model explainability within a broader microservices platform

`PyTorch` `Anomaly Detection` `Time-Series / Telemetry` `LangGraph` `Qdrant` `FastAPI` `SHAP` `Docker`

*Public repository/demo link can be added when available.*

### 3. CallVerse — E-commerce Customer-Service Digital Twin
[**Repository →**](https://github.com/hamzafarha/CallVerse)

A simulation and optimization platform for an e-commerce customer-contact center. It connects demand forecasting, discrete-event simulation, agent policies, evaluation, and an interactive operations dashboard.

**Highlights**
- SimPy-based simulation of customer contacts, queues, resources, and scenarios
- Advisor copilot with RAG/tools, quality review, and reinforcement-learning workforce policies
- Local-first design with no mandatory external LLM API

`Python` `Forecasting` `SimPy` `Agentic AI` `RAG` `Reinforcement Learning` `FastAPI` `Streamlit`

### 4. FleetIQ — Smart Taxi Arrival-Time Estimation
[**Repository →**](https://github.com/hamzafarha/FleetIQ)

A production-oriented ETA prediction project for a taxi dispatch context. The current prototype uses public NYC taxi data while keeping the pipeline adaptable to future company data.

**Highlights**
- Data audit and cleaning workflow with explicit data contracts
- Planned time-aware validation and benchmarking of tabular ML models
- FastAPI inference service and real-time ride-stream simulation

`Python` `Pandas` `Scikit-learn` `XGBoost` `LightGBM` `CatBoost` `FastAPI` `Docker`

### 5. Housing Price Prediction — End-to-End ML
[**Repository →**](https://github.com/hamzafarha/Housing-Price-Prediction)

An end-to-end housing-price regression system with modular feature, training, evaluation, inference, and batch pipelines, plus an API and interactive dashboard.

**Highlights**
- XGBoost training and Optuna hyperparameter tuning with MLflow tracking
- FastAPI prediction service and Streamlit dashboard
- Docker containers, GitHub Actions CI/CD, and AWS S3, ECR, and ECS deployment configuration
- Time-based data splits and safeguards against data leakage

`Python` `XGBoost` `Scikit-learn` `Optuna` `MLflow` `FastAPI` `Streamlit` `Docker` `AWS`

### 6. Show, Attend and Tell — Image Captioning
[**Repository →**](https://github.com/hamzafarha/show-attend-tell-implementation)

A PyTorch implementation of the *Show, Attend and Tell* image-captioning paper, exploring visual attention and the relationship between computer vision and language generation.

`PyTorch` `Deep Learning` `Computer Vision` `Attention`

### 7. Breast-Cancer Classification with Transformers & XAI
[**Repository →**](https://github.com/hamzafarha/breast-cancer-transformers-xai)

A deep-learning project exploring breast-ultrasound image classification with Vision Transformers, Swin Transformers, and explainable-AI methods on the BUSI dataset.

`PyTorch` `Vision Transformers` `Swin Transformer` `Computer Vision` `Explainable AI`

## 🧰 Technical Skills

| Area | Technologies |
|---|---|
| **Languages & data** | Python, SQL, Pandas, NumPy |
| **Machine learning** | Scikit-learn, XGBoost, LightGBM, CatBoost, Optuna |
| **Deep learning** | PyTorch, Transformers, computer vision, attention mechanisms |
| **LLMs & retrieval** | LangGraph, RAG, Qdrant, Sentence Transformers, reranking, QLoRA, Ollama |
| **Backend & apps** | FastAPI, Streamlit, REST APIs |
| **Data stores** | PostgreSQL, Redis |
| **MLOps & engineering** | MLflow, Docker, GitHub Actions, pytest, CI/CD |
| **Cloud & observability** | AWS (S3, ECR, ECS), Prometheus, Grafana |

## 🧪 How I Approach AI Projects

- **Data first:** inspect data quality, define schemas, and prevent leakage.
- **Measure performance:** use suitable baselines, validation strategies, and task-specific metrics.
- **Build for reuse:** keep data, training, evaluation, and inference code modular.
- **Make outputs explainable:** ground LLM responses in evidence and use explainability tools where appropriate.
- **Engineer for delivery:** test components, containerize services, document setup, and automate checks.

## 🎓 Certifications

- NVIDIA — Deep Learning
- NVIDIA — Anomaly Detection

*Add the official credential links here when available.*

## 🤝 Let's Connect

I'm interested in **AI / Data Science internships, end-to-end ML projects, LLM applications, and AI engineering opportunities**.

- 💼 [LinkedIn](https://www.linkedin.com/in/hamzafarhani)
- 🐙 [GitHub repositories](https://github.com/hamzafarha?tab=repositories)
- ✉️ [Email](mailto:hamza.farhani@esprit.tn)

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f172a,50:1d4ed8,100:38bdf8&height=100&section=footer" width="100%" alt=""/>

</div>
