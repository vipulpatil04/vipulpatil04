# Hi, I'm Vipul Patil 👋

**Site Reliability Engineer turned AI Infrastructure Engineer.**
I spent nearly three years keeping enterprise backup clusters running for 100+ customers. Now I build the systems that make AI work at scale: distributed RAG pipelines, vector search, streaming ML and GPU inference at the edge.

🎓 M.S. Computer Science @ **University of Illinois Chicago** (2025 – 2027)
🔬 Graduate Student Intern @ **Argonne National Laboratory**, ALCF (Summer 2026)
🌐 [Portfolio](https://vipulpatil04.github.io) · [LinkedIn](https://linkedin.com/in/vipulpatil04) · vpati@uic.edu

---

## 🧭 My Journey

```
2018 ──► B.Tech Computer Engineering (Honors: Data Science), Savitribai Phule Pune University
2022 ──► Site Reliability Engineer @ Veritas Technologies (now Cohesity), until Dec 2024
2025 ──► M.S. Computer Science @ UIC: distributed systems, vector DBs, MLOps, edge, security
2026 ──► Graduate Student Intern @ Argonne National Laboratory (ALCF Polaris supercomputer)
2027 ──► 🎯 Graduating May 2027, open to AI Infra / SRE / Platform roles
```

## 🔬 Argonne National Laboratory: ALCF (Summer 2026)

- Benchmarked vector databases (**LanceDB, Milvus, Qdrant**) for multimodal approximate nearest-neighbor search on the **Polaris supercomputer**
- Designed large-scale experiments with LanceDB, PyTorch and multimodal embeddings to analyze **HNSW and IVF** indexing performance for AI/HPC workloads

## 🚀 Featured Projects

| Project | What it does | Stack |
|---|---|---|
| **RAG Index Builder** | Distributed MapReduce pipeline: PDF extraction → sentence-aware sliding-window chunking → 1024-d embeddings → sharded Lucene HNSW vector indexes | Scala 3, Hadoop MapReduce, Lucene, PDFBox, Ollama |
| [**Incremental RAG**](https://github.com/vipulpatil04/CS441-HW2-Incremental-RAG) | Follow-up to the RAG Index Builder: updates the index incrementally instead of rebuilding from scratch | Scala |
| [**BigVectorBench**](https://github.com/vipulpatil04/BigVectorBench) | Vector database benchmarking | Python |
| **Edge Vehicle Counting** _(repo coming soon)_ | GPU-accelerated YOLOv8 pipeline, containerized with Docker Compose on NVIDIA Jetson Thor | Docker, YOLOv8, CUDA 13, JetPack 7 |
| **Edge AI Profiling** _(repo coming soon)_ | Per-phase inference latency and CPU/GPU/memory profiling on Jetson Thor | Python, jtop, nvidia-smi |
| [**ML in Production: Kafka Lab**](https://github.com/vipulpatil04/mlip-kafka-lab) | Streaming data pipeline for production ML systems | Kafka, Python |

## 📚 Graduate Coursework (UIC)

| Area | Course |
|---|---|
| ☁️ Distributed Systems | CS 441: Engineering Distributed Objects for Cloud Computing |
| 🧠 Vector DBs | CS 594: Vector Databases |
| 🏭 MLOps | CS 544: Machine Learning in Production |
| 📡 Edge | CS 494: Edge Computing |
| 🌐 Web | CS 484: Secure Web Application Development |
| 🔐 Security | CS 587: Computer Systems Security |
| 🧮 Theory | CS 401: Computer Algorithms |

## 🛠️ Tech Stack

**Languages:** Scala · Python · JavaScript · Bash · Rust
**AI / Data:** RAG · PyTorch · LanceDB · Milvus · Qdrant · Lucene HNSW · Ollama · YOLOv8 · OpenCV · Kafka · RabbitMQ
**Cloud & Infra:** AWS (ECS, EKS, Lambda, DynamoDB, RDS) · Docker · Kubernetes · Helm · CI/CD · Linux
**Edge / HPC:** NVIDIA Jetson Thor · CUDA · ALCF Polaris
**Web:** React · Node.js · Express · gRPC · PostgreSQL

## 💼 SRE Roots: Veritas Technologies (now Cohesity), 2022 – 2024

- Led root-cause analysis of critical backup and cluster failures for **100+ enterprise clients** using failover-cluster logs, tcpdump traces and system metrics
- Delivered **20–25% throughput gains** by tuning storage, network and compute bottlenecks
- Automated diagnostics and log aggregation with Bash, Python and PowerShell: **40% less manual work, 30% faster incident resolution**
- Delivered **10+ technical sessions** on Veritas NetBackup
