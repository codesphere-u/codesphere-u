<div align="center">
  <img src="./assets/hero-banner.svg" alt="Codesphere Engineering — Software Engineer, AI Systems Builder, Cybersecurity & Cloud Engineering" width="100%" />
</div>

<h3 align="center">
  Software Engineer &nbsp;|&nbsp; AI Systems Builder &nbsp;|&nbsp; Cybersecurity &nbsp;|&nbsp; Full-Stack &amp; Cloud Engineering &nbsp;|&nbsp; Building Technology for Real-World Problems
</h3>

<p align="center">
  <a href="https://github.com/codesphere-u/agentshield"><img src="https://img.shields.io/badge/Flagship-AgentShield%20(OWASP%202026)-4de8ae?style=flat-square" alt="AgentShield" /></a>
  <a href="https://github.com/codesphere-u/cyber-dragon"><img src="https://img.shields.io/badge/Flagship-Cyber%20Dragon%20v1.0-38bdf8?style=flat-square" alt="Cyber Dragon" /></a>
  <a href="https://github.com/codesphere-u/auralis-local"><img src="https://img.shields.io/badge/Flagship-Auralis%20Local%20AI-a78bfa?style=flat-square" alt="Auralis Local" /></a>
  <a href="https://github.com/codesphere-u/flowledger"><img src="https://img.shields.io/badge/Flagship-FlowLedger%20Core-fbbf24?style=flat-square" alt="FlowLedger" /></a>
  <a href="https://github.com/codesphere-u/ARGUS-AI"><img src="https://img.shields.io/badge/Flagship-ARGUS%20AI%20v2.1-f472b6?style=flat-square" alt="ARGUS AI" /></a>
  <a href="https://github.com/codesphere-u/stackpulse"><img src="https://img.shields.io/badge/Flagship-StackPulse%20SRE-60a5fa?style=flat-square" alt="StackPulse" /></a>
</p>

---

## Engineering Identity & Philosophy

I am a software engineer, full-stack architect, cybersecurity practitioner, and AI systems builder based in **Kampala, Uganda**. I design and build auditable, production-grade software systems at the intersection of:

- **Autonomous AI & Local Inference:** Multi-agent deliberation with adversarial veto controls, privacy-first Apple Silicon AI workspaces, and hybrid local retrieval (BM25 + phrase RAG).
- **Cybersecurity & AI Agent Governance:** OWASP 2026 agentic capability firewalls, prompt-injection red-teaming, and SSRF-free digital fraud detection tailored to East African Mobile Money and USSD threat patterns.
- **Financial Infrastructure & Distributed Reliability:** Integer minor-unit double-entry payment ledgers, idempotent webhook state machines, automated 3-way reconciliation, and OpenTelemetry critical-path observability.
- **Resilient Field & Healthcare Systems:** Offline-first smallholder agricultural advisory platforms with Lamport/LWW sync queues and polyglot clinical telemedicine architectures.

Every flagship repository below includes **working CLI/API/UI implementations, deterministic benchmarks, documented Architectural Decision Records (ADRs), and automated GitHub Actions verification.**

---

## Flagship Engineering Systems (Recommended Pinned Portfolio)

### 1. [🛡️ AgentShield — AI Agent Security & Governance Framework (`agentshield`)](https://github.com/codesphere-u/agentshield)
> **Domain:** AI Security · OWASP 2026 Agentic Top 10 · Capability Firewall · Python SDK & Security Lab
- **What It Solves:** Prevents autonomous LLM agents from falling victim to direct/indirect prompt injection, executing unauthorized shell/filesystem/SSRF tool calls, or leaking credentials.
- **Engineering Highlights:**
  - Multi-layer `PromptInjectionDetector` catching system-prompt overrides, RAG context poisoning, Base64/Hex obfuscation, and zero-width Unicode steganography.
  - Declarative `AgentShieldPolicy` enforcing `allow`, `deny`, and `require_approval` boundaries across Shell, Filesystem Sandbox, RFC1918/Cloud-Metadata SSRF, and SQLi inspectors.
  - SHA-256 hash-chained tamper-evident `AuditLedger` (`verify_integrity()`) + 25-scenario OWASP 2026 benchmark suite (**100% recall, 0% FPR, 42 passing tests**).

