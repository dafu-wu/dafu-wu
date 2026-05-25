# Dafu Wu

**AI Infrastructure Engineer**

Building the systems that make large-scale AI possible — from LLM training clusters to agentic RL training and inference infrastructure.

---

## What I Work On

**Large-scale LLM Training Infrastructure**
Led end-to-end design and implementation of cloud-native AI training infrastructure from the ground up, supporting large-scale distributed training across heterogeneous GPU clusters (A100, H100, GB200). Integrated GPU scheduling, high-performance networking, and distributed training frameworks (PyTorch, Ray), achieving high cluster MFU. Drove system-level performance optimization across compute, networking, and storage layers, addressing bottlenecks in NCCL communication, GPU utilization, and I/O throughput in multi-node environments.

**GPU Cluster Scheduling & Kubernetes Native AI Platforms**
Architected a multi-cluster scheduling system spanning 5 GPU clusters, enabling cross-cluster workload orchestration, resource pooling, and improved global utilization. Reviewer and contributor to [Volcano](https://github.com/volcano-sh/volcano) (CNCF), with contributions to gang scheduling, capacity plugin correctness, and DRA resource management. End-to-end ML platform design on Kubernetes: job lifecycle management, GPU affinity, multi-tenancy, autoscaling, and observability.

**Agentic RL & Inference Infrastructure**
Infrastructure for agentic RL training and inference. Integrated RL training frameworks (veRL, AReaL, NeMo-RL) and high-throughput inference engines (vLLM, SGLang) into production platforms. Built a pluggable OSWorld sandbox provider on the training platform, enabling closed-loop RL training pipelines for computer-use agents at scale.

---

## Technical Stack

| Layer | Technologies |
|---|---|
| Training Frameworks | PyTorch, Ray |
| RL Training | veRL, AReaL, NeMo-RL |
| Inference | vLLM, SGLang |
| Distributed | NCCL |
| Orchestration | Kubernetes, Volcano |
| Hardware | A100, H100, GB200 |

---

## Principles

- **Systems thinking first** — AI infrastructure requires deep understanding of the full stack: hardware, networking, runtime, and model architecture.
- **Measure before optimizing** — bottlenecks in distributed training are rarely where intuition suggests. Profile first, optimize second.

---

## Open Source

- **[volcano-sh/volcano](https://github.com/volcano-sh/volcano)** — Reviewer & Contributor. Core focus on GPU scheduling correctness and scalability for AI workloads.
- **[volcengine/verl](https://github.com/volcengine/verl)** · **[inclusionAI/AReaL](https://github.com/inclusionAI/AReaL)** · **[NVIDIA/NeMo-RL](https://github.com/NVIDIA/NeMo-RL)** — Contributor. Agentic RL training infrastructure and inference backend stability.

---

## Interests

Particularly drawn to **automated research** and **self-improving agents** — systems that can autonomously explore, experiment, and refine themselves. Interested in the infrastructure challenges these workloads introduce: long-horizon task execution, scalable sandbox environments, and tight feedback loops between inference and training.

---

## Contact

[GitHub](https://github.com/dafu-wu)
