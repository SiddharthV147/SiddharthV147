<div align="center">

# Siddharth Varade

**I love building stuff :)**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/siddharth-varade/)
[![LeetCode](https://img.shields.io/badge/LeetCode-FFA116?style=flat&logo=leetcode&logoColor=white)](https://leetcode.com/u/siddharth_varade/)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white)](https://github.com/SiddharthV147/)

</div>

---

## About Me

Final-year Computer Engineering student at JSPM's BSIOTR, Pune — targeting SDE and ML Engineering roles.

I work across the full depth of the stack: from designing distributed backend systems in Java and C++ to building and deploying ML pipelines with real performance constraints. My interests lean toward **high-throughput backend engineering**, **AI/ML** and **systems programming** — areas where correctness and performance both matter.

- Contributed to **Google's Keras**
- Merged a PR to **Intel's OpenVINO** (C++ systems, PyTorch model conversion pipeline)
- Strong DSA fundamentals — **LeetCode rating: 1808**

---

## Tech Stack

**Languages**

![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)

**Backend & Systems**

![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnubash&logoColor=white)

**AI / ML**

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white)
![ONNX](https://img.shields.io/badge/ONNX-005CED?style=for-the-badge&logo=onnx&logoColor=white)
![scikit-learn](https://img.shields.io/badge/Scikit--Learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white)

**Databases & Infra**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)
![Milvus](https://img.shields.io/badge/Milvus-00A1EA?style=for-the-badge&logo=milvus&logoColor=white)

**Tools**

![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white)
![Pytest](https://img.shields.io/badge/Pytest-0A9EDC?style=for-the-badge&logo=pytest&logoColor=white)
![JUnit](https://img.shields.io/badge/JUnit5-25A162?style=for-the-badge&logo=junit5&logoColor=white)

**Coursework**

Operating Systems · DBMS · Computer Networks · Distributed Systems
---

## Featured Projects

### Collaborative Code Editor
**The problem:** Real-time collaborative editing requires conflict-free, order-independent operation merging across concurrent users.

**What I built:** A distributed collaborative editor implementing Operational Transformation (OT) from scratch in a Java Maven multi-module architecture. Backend handles concurrent edits via WebSocket STOMP with Redis pub/sub fan-out. Frontend uses Monaco Editor.

**Stack:** Java 21 · Spring Boot · WebSocket (STOMP) · Redis · React · Monaco Editor  
**Engineering focus:** Pure OT engine as a standalone `ot-engine` module, tested independently before integration.

---

### Privacy-Focused Semantic Caching System for LLM Chatbots
**The problem:** LLM-powered educational chatbots repeat expensive API calls for semantically identical queries, with no isolation between courses.

**What I built:** A two-tier caching layer — Redis for exact-match and Milvus (HNSW indexing) for semantic similarity — integrated with a RAG pipeline. Course-level privacy isolation is enforced through Milvus storage partitions. Added a five-checkpoint prompt injection defense pipeline: rule-based firewall → DeBERTa-v3-base classifier → structured prompt boundaries → document scanner → output validator.

**Stack:** Python · Milvus · Redis · HuggingFace · DeBERTa-v3 · FastAPI  
**Context:** Final Year Project under JASWIN AI Solutions. IEEE conference paper produced.

---

### HTTP/1.1 Server — From Scratch in C++
**The problem:** Understanding HTTP at the systems level requires building it without abstractions.

**What I built:** A fully functional HTTP/1.1 server using raw POSIX sockets — supporting chunked file transfer, persistent connections, and proper request parsing. No third-party networking libraries.

**Stack:** C++ · POSIX Sockets · Linux  
**Why it matters:** Demonstrates systems-level thinking: manual memory management, socket lifecycle, protocol compliance.

---

## Current Focus

- **Collaborative Systems** — Deepening understanding of OT and CRDTs for distributed editing
- **ML Infrastructure** — Exploring LLM tooling for niche hardware description languages (Verilog-AMS), LSP design, and RL-based code generation
- **Systems Engineering** — C++ performance, low-level networking, and compiler/runtime internals

---

## Experience & Highlights

**JASWIN AI Solutions — SDE Intern**
Built polyglot microservices (Spring Boot/FastAPI) for an LMS backend and engineered a real-time YouTube Analytics ingestion pipeline feeding a multi-tenant engagement dashboard.

**True Data Software — ML Engineering Intern**
Fine-tuned YOLOv11 on a custom defect dataset (98.8% accuracy), optimized inference to sub-50ms via ONNX + TensorRT, and delivered a FastAPI + React dashboard with <1s data refresh for factory floor monitoring.

**Open Source**
- Merged PR [#21231](https://github.com/keras-team/keras/pull/21231) to **Intel OpenVINO** — PyTorch model conversion in a C++ inference pipeline
- Contributor to **Google Keras**

---

## GitHub Stats

<div align="center">
  
![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=SiddharthV147&layout=compact&theme=github_dark&hide_border=true)

</div>

---

<div align="center">

*I build things that are correct, fast, and production-ready. Let's connect.*

</div>