### 2. [🐉 Cyber Dragon v1.0 — Community Cyber Defense Platform (`cyber-dragon`)](https://github.com/codesphere-u/cyber-dragon)
> **Domain:** Defensive Cybersecurity · Mobile Money & USSD Fraud Intelligence · Next.js 15 & FastAPI · [**Live Demo ↗**](https://cyber-dragon-ivory.vercel.app)
- **What It Solves:** Helps individuals, community responders, and developers inspect suspicious SMS messages, phishing links, lookalike domains, and USSD traps without opening untrusted URLs.
- **Engineering Highlights:**
  - **5-Dimension Heuristic Engine** with parity across TypeScript (`apps/web`) and Python (`services/threat-api`), evaluating Credential Harvesting, Mobile Money/USSD Fraud (`*21*` call diversion, `*165*` traps), Domain Deception (IDN Punycode `xn--` & Levenshtein brand lookalikes across 18+ African & global brands), Coercive Urgency, and Advance-Fee scams.
  - **100% SSRF-Free by Construction** (zero external network fetches) + automatic PII redaction for exportable Markdown/JSON incident reports and a Developer CLI (`cyber-dragon scan | report | benchmark`).

### 3. [✨ Auralis Local v0.2 — Private Apple Silicon AI Workspace (`auralis-local`)](https://github.com/codesphere-u/auralis-local)
> **Domain:** Local LLM Inference · Hybrid BM25 RAG · Local Voice (MLX/Whisper) · React 19 & TypeScript
- **What It Solves:** Delivers a fast, inspectable local AI assistant engineered for 16 GB Apple Silicon Macs with zero cloud telemetry and explicit human approval for state-changing tools.
- **Engineering Highlights:**
  - **Local Document Knowledge Base (`server/knowledge.ts`)** with line-aware chunking and Hybrid BM25 + Phrase retrieval (`P50: 0.245 ms`), streaming inline source citations (`#Lstart-Lend`) into chat responses.
  - **Guarded Workspace Inspector (`server/workspace.ts`)** blocking path traversal, symlinks, and dotfile/secret access, paired with session-bound 5-minute approval tokens (`36 passing tests`).

### 4. [💳 FlowLedger — African Payment Orchestration & Double-Entry Engine (`flowledger`)](https://github.com/codesphere-u/flowledger)
> **Domain:** Fintech Infrastructure · Double-Entry Accounting · Mobile Money Reconciliation · Python & FastAPI
- **What It Solves:** Models institutional payment orchestration across simulated MTN MoMo and Airtel Money rails with mathematical ledger integrity.
- **Engineering Highlights:**
  - **Integer Minor-Unit Double-Entry Engine** (`UGX`, `KES`, `NGN`, `USD`) enforcing $\sum \text{Debits} \equiv \sum \text{Credits}$ and SHA-256 hash-chained journal entries.
  - **Idempotent Payment State Machine & 3-Way Reconciliation Pipeline** handling duplicate webhooks, out-of-order settlement-before-authorization callbacks, HMAC-SHA256 replay windows, and automated fee-discrepancy adjustment proposals (`51 passing invariant & API tests`).

### 5. [🏛️ ARGUS AI v2.1 — Auditable Multi-Agent Decision System (`ARGUS-AI`)](https://github.com/codesphere-u/ARGUS-AI)
> **Domain:** Multi-Agent Systems · Adversarial Governance · Leakage-Free Backtesting · MCP Server
- **What It Solves:** Replaces blind single-agent execution with a 7-agent Investment Committee where a dedicated **Devil's Advocate Agent** stress-tests proposals and holds unilateral veto power (`>=75%` disqualification risk).
- **Engineering Highlights:**
  - **Leakage-Free Walk-Forward Backtester (`argus_ai/backtest.py`)** with `PointInTimeGuard` (`LookaheadLeakageError`), ATR-scaled slippage + spread modeling, and counterfactual Devil's Advocate veto attribution (`61 passing tests`).
  - Cryptographic SHA-256 **Trade Passports** with deterministic decision replay (`argus_ai/cli.py replay`) and Model Context Protocol (`argus_ai/mcp_server.py`) integration.

### 6. [📈 StackPulse — Cloud Observability, Distributed Tracing & SLO Lab (`stackpulse`)](https://github.com/codesphere-u/stackpulse)
> **Domain:** Cloud Reliability · OpenTelemetry DAG Analysis · Multi-Window SLOs · Python, FastAPI & Docker
- **What It Solves:** Self-hostable observability and incident investigation platform for reconstructing distributed traces, catching ORM performance regressions, and tracking error budgets.
- **Engineering Highlights:**
  - **W3C TraceContext DAG Analyzer** computing true critical-path bottlenecks (`51.2 µs/trace`), automatic **N+1 Query Detection**, and cascading retry-storm identification.
  - **Google SRE Workbook Multi-Window Burn-Rate Engine** (`1h/6h/24h/72h`) + automated Blameless SRE Postmortem generator (`47 passing tests`).

---

## Additional Engineering Repositories

- **[🌱 AgriSignal (`agrisignal`)](https://github.com/codesphere-u/agrisignal):** Offline-first smallholder agricultural decision support platform featuring agro-ecological rule evaluation with explicit uncertainty bounds, Fall Armyworm / Coffee Wilt IPM risk matrices, Lamport-clock LWW offline sync queues, and 160-character SMS advisories in English, Luganda, and Swahili.
- **[🏥 Clinical & Virtual Health Platform (`Clinical-Virtual-Health-Platform`)](https://github.com/codesphere-u/Clinical-Virtual-Health-Platform):** Polyglot telemedicine monorepo (Turborepo, Next.js portals, Fastify OpenAPI backend, Prisma/PostgreSQL, LiveKit SFU video gateway, Flutter packages, and 15 documented ADRs).
- **[🌐 Engineering Portfolio Showcase (`codesphere-portfolio`)](https://github.com/codesphere-u/codesphere-portfolio):** Interactive recruiter-facing technical portfolio featuring live architecture explorations, benchmark data, and engineering case studies.

---

## Technology Stack & Core Competencies

| Layer | Technologies & Practices |
| :--- | :--- |
| **Languages** | TypeScript, Python (3.11–3.13), Dart / Flutter, SQL, Bash |
| **Frontend & Mobile** | React 19, Next.js 15, Vite, Tailwind CSS, Accessible Design Systems (WCAG), Flutter Cross-Platform |
| **Backend & Systems** | FastAPI, Node.js, Fastify, REST / OpenAPI, Server-Sent Events (SSE), Model Context Protocol (MCP), CLI Tooling |
| **AI & Machine Learning** | Multi-Agent Orchestration, Local LLMs (Ollama, MLX, Whisper), Hybrid BM25 + Phrase RAG, AI Security & Guardrails (OWASP) |
| **Security & Fintech** | Static URL/Domain Heuristics, IDN Homograph Detection, Capability Firewalls, HMAC Webhook Security, Double-Entry Ledgers |
| **Data, Cloud & DevOps** | PostgreSQL, Prisma, Redis, OpenTelemetry, Docker Compose, GitHub Actions CI/CD, Deterministic Benchmarking |

---

## Collaborating & Open Source

Contributions, security reviews, and architectural discussions are welcome across all public repositories:
- Review each repository's `CONTRIBUTING.md`, `SECURITY.md`, and `docs/architecture.md`.
- Explore labeled issues and `docs/roadmap.md` for scoped open-source enhancements.
