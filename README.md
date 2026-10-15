# Hi, I'm Vu Nguyen 👋

Backend & AI Engineer based in Ho Chi Minh City, Vietnam.

I transitioned from logistics operations into software engineering focusing on async Python backends and Applied-AI for production systems.

1 year into my professional engineering journey, including 2 months as a Software Developer in Chandigarh, India.

---

### 🔗 Quick Links

<p align="left">
  <a href="https://avandall.github.io/Portfolio/"><img src="https://img.shields.io/badge/Portfolio-Interactive_Site-2563eb?style=flat-square&logo=google-chrome&logoColor=white" alt="Portfolio" /></a>
  <a href="https://pypi.org/project/arc-reliability/"><img src="https://img.shields.io/pypi/v/arc-reliability?style=flat-square&color=blue&label=PyPI%3A%20arc-reliability" alt="PyPI" /></a>
  <a href="https://haku-hakus.onrender.com/"><img src="https://img.shields.io/badge/Live_Demo-Haku_App-10b981?style=flat-square&logo=render&logoColor=white" alt="Live Demo" /></a>
  <a href="https://www.linkedin.com/in/avandall479"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="mailto:avandall.lucas@gmail.com"><img src="https://img.shields.io/badge/Email-avandall.lucas@gmail.com-ea4335?style=flat-square&logo=gmail&logoColor=white" alt="Email" /></a>
</p>

---

### 🛠️ What I Focus On

- **Applied Generative AI**: Designing production-grade LLM services.
- **AI-Native Architecture**: Building workflows designed from the ground up around autonomous agents and MCP tool.
- **AI System Reliability & Guardrails**: Hardening non-deterministic AI behavior using strict validation and AST invariants.
- **Deterministic Chaos Testing**: Stress-testing agent workflows with simulated latency, fault injections, and replay engines.

---

### 📌 Featured Work

#### 1. [`arc-reliability`](https://pypi.org/project/arc-reliability/) — Autonomous Reliability & Chaos Harness for AI Agents
*Open-source Python library published on PyPI*
- An interceptor SDK (`@trace_agent`, `@trace_tool`) designed to trace, test, and inject faults into autonomous agent runs.
- Features virtual clock injection, sandboxed fork-replay, and automated delta-debugging (`ddmin`) to reduce transient LLM failures into reproducible test cases.
- Implements AST invariant mining via Tree-Sitter to verify transactional integrity rules.
- **Links**: [PyPI Package](https://pypi.org/project/arc-reliability/) • [Source Code]((https://github.com/avandall/ARC))

#### 2. Low-Latency TTS English App
*Real-time audio AI service*
- Built a bidirectional streaming pipeline decoupling real-time dialogue generation from background evaluation workers.
- Integrated WebSocket streaming with acoustic filler cues to cut Time-to-First-Audio (TTFA) from 3,500ms down to <200ms.
- **Links**: [Live Application Demo](https://haku-hakus.onrender.com/)

#### 3. Concurrency-Safe WMS Core Engine
*Domain-Driven Warehouse Management Backend*
- Designed around real-world warehousing constraints (FIFO rules, slotting optimization, capacity limits).
- Handled high-concurrency checkout and stock movement using PostgreSQL row-level locks and Redis distributed locks to prevent overselling.
- **Links**: [Source Code]((https://github.com/avandall/ARC)](https://github.com/avandall/WMS_Core))
---

### 🧰 Tech Stack & Tools

| Area | Tools & Technologies |
| :--- | :--- |
| **Languages & Core** | Python (FastAPI, Asyncio, Pydantic), SQL, JavaScript / Node.js |
| **Data & Messaging** | PostgreSQL, Redis (Streams, Distributed Locks), SQLAlchemy |
| **AI & Protocols** | Model Context Protocol (MCP), gRPC, OpenTelemetry, AST Parsing (Tree-Sitter) |
| **Testing & Tooling** | Pytest, Docker, Git/GitHub Actions, Linux/WSL |

---

> Early in my engineering path—focused on turning brittle, non-deterministic AI into resilient production systems. Always seeking tough code reviews, complex failure modes, and opportunities to harden open-source AI tooling alongside experienced engineers.
