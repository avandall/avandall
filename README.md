# Hi, I'm Vu Nguyen (avandall) 👋

Backend & AI Engineer based in Ho Chi Minh City, Vietnam.  
I transitioned from logistics operations into software engineering by automating operational bottlenecks with code. Today, my focus is on **asynchronous Python backends**, **low-latency streaming**, and **hardening AI systems for production reliability**.

I am roughly 1 year into my professional engineering journey. I care deeply about deterministic testing, system concurrency, and pragmatic software architecture over industry hype.

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

- **Backend & Microservices**: Building clean, async APIs with FastAPI, handling concurrent workloads, and connecting services via gRPC and Redis Streams.
- **AI Agent Reliability & Guardrails**: Developing Model Context Protocol (MCP) tool servers and mitigating LLM failure modes (schema drift, race conditions, timeout handling).
- **Chaos Engineering & Testing**: Validating failure modes using property-based testing and deterministic simulations rather than relying on guesswork.
- **Domain Modeling**: Applying Domain-Driven Design (DDD) to software problems, drawing from real-world operations and inventory management.

---

### 📌 Featured Work

#### 1. [`arc-reliability`](https://pypi.org/project/arc-reliability/) — Autonomous Reliability & Chaos Harness for AI Agents
*Open-source Python library published on PyPI*
- An interceptor SDK (`@trace_agent`, `@trace_tool`) designed to trace, test, and inject faults into autonomous agent runs.
- Features virtual clock injection, sandboxed fork-replay, and automated delta-debugging (`ddmin`) to reduce transient LLM failures into reproducible test cases.
- Implements AST invariant mining via Tree-Sitter to verify transactional integrity rules.
- **Links**: [PyPI Package](https://pypi.org/project/arc-reliability/) • [Source Code](https://github.com/avandall)

#### 2. Low-Latency Conversational Voice Pipeline
*Real-time audio AI service*
- Built a bidirectional streaming pipeline decoupling real-time dialogue generation from background evaluation workers.
- Integrated WebSocket streaming with acoustic filler cues to cut Time-to-First-Audio (TTFA) from 3,500ms down to <200ms.
- **Links**: [Live Application Demo](https://haku-hakus.onrender.com/) • [Portfolio Walkthrough](https://avandall.github.io/Portfolio/)

#### 3. Concurrency-Safe WMS Core Engine
*Domain-Driven Warehouse Management Backend*
- Designed around real-world warehousing constraints (FIFO rules, slotting optimization, capacity limits).
- Handled high-concurrency checkout and stock movement using PostgreSQL row-level locks (`SELECT ... FOR UPDATE`) and Redis distributed locks to prevent overselling.

---

### 🧰 Tech Stack & Tools

| Area | Tools & Technologies |
| :--- | :--- |
| **Languages & Core** | Python (FastAPI, Asyncio, Pydantic), SQL, JavaScript / Node.js |
| **Data & Messaging** | PostgreSQL, Redis (Streams, Distributed Locks), SQLAlchemy |
| **AI & Protocols** | Model Context Protocol (MCP), gRPC, OpenTelemetry, AST Parsing (Tree-Sitter) |
| **Testing & Tooling** | Pytest, Docker, Git/GitHub Actions, Linux/WSL |

---

### 📈 Current Growth & Philosophy

> *"Code is a liability; clear domain boundaries and reproducible tests are the assets."*

I recognize that I am early in my engineering path, which is why I actively seek:
- Rigorous peer code reviews and architectural critique.
- Complex backend distributed system challenges.
- Collaborations on open-source reliability tools and production AI systems.

Feel free to explore my repositories, test [arc-reliability](https://pypi.org/project/arc-reliability/), or reach out for collaboration.
