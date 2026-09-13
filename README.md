# Hi, I'm Dafu Wu 👋

### AI Infrastructure Engineer

Building **large-scale AI infrastructure** for systems that train, reason, and improve themselves — from GPU clusters and distributed training to post-training and Agentic RL.

[![GitHub](https://img.shields.io/badge/GitHub-dafu--wu-181717?style=flat-square&logo=github)](https://github.com/dafu-wu)
![AI Infrastructure](https://img.shields.io/badge/AI-Infrastructure-blue?style=flat-square)
![Distributed Training](https://img.shields.io/badge/Distributed-Training-orange?style=flat-square)
![Agentic RL](https://img.shields.io/badge/Agentic-RL-purple?style=flat-square)

---

<img width="38%" align="right" alt="AI Infrastructure" src="https://raw.githubusercontent.com/onimur/.github/master/.resources/git-header.svg" />

### 🚀 AI Infrastructure

Designing and building infrastructure for **large-scale AI training and post-training** across heterogeneous GPU clusters — **A100, H100, and GB200**.

My work spans the full AI systems stack:

`GPU` → `Network` → `Runtime` → `Distributed Training` → `Scheduling` → `Inference`

Focused on:

- Large-scale distributed training
- GPU cluster architecture & scheduling
- NCCL / RDMA communication
- GPU utilization & MFU optimization
- Multi-node training performance & reliability
- Storage and I/O performance
- Multi-cluster resource orchestration

<br clear="right"/>

---

### ⚡ Distributed Training & Performance

Working on system-level optimization for large-scale model training across **compute, communication, memory, networking, and storage**.

`PyTorch` · `Ray` · `NCCL` · `RDMA` · `A100` · `H100` · `GB200`

Performance work includes distributed communication, GPU utilization, parallelism strategies, I/O throughput, and end-to-end training efficiency.

> **Measure first. Optimize the bottleneck, not the symptom.**

---

### ☸️ GPU Scheduling & AI Platforms

Architected a **multi-cluster scheduling system spanning 5 GPU clusters**, enabling global workload orchestration, resource pooling, and improved GPU utilization.

Reviewer & Contributor to [Volcano](https://github.com/volcano-sh/volcano) (CNCF), working on:

`Gang Scheduling` · `Capacity Scheduling` · `DRA` · `GPU Scheduling` · `Resource Management`

Building Kubernetes-native AI platforms covering the full workload lifecycle:

`Scheduling` → `Provisioning` → `Training` → `Observability` → `Recovery`

---

### 🧠 Post-Training Infrastructure

Designing a lightweight **Post-Training Platform** that gives researchers simple training primitives while abstracting distributed execution, inference, scheduling, and GPU infrastructure.

```text
Researcher
    ↓
Python SDK
    ↓
forward_backward() · optim_step() · sample() · save_state()
    ↓
Post-Training Platform
    ↓
NeMo / NeMo-RL · vLLM · Ray
    ↓
Kubernetes / Volcano
    ↓
H100 / GB200
```

Building a unified execution layer across **LLM, VLM, Speech, and RL** workloads:

`SFT` · `LoRA` · `DPO` · `GRPO` · `Sampling`

The platform centralizes:

- **Reusable training infrastructure** across research teams
- **Best-known GPU configurations** for common models and workloads
- **Validated training recipes** and performance configurations
- **Training / inference runtime management**
- **Framework capability and feature lifecycle tracking**
- **Scheduling, observability, checkpointing, and artifact management**

> **Researchers focus on models and algorithms; the platform owns distributed execution, performance, and reliability.**

---

### 🤖 Agentic RL & Inference

Building infrastructure for **Agentic RL, computer-use agents, and self-improving systems**.

Working across the closed-loop RL stack:

`Training` → `Inference` → `Sandbox` → `Environment` → `Reward` → `Training`

**RL Training**

[veRL](https://github.com/volcengine/verl) · [AReaL](https://github.com/inclusionAI/AReaL) · [NeMo-RL](https://github.com/NVIDIA/NeMo-RL)

**Inference**

[vLLM](https://github.com/vllm-project/vllm) · [SGLang](https://github.com/sgl-project/sglang)

Built scalable **OSWorld sandbox infrastructure** for closed-loop RL training of computer-use agents.

---

### 🛠️ Systems Stack

| Layer | Technologies |
| --- | --- |
| **Training** | PyTorch · Ray |
| **Post-Training / RL** | veRL · AReaL · NeMo-RL |
| **Inference** | vLLM · SGLang |
| **Communication** | NCCL · RDMA |
| **Orchestration** | Kubernetes · Volcano |
| **Compute** | A100 · H100 · GB200 |

---

### 🌱 Open Source

**[volcano-sh/volcano](https://github.com/volcano-sh/volcano)** — Reviewer & Contributor  
GPU scheduling, gang scheduling, capacity scheduling, DRA, and resource management for AI workloads.

**Agentic RL Ecosystem** — Contributor  
[veRL](https://github.com/volcengine/verl) · [AReaL](https://github.com/inclusionAI/AReaL) · [NeMo-RL](https://github.com/NVIDIA/NeMo-RL)

---

### 🔬 Current Interests

Particularly interested in the infrastructure behind **automated research and self-improving AI systems**.

`Agentic RL` · `Automated Research` · `Self-Improving Agents` · `Post-Training Infrastructure` · `Scalable Sandboxes` · `Training-Inference Co-design`

> **How do we build infrastructure that enables AI systems to continuously explore, learn, and improve at scale?**

---

**Think in systems. Measure everything. Build infrastructure that scales.**
