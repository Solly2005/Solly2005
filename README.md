# Hi, I'm Bassil 👋

### AI Engineer · Applied ML Engineer · Software Engineer

Computer Engineering & Software Systems student at **Ain Shams University (ICHEP)**, Cairo — graduating 2027. I build production AI systems end to end: multi-agent LLM pipelines, RAG architectures, and polyglot microservices that actually ship. Equally at home in applied ML/NLP/CV and full-stack distributed backends.

- 🔭 Building multi-agent LLM systems, semantic search, and zero-trust microservices
- 🧠 Deep into deep learning, NLP, computer vision, RAG/CAG, and LLM orchestration
- 💼 Open to software & ML engineering internships and roles
- 📫  · [Email](mailto:alsafadibasil@gmail.com) · [LinkedIn](https://www.linkedin.com/in/bassil-alsafadi)

---

## 🛠️ Tech Stack

**Languages**
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=flat&logo=go&logoColor=white)
![C#](https://img.shields.io/badge/C%23-512BD4?style=flat&logo=dotnet&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![C++](https://img.shields.io/badge/C/C++-00599C?style=flat&logo=cplusplus&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat&logo=openjdk&logoColor=white)
![Dart](https://img.shields.io/badge/Dart-0175C2?style=flat&logo=dart&logoColor=white)

**AI / ML**
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat&logo=tensorflow&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat&logo=scikitlearn&logoColor=white)
![Hugging Face](https://img.shields.io/badge/🤗%20Hugging%20Face-FFD21E?style=flat&logoColor=black)
![ONNX](https://img.shields.io/badge/ONNX%20Runtime-005CED?style=flat&logo=onnx&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white)

**LLM / Agents**
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat&logo=langchain&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat&logoColor=white)
![RAG](https://img.shields.io/badge/RAG%20%2F%20CAG-412991?style=flat&logoColor=white)
![pgvector](https://img.shields.io/badge/pgvector-4169E1?style=flat&logoColor=white)
![LoRA](https://img.shields.io/badge/LoRA%20%2F%20QLoRA-EE4C2C?style=flat&logoColor=white)

**Backend & Frameworks**
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)
![.NET](https://img.shields.io/badge/.NET%209-512BD4?style=flat&logo=dotnet&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat&logo=nodedotjs&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat&logo=flask&logoColor=white)
![gRPC](https://img.shields.io/badge/gRPC%20%2F%20protobuf-244c5a?style=flat&logo=protobuf&logoColor=white)
![NATS](https://img.shields.io/badge/NATS%20JetStream-27AAE1?style=flat&logo=natsdotio&logoColor=white)

**Frontend**
![React](https://img.shields.io/badge/React-61DAFB?style=flat&logo=react&logoColor=black)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat&logo=nextdotjs&logoColor=white)
![Angular](https://img.shields.io/badge/Angular-DD0031?style=flat&logo=angular&logoColor=white)
![Flutter](https://img.shields.io/badge/Flutter-02569B?style=flat&logo=flutter&logoColor=white)

**Data & Infra**
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=flat&logo=supabase&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat&logo=mongodb&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat&logo=redis&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat&logo=vercel&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat&logo=linux&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)

---

## 🚀 Featured Projects

### 🩺 ORSA — AI Health Companion
**[Live demo](https://orsa.vercel.app)** · **[Code](https://github.com/Solly2005/Orsa)**
Production-ready AI health triage platform split into three self-contained microservices: Angular 19 client, Go orchestration gateway, and ASP.NET 9 identity engine. 7-stage clinical triage pipeline with a fine-tuned **Bio-ClinicalBERT** ONNX classifier for severity prediction, an escalate-only reconciliation safety algorithm, UMLS/SNOMED concept coding, FHIR R5 bundle generation, and multimodal analysis (PDF/images) via vision LLMs. Secured via protobuf/gRPC, HS256 JWT sessions, PBKDF2-SHA256 hashing (600k iterations), and custom CORS policies.

### 🛒 MyPal — AI-Native Microservices Marketplace
**[Code](https://github.com/Solly2005/MyPal)**
Polyglot microservices marketplace with a Go API gateway enforcing token validation, rate-limiting, request size limits, and a normalized response envelope. Distributed-systems backend with **Saga-based checkout orchestration**, the Transactional Outbox pattern, and asynchronous event streaming via NATS JetStream. AI-powered product discovery using natural-language search with vector similarity embeddings and multi-provider LLM routing. React, Go, C#/.NET 9, Node.js, Supabase, PostgreSQL (pgvector), Hugging Face.

### 👤 3D Face Recognition System
**[Code](https://github.com/Solly2005/3D-Face-Recognition)**
Deep learning spatial verification pipeline converting raw 3D scans into optimized volumetric voxel grids over the Texas 3D Face Database. **99.93% test specificity**, with post-training quantization to reduce memory footprint and speed up live inference. PyTorch, 3D CNNs.

### 🎓 University Management System (Uni SIS)
**[Code](https://github.com/Solly2005/SIS)**
Responsive university portal supporting student enrollment, dynamic course selection, and role-based access control (RBAC) across three role types (student, professor, admin). Connected Google Calendar API and OAuth 2.0 flow for automated scheduling and authenticated logins. React, TypeScript, FastAPI, PostgreSQL, Supabase.

### 🎮 Online Multiplayer Grid Clash Game
**[Code](https://github.com/Solly2005/Networks_Project)**
Concurrent multiplayer grid game powered by a custom UDP socket layer with a custom binary protocol for low-latency real-time state synchronization. Reliable communication mechanics including sequence numbers, CRC32 checksums, and ACK-based flow control on top of raw UDP. Python, concurrent server architecture, Linux.

### 🌳 Syntax Tree Visualizer
**[Code](https://github.com/Solly2005/Syntax-tree-for-mathematical-operations)**
Cross-platform desktop application parsing complex algebraic expressions and rendering interactive syntax/parse trees. Modular object-oriented architecture separating core expression Node structures, recursive ParseTree parsing algorithms, and wxWidgets UI tree panels. C++, wxWidgets, CMake.

---

## 📊 GitHub Stats

![Bassil's GitHub stats](https://github-readme-stats.vercel.app/api?username=Solly2005&show_icons=true&theme=tokyonight)
![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=Solly2005&layout=compact&theme=tokyonight&langs_count=8)
