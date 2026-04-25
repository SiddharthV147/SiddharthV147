<div align="center">

# Siddharth Varade

**I love building stuff :)**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/siddharth-varade/)
[![LeetCode](https://img.shields.io/badge/LeetCode-FFA116?style=flat&logo=leetcode&logoColor=white)](https://leetcode.com/u/siddharth_varade/)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white)](https://github.com/SiddharthV147/)

</div>

---

## About Me

Final-year Computer Engineering student at JSPM's BSIOTR, Pune — targeting SDE and ML Engineering roles at top-tier product companies.

I work across the full depth of the stack: from designing distributed backend systems in Java and C++ to building and deploying ML pipelines with real performance constraints. My interests lean toward **systems programming**, **ML infrastructure**, and **high-throughput backend engineering** — areas where correctness and performance both matter.

- Merged a PR to **Intel's OpenVINO** (C++ systems, PyTorch model conversion pipeline)
- Contributed to **Google's Keras**
- Strong DSA fundamentals — **LeetCode rating: 1808**

---

## Tech Stack

**Languages**
`C++` `Python` `Java` `JavaScript` `SQL`

**Backend & Systems**
`Spring Boot` `FastAPI` `POSIX Sockets` `Redis` `Docker` `Linux` `Bash`

**AI / ML**
`PyTorch` `TensorFlow` `HuggingFace Transformers` `Sentence-Transformers`
`ONNX` `TensorRT` `OpenCV` `YOLOv11` `Scikit-learn`

**Databases & Infra**
`PostgreSQL` `MongoDB` `Milvus (HNSW)` `Redis pub/sub`

**Tools**
`Git` `Postman` `Pytest` `JUnit`

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

**JASWIN AI Solutions — Backend & ML Engineering Intern**
Built the FastAPI-based LMS backend and led the semantic caching system from architecture to IEEE paper.

**True Data Software — Computer Vision Intern**
Delivered a production YOLOv8 + WebSocket visual inspection pipeline for a real industrial client.

**Open Source**
- Merged PR [#21231](https://github.com/openvinotoolkit/openvino) to **Intel OpenVINO** — PyTorch model conversion in a C++ inference pipeline
- Contributor to **Google Keras**

**Shipped**
- **RamdasiBana** — Production Android app, live on the Play Store

---

## GitHub Stats

<div align="center">

![Siddharth's GitHub Stats](https://github-readme-stats.vercel.app/api?username=SiddharthV147&show_icons=true&theme=github_dark&hide_border=true&include_all_commits=true&count_private=true)
![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=SiddharthV147&layout=compact&theme=github_dark&hide_border=true)

</div>

---

<div align="center">

*I build things that are correct, fast, and production-ready. Let's connect.*

</div>
