<h1 align="center">John Tenkorang Anim</h1>

<p align="center">
  <b>AI/ML engineering — training pipelines, agent systems, and the infrastructure that serves them</b><br>
  Information Science @ Cornell · SWE Intern @ Microsoft CoreAI
</p>

<p align="center">
  <a href="https://linkedin.com/in/john-anim"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="mailto:ja857@cornell.edu"><img src="https://img.shields.io/badge/Email-24292F?style=flat-square&logo=gmail&logoColor=white" alt="Email"></a>
  <a href="https://github.com/John-Tenkorang-Anim"><img src="https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white" alt="GitHub"></a>
</p>

---

## About

I build machine learning systems end to end — data pipelines, model training, retrieval, agent loops — and the serving infrastructure underneath them. My interest sits where the two meet: a model is only as good as the system that runs it, and when that system is slow or wrong I want to know exactly which stage is responsible. I learn by implementing things from scratch first, then reaching for the production library.

- **Prev** — SWE intern at Microsoft CoreAI, working on evaluation and regression tooling for LLM agent systems.
- **Building** — three systems that give sequence models and reinforcement learning real jobs rather than decorative ones. Each one has to beat a simple baseline or the result gets published anyway.
- **Interested in** — inference efficiency (KV caching, batching, quantization), retrieval and agent architectures, evaluation of nondeterministic systems, and making this class of infrastructure practical in African institutional contexts.

## Tech

| | |
|---|---|
| **Languages** | ![Rust](https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white) ![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white) ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white) ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white) |
| **Systems** | ![gRPC](https://img.shields.io/badge/gRPC-244C5A?style=flat-square&logo=grpc&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) ![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white) ![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black) · Raft & quorum consensus |
| **Data & ML** | ![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white) ![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white) ![Postgres](https://img.shields.io/badge/Postgres-4169E1?style=flat-square&logo=postgresql&logoColor=white) ![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white) |

## In progress
SceneSeek is an AI-powered video search engine that enables users to find specific scenes and moments in videos using natural language. Instead of relying on titles, hashtags, or manually assigned metadata, SceneSeek combines computer vision, speech recognition, and semantic search to understand video content and retrieve relevant moments based on a user's description.

The project explores multimodal AI, vector search, and scalable backend systems to build an intelligent, efficient, and intuitive video discovery experience.

## Shipped
### [PharmaBoard](https://github.com/John-Tenkorang-Anim/pharmaboard)
![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white) ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white) ![Postgres](https://img.shields.io/badge/Postgres-4169E1?style=flat-square&logo=postgresql&logoColor=white)

Trusted communications platform for Ghana's pharmacy profession. A published notice's audience is frozen in a single transaction and never silently edited — the one guarantee the whole modular Go backend exists to protect. Verified identity, a two-person approval workflow, and an RxForum with Reddit-style communities. Deployed on Render + Vercel.


### [Pulse](https://github.com/John-Tenkorang-Anim/Pulse)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)

Distributed TCP health-check daemon. Checker nodes vote on liveness through quorum consensus, so a single bad vantage point can't declare a false outage. Anomaly detection runs on a backpropagation network written from scratch — no ML dependencies. Deployed on Render.

### [GalamseyWatch](https://github.com/John-Tenkorang-Anim/GalamseyWatch)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)

Change detection over Sentinel-2 satellite imagery to flag illegal mining sites in Ghana, turning a manual monitoring problem into a repeatable pipeline.

### [MedLens AI](https://github.com/John-Tenkorang-Anim/medlens-ai)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)

ResNet-18 pneumonia classifier with Grad-CAM overlays, so every prediction ships with the region of the X-ray that drove it. Deployed on Hugging Face.

### [CodeDoc Analyst Pro](https://github.com/John-Tenkorang-Anim/codedoc-analyst-pro)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white) ![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)

Code analysis service over GPT-4: documentation generation, refactor suggestions, test scaffolding, and complexity analysis behind one API.
