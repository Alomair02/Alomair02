# Abdulaziz Alomair

Computer engineer. I start from a domain's real constraints, model the problem to fit them, then build down the stack until it runs in production.

Right now that means teaching and running GPU workloads at **KAUST Academy**, and building trading and reserving systems on the side.

- 🌐 Portfolio — [alomair02.github.io/Mou](https://alomair02.github.io/Mou)
- 💼 LinkedIn — [in/abdulazizom](https://www.linkedin.com/in/abdulazizom)
- ✉️ abdulaziz.t.alomair@gmail.com

---

## Stack

| | |
|---|---|
| **Languages** | Go · Python · TypeScript · Swift · C/C++ · Java · SQL · Bash |
| **Backend** | Gin · GORM · PostgreSQL · SQLAlchemy · Alembic · Next.js · React 19 |
| **Infrastructure** | Docker · Kubernetes & Helm · nginx · GCP · AWS · GitHub Actions · SLURM |
| **Observability** | OpenTelemetry · Prometheus |
| **AI / ML** | PyTorch · Transformers · vLLM · llama.cpp · LoRA & quantization · multi-modal RAG · agent tooling |
| **Compute** | ROCm / HIP · CUDA-class GPU kernels · HPC job orchestration on IBEX |
| **Data** | pandas · NumPy · XGBoost · walk-forward & blocked CV · Monte Carlo simulation |

---

## Background

**KAUST Academy** — Teaching Assistant & Professional Trainer, Data Science & AI/ML · *Jun 2026 – Present*
Run accelerated training and fine-tuning workloads on IBEX, KAUST's HPC cluster; built SLURM job automation and user-side observability for multi-node GPU jobs. Partner with KAUST consultants on an enterprise AI-transformation engagement.

**Flybee** — Founder & Software Engineer · *Sep 2025 – May 2026*
Owned an AI travel platform end to end: ~80k lines of Go across 47 packages, 74 schema migrations, JWT auth and RBAC, containerized services behind nginx on GCP. Built FlyHive, a multi-provider agent layer with hand-rolled HTTP clients and a tool-calling loop — no vendor SDKs. Shipped both clients: native iOS in SwiftUI, and a React + TypeScript admin SPA.

**Schneider Electric** — R&D Intern, Distributed Systems · *Aug 2025 – Dec 2025*
Deployed Eclipse Symphony on Kubernetes as a declarative orchestration control plane for heterogeneous automation targets. Modeled IEC 61499 components for IT/OT integration across two deployments.

**KAUST Academy** — Teaching Assistant, Deep Learning · *Jun 2025 – Sep 2025*
Built and delivered coursework across NLP and CV modules; advised 10+ teams through scoping and delivery.

**Education**
- **KFUPM** — BSc Computer Engineering, Honors · *2021 – 2026*
- **KAUST Academy** — AI Specialization, top 1% of the national cohort · *2023 – 2024*

**Leadership & awards**
VP Operations, TechHub (KFUPM student technology chapter) — the chapter was awarded MiSK Foundation incubation during my tenure · BCG Jeel Tamooh Fellow · McKinsey Forward alumnus · Ibdaa National Science Fair finalist

---

## Selected work

| Project | What it is | Stack |
|---|---|---|
| [**Orama**](https://github.com/Alomair02/Orama) 🔒 | Intraday walk-forward trading system across equities, crypto, and tokenized commodities. 1.52 Sharpe out-of-sample over 18 folds and 3 CV schemes. Exit logic is shared byte-identically between backtest and live execution. | Python · SQLAlchemy · Alpaca · Binance |
| [**Blitz**](https://github.com/Alomair02/Blitz) | GPU-accelerated Monte Carlo actuarial reserving. AMD HIP kernels run thousands of parallel bootstrap chain-ladder sims over Schedule P loss triangles, emitting full reserve distributions with a cost-of-capital risk margin. | ROCm / HIP · Python |
| [**Flybee**](https://github.com/Alomair02/flybee-backend) 🔒 | AI travel platform — Go backend, native iOS client, React admin SPA, and FlyHive, a multi-provider agent layer built without vendor SDKs. | Go · Swift · PostgreSQL |
| [**Paro**](https://github.com/Alomair02/Paro) 🔒 | Generation-first engine that transpiles a high-level XML DSL into standards-conformant OOXML PowerPoint decks, with an agent layer on top. | Python · OOXML |
| [**Silkroad**](https://github.com/Alomair02/Silkroad) 🔒 | Quoting platform with AI-generated quotes, tokenized email approval flows, and Drizzle-backed Postgres. | Next.js · TypeScript · Drizzle |
| [**ESP32 Video Interpolation**](https://github.com/Alomair02/esp32-video-streaming-interpolation) | Real-time ESP32-S3 camera streaming over TCP with RAFT optical-flow interpolation and a hand-gesture CNN. | MicroPython · OpenCV · PyTorch |
| [**OS CPU Scheduler**](https://github.com/Alomair02/os-project-cpu-scheduler) | Scheduling algorithms in C with workload simulation and tests. | C · Make |
| [**Project Mou**](https://github.com/Alomair02/Mou) | Interactive portfolio built as a WebGL knowledge map. | React · TypeScript · React Three Fiber |
| **ChartWise** | Multi-modal RAG with LLM-based indexing and query optimization; fine-tuned Gemma 2 on chart imagery. Ranked 3rd of 80 at KAUST Academy. | PyTorch · LoRA |

🔒 = private repository — the link resolves if you have access. Happy to walk through any of these on request.

---

## Interests

- **Quantitative finance** — regime governance, walk-forward validation, and the unglamorous truth that the edge usually lives in the exit logic, not the entry.
- **GPU and high-performance compute** — writing kernels close to the metal, and making HPC clusters usable by people who shouldn't have to learn SLURM.
- **Agent systems built from primitives** — hand-rolled tool-calling loops and turn policy over vendor SDKs, because the abstraction is where the bugs hide.
- **Embedded systems** — microcontrollers, real-time streaming, and the constraints that make you honest.
- **Tech entrepreneurship in Saudi Arabia** — building the student and deep-tech ecosystem through TechHub.
- **Languages** — Arabic (native), English (IELTS 7.5), Korean (intermediate, ongoing).
