## 👋 Hi, I'm Deyvi

I'm a **full-stack software engineer** with ~4 years of experience in **early-stage startups**,
working at the intersection of **product, architecture, and applied AI**.

I started on the frontend and progressively evolved toward **end-to-end ownership**:
system design, technical decision-making, and shipping features into production.
Most recently, I led the technical foundations of a **generative AI product in healthcare**,
taking it from a hackathon prototype to real-world production usage, with a strong focus on
**robustness, scalability, and zero-click user experience**.

I enjoy building AI-powered products that operate in **real operational contexts**,
where constraints, trade-offs, and user trust matter more than polished demos.

---

## 🚀 Selected Projects

### 🥇 Gmail Agent POC — AI Gmail Copilot (Deployed)
A production-oriented Gmail assistant POC that helps users **triage inbox activity, draft replies, and send with explicit confirmation**.

- Tool-driven chat with streaming responses and transparent tool events
- Gmail workflows: recent email summaries, unanswered threads, waiting-for-reply detection, attachment text extraction
- Guarded sending flow: `draft_email -> confirm_send_email`
- Next.js App Router + Auth.js Google OAuth + Prisma/Postgres + AI SDK
- Fully deployed and demo-ready

🔗 Live demo: https://gmail-agent-poc.vercel.app/  
🔗 Code: https://github.com/dezu2430/gmail-agent-poc

---

### 🥈 Persona Scoring Lab — LLM-based Lead Scoring (Deployed)
A persona-driven lead scoring POC designed to help sales teams decide
**which leads to contact first, and why**.

- One-prompt LLM scoring with explainability and confidence cutoffs
- Next.js monorepo (App Router + API Routes)
- Product-first trade-offs: simple infra, predictable cost & latency
- Fully deployed and demo-ready

🔗 Live demo: https://persona-scoring-lab.vercel.app/login  
🔗 Code: https://github.com/dezu2430/persona-scoring-lab

---

### 🥉 Medicoder RAG — Medical Coding with Retrieval-Augmented Generation (Ongoing)
A RAG system that suggests **ICD-10 medical codes** from clinical descriptions,
using annotated medical PDFs (CoCoA) as a trusted knowledge source.

- Real-world healthcare domain constraints (PMSI, ICD-10)
- Microservices architecture: Next.js, NestJS, FastAPI
- PDF ingestion, chunking, retrieval, and LLM-assisted reasoning
- Focus on correctness, traceability, and explainability

🔗 Code: https://github.com/dezu2430/medicoder-rag

---

## 🧰 Stack & Tools (used in recent projects)

**Frontend**
- React, Next.js (App Router)
- TypeScript
- Tailwind CSS

**Backend**
- Next.js API Routes
- NestJS
- FastAPI (Python)

**Data & Storage**
- Postgres (Neon)
- JSONB for embeddings and structured data

**AI / LLM**
- OpenAI APIs (embeddings, structured outputs)
- Retrieval-Augmented Generation (RAG)
- Prompt design with cost and latency constraints

**Infra & Dev**
- Vercel
- Docker & docker-compose
- GitHub Actions (basic CI)

---

## 🧠 What I focus on

- Product-oriented system design
- Pragmatic architecture and explicit trade-offs
- Applied LLMs beyond demos (scoring, RAG, explainability)
- Shipping usable software under real constraints
- Collaborating closely with product and domain experts

---

## 🎯 What I'm looking for

I'm looking to join a **product-driven team or startup** working on **real-world problems**,
where I can take ownership across the stack, contribute to architectural decisions,
and help grow systems from **early-stage to production**.

If you're building something ambitious and grounded in reality, I'd be happy to connect.
