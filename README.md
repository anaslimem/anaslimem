# 👋 Hi, I’m **Anas Limem**

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&pause=1200&color=00E7FF&center=true&vCenter=true&width=900&lines=AI+Engineer-in-the-Making;Turning+Math+into+Machines;RAG+%7C+MLOps+%7C+Deep+Learning;From+first+principles+to+production" alt="Typing SVG" />
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=anaslimem&label=Profile+views&color=0e75b6&style=flat-square" alt="profile views" />
  <a href="https://github.com/anaslimem?tab=followers"><img alt="followers" src="https://img.shields.io/github/followers/anaslimem?style=flat-square&color=blue" /></a>
  <img alt="location" src="https://img.shields.io/badge/Tunis-Tunisia-ff4757?style=flat-square" />
  <img alt="open to work" src="https://img.shields.io/badge/Open%20to%20Work-Yes-success?style=flat-square" />
</p>

---

## 🚀 About Me

My expertise lies in engineering production-grade AI systems, encompassing everything from foundational model development and RAG pipeline construction to deploying scalable, cloud-native applications that seamlessly integrate mathematical rigor with software craftsmanship.

- 🧠 Deep Learning, NLP, and RAG systems enthusiast
- 🛠️ From first principles (scratch-built CNNs/optimizers) to production-grade MLOps
- ☁️ Cloud-native thinker: containers, orchestration, observability
- 🤝 Open to collaborating on impactful AI products and research-driven prototypes

---

## 🌟 Featured Projects

### VectorMind AI — Personal Document Q&A Engine
Repo: https://github.com/anaslimem/VectorMind-AI  
- Built an AI app to chat with your documents using RAG
- Streamlit (frontend) + FastAPI (backend), Redis queue for async processing
- ChromaDB for vector storage, sentence-transformers for embeddings, Ollama for LLM
- Containerized with Docker, orchestrated with Kubernetes

---

### AI-Assistant-RAG — RAG-Powered Intelligent Search
Repo: https://github.com/anaslimem/AI-Assistant-RAG  
- Retrieval-Augmented Generation using ChromaDB, LangChain, and Redis
- Streamlit UI for real-time Q&A
- Response optimization and caching for near-instant answers on repeat queries

---

### Smart Article Search v2.0 — AI-Powered News Search
Repo: https://github.com/anaslimem/Smart-Article-Search  
- FastAPI backend + Streamlit frontend
- Elasticsearch for indexing and full-text search
- Dockerized and deployed via Kubernetes (Minikube), ConfigMaps & Secrets

---

### CNN-from-scratch — Pure NumPy Deep Learning
Repo: https://github.com/anaslimem/CNN-from-scratch  
- Convolution, pooling, dropout, batch norm—implemented from scratch
- Manual forward/backward passes and training loop
- Achieved 98% accuracy on MNIST without high-level DL frameworks

---

### Optimizers-from-scratch — Training Without Autograd
Repo: https://github.com/anaslimem/Optimizers-from-scratch  
- Tiny MLP with hand-written backprop and gradient checks
- Optimizers: SGD, Momentum, RMSProp, Adam, AdamW
- Learning-rate schedules: step decay, cosine, warmup (97%+ test accuracy)

---

## 🧭 How I Build AI Systems

```mermaid
flowchart TD
  U[User] --> UI[Streamlit UI]
  UI --> API[FastAPI Backend]
  subgraph Async & Compute
    API --> Q[Redis Queue]
    W1[Worker] -->|Embed| E[sentence-transformers]
    W1 -->|Index| V[(ChromaDB)]
    W2[Worker] -->|Query| V
    W2 -->|Augment| C[Context Builder]
  end
  C --> LLM[Ollama-hosted LLM]
  LLM --> API
  API --> UI
```

- Modular design with queues, workers, and vector stores
- Cloud-native deployments with Docker/Kubernetes
- Clear observability and caching layers for performance

---

## 🧰 Tech Toolbox

<p align="center">
  <h3>Languages & Scripting</h3>
  <img src="https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white&style=for-the-badge" />
  <img src="https://img.shields.io/badge/Java-007396?logo=openjdk&logoColor=white&style=for-the-badge" />
  <img src="https://img.shields.io/badge/SQL-4479A1?logo=postgresql&logoColor=white&style=for-the-badge" />
  <img src="https://img.shields.io/badge/Bash-4EAA25?logo=gnubash&logoColor=white&style=for-the-badge" />
</p>

