# Yaroslav "Yar" Mikhaylik

**Senior Software Engineer - AI/ML Infrastructure & Systems**
LLM serving (vLLM), compilers, distributed systems.

I build the layer that makes AI systems actually run in production: model
serving, evaluation and quantization harnesses, infrastructure-as-code, and
the distributed/low-level systems underneath. CTO-level ownership from silicon
to org chart - I have shipped from JIT operator compilers on ARM big-data
chips up through whole product platforms and the teams that build them.

- Based in Ottawa, ON, Canada. Remote-first; open to relocation (TN-eligible).
- BSc, Computer Science and Mathematics (Joint Honours), University of Manitoba.
- i@yar.sh - [yar.sh](https://yar.sh) - [LinkedIn](https://www.linkedin.com/in/yaroslav-mikhaylik/)

## What I work on

- **LLM serving / inference.** Production vLLM pipelines with Vertex/Gemini
  fallback, token-length routing, per-request model override, and TensorRT-LLM
  recompilation for faster inference. LangGraph workflows on top.
- **ML evaluation & quantization.** Eval and quantization harnesses across many
  serving configs and benchmark types, multilingual quality (lm-eval-harness),
  W4A16 down to W2A16 / AWQ matrices, LLM-as-judge, reproducible timestamped runs.
- **Infrastructure & distributed systems.** Terraform IaC with tiered IAM and
  managed secrets, dev/prod parity, multi-cloud over WireGuard, gateway and load
  balancer consolidation, GitOps. NixOS fleets, OpenBao secrets, hardware-key trust.
- **Compilers & low level.** JIT operator compilation with PGO and realtime
  counters (OmniRuntime), trusted execution environments for petabyte-scale
  big-data on ARM, graph-based ANN vector indexes (patent-pending).

## Experience

| Company | Role | When |
| --- | --- | --- |
| Inkast | CTO (earlier: Backend/Infra Dev) | 2026-present (2022-2024) |
| Solant | CTO & AI/ML Engineer | 2025-2026 |
| Ford Motor Company | Software Engineer | 2024-2025 |
| Huawei Technologies Canada | Big Data Engineer | 2023-2024 |
| FarmLink Marketing Solutions | Software Developer | 2020-2022 |
| Cogmation Robotics | Software Developer | 2021 |

Highlights: at Solant, led the technical side of an ~11-person org and built a
production LLM pipeline end to end (self-hosted vLLM + cloud fallback,
TensorRT-LLM recompilation for +12% tok/sec) plus a full eval/quantization
harness and a single-repo Terraform source of truth. At Ford, built an
AUTOSAR-compatible logging API for an AOSP vehicle platform across multiple ECU
nodes over Ethernet and CAN, within tight flash constraints, for warranty
diagnostics. At Huawei, worked on a TEE for big-data on Huawei ARM chips, JIT
operator compilation (OmniRuntime), and graph-based ANN vector indexes.

## Proof of work

The unfakeable layer - things I built because I wanted them to exist:

- **clusterstuck** - a self-built multi-machine AI agent swarm on a secure
  NixOS fleet: OpenBao secrets, Nitrokey-3 hardware-key trust model, Forgejo
  GitOps, capability-routed agent personas.
- **Censorship-resistant networking** - an anti-censorship VPN transport
  (Reality / xHTTP / CDN) for hostile network environments.
- **AI-focused filesystem concept** - per-file embeddings instead of many
  per-project vector databases.
- **Games & reverse engineering** - 9 Ludum Dare entries (ship-under-pressure),
  a Steins;Gate PSP English patch (C++ ROM hacking), Criware reverse-engineering
  tools, and an osu! file parser. See [yar.sh](https://yar.sh) for the full junkyard.

## Publication

"Development of a Convolutional Neural Network for Defining a Renal Pathology
Using Computed Tomography Images" - Kabachenko F., Samarina A., Mikhaylik Y. -
Studies in Computational Intelligence, 2022.

## Tech

LLVM - C/C++ - Python - TypeScript - CUDA - vLLM - TensorRT-LLM - PyTorch -
TensorFlow - distributed systems - Terraform - Docker - Kubernetes - GCP -
PostgreSQL - vector databases - Apache Spark - Hadoop - HPC - Django - NixOS.