<p align="center">
  <h3>Machine Learning & AI</h3>
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?logo=pytorch&logoColor=white&style=for-the-badge" />
  <img src="https://img.shields.io/badge/TensorFlow-FF6F00?logo=tensorflow&logoColor=white&style=for-the-badge" />
  <img src="https://img.shields.io/badge/scikit--learn-F7931E?logo=scikitlearn&logoColor=white&style=for-the-badge" />
  <img src="https://img.shields.io/badge/sentence--transformers-1E90FF?style=for-the-badge" />
  <img src="https://img.shields.io/badge/LangChain-0C8CE9?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Ollama-000000?style=for-the-badge" />
  <img src="https://img.shields.io/badge/FAISS-005F9E?style=for-the-badge" />
  <img src="https://img.shields.io/badge/ChromaDB-FF0080?style=for-the-badge" />
</p>

<p align="center">
  <h3>Data & Visualization</h3>
  <img src="https://img.shields.io/badge/Pandas-150458?logo=pandas&logoColor=white&style=for-the-badge" />
  <img src="https://img.shields.io/badge/NumPy-013243?logo=numpy&logoColor=white&style=for-the-badge" />
  <img src="https://img.shields.io/badge/Matplotlib-000000?logo=matplotlib&logoColor=white&style=for-the-badge" />
  <img src="https://img.shields.io/badge/Elasticsearch-005571?logo=elasticsearch&logoColor=white&style=for-the-badge" />
</p>

<p align="center">
  <h3>Backend & APIs</h3>
  <img src="https://img.shields.io/badge/FastAPI-009688?logo=fastapi&logoColor=white&style=for-the-badge" />
  <img src="https://img.shields.io/badge/Flask-000000?logo=flask&logoColor=white&style=for-the-badge" />
  <img src="https://img.shields.io/badge/Streamlit-FF4B4B?logo=streamlit&logoColor=white&style=for-the-badge" />
</p>

<p align="center">
  <h3>Databases & Messaging</h3>
  <img src="https://img.shields.io/badge/PostgreSQL-336791?logo=postgresql&logoColor=white&style=for-the-badge" />
  <img src="https://img.shields.io/badge/MongoDB-47A248?logo=mongodb&logoColor=white&style=for-the-badge" />
  <img src="https://img.shields.io/badge/Redis-D82C20?logo=redis&logoColor=white&style=for-the-badge" />
</p>

<p align="center">
  <h3>DevOps & Cloud</h3>
  <img src="https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white&style=for-the-badge" />
  <img src="https://img.shields.io/badge/Kubernetes-326CE5?logo=kubernetes&logoColor=white&style=for-the-badge" />
  <img src="https://img.shields.io/badge/GitHub%20Actions-2088FF?logo=githubactions&logoColor=white&style=for-the-badge" />
  <img src="https://img.shields.io/badge/Azure%20Blob%20Storage-0078D4?logo=microsoftazure&logoColor=white&style=for-the-badge" />
</p>


---

## 📚 Currently Exploring

- Reinforcement Learning (RL)
- Advanced RAG architectures and evaluation
- MLOps: experiment tracking, CI/CD for models, data versioning
- Scalable search: embeddings, hybrid retrieval, vector databases

---

## 📈 Stats & Highlights

<p align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=anaslimem&theme=radical&no-bg=true&no-frame=true&column=6" alt="trophies" />
</p>

<p align="center">
  <img src="https://streak-stats.demolab.com?user=anaslimem&theme=radical" alt="streak" />
</p>

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=anaslimem&show_icons=true&theme=radical" alt="stats" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=anaslimem&layout=compact&theme=radical" alt="top languages" />
</p>

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=anaslimem&theme=react-dark" alt="activity graph" />
</p>

---

## 🤝 Connect

<a href="https://www.linkedin.com/in/anas-limem-2b01702b1/">
  <img src="https://img.shields.io/badge/LinkedIn-0077B5?logo=linkedin&logoColor=white&style=for-the-badge" />
</a>
<a href="https://github.com/anaslimem">
  <img src="https://img.shields.io/badge/GitHub-181717?logo=github&logoColor=white&style=for-the-badge" />
</a>
<a href="http://medium.com/@limemanas0">
  <img src="https://img.shields.io/badge/Medium-12100E?logo=medium&logoColor=white&style=for-the-badge" />
</a>

---

<p align="center"><i>“The best way to learn is to build.”</i> — Let’s build something intelligent together.</p>
