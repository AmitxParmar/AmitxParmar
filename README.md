<p align="center">
  <img src="/assets/header.png" alt="Amit Parmar Banner" width="100%" />
</p>
<p align="center">
  <!-- Daily Commit Streak & Longest Streak -->
  <a href="https://github.com/AmitxParmar">
    <img src="https://streak-stats.demolab.com/?user=AmitxParmar&theme=dracula&hide_border=false&border_radius=8" alt="Amit's GitHub Streak" />
  </a>
</p>
<div align="center">

# Amit Parmar
**Full-Stack AI & Distributed Systems Engineer**

Savarkundla, Gujarat, India

[![Portfolio](https://img.shields.io/badge/Portfolio-bento--grid-000000?style=for-the-badge&logo=vercel&logoColor=white)](https://portfolio-bento-grid.vercel.app/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-amitxparmar-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/amitxparmar)
[![GitHub](https://img.shields.io/badge/GitHub-AmitxParmar-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/AmitxParmar)
[![Email](https://img.shields.io/badge/Email-amitparmar901%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:amitparmar901@gmail.com)

</div>

---

### 👨‍💻 What I Build

I design and build end-to-end architectures across **distributed backend microservices**, **real-time systems**, and **agentic AI workflows**:

* 🤖 **Agentic & RAG Systems:** Multi-stage hybrid retrieval pipelines (HyDE + dense vector + full-text search with RRF reranking), streaming citation verification, and resilient Model Gateways with provider fallback.
* ⚡ **Distributed & Event-Driven Backends:** Asynchronous Saga patterns, high-throughput message brokers (RabbitMQ, Redis Pub/Sub), and race-condition prevention using PostgreSQL pessimistic locking.
* 🔄 **Real-Time & Local-First:** Non-blocking socket tiers, local-first client caching via Dexie.js (IndexedDB), and resilient background queue workers (BullMQ) delivering push notifications.

---

### 🚀 Featured Engineering Projects

| Project | Architecture & Stack | Key Highlights | Links |
| :--- | :--- | :--- | :--- |
| **Agentic Research Workspace** | `FastAPI` `LangGraph` `pgvector` `Cohere` `Next.js` | Built an enterprise RAG knowledge engine with async multi-modal ingestion (`arq`), hybrid retrieval (HyDE + dense + FTS with Cohere rerank-v3), and a LangGraph ReAct agent routed behind a Groq/OpenRouter fallback gateway. | [Live App](https://agentic-knowledge-base-web.vercel.app/research) • [GitHub](https://github.com/AmitxParmar/agentic-knowledge-base) |
| **Modular Mart** | `NestJS` `RabbitMQ` `PostgreSQL` `Stripe` `Turborepo` | Event-driven microservices e-commerce system implementing asynchronous Saga patterns across order/payment domains and pessimistic locking for 100% accurate, race-free inventory management. | [Live App](https://modular-mart-microservices-web.vercel.app/) • [GitHub](https://github.com/AmitxParmar/modular-mart-microservices) |
| **QuickChat** | `Next.js` `Socket.io` `Redis Pub/Sub` `BullMQ` `Dexie.js` | Horizontally scalable chat system featuring a local-first client layer (Dexie.js/IndexedDB) for offline messaging, optimistic state syncing, and BullMQ background workers for reliable Web Push delivery. | [Live App](https://quick-chat-redesigned-five.vercel.app/) • [GitHub](https://github.com/AmitxParmar/rapid-quest-assignment) |
| **Realtime Market Lab** | `React` `TypeScript` `Web Workers` `Canvas API` | Frontend stress-test laboratory benchmarking rendering performance under a continuous feed of 5,000+ ticks/sec without UI frame drops. | [GitHub](https://github.com/AmitxParmar/realtime-market-lab) |
| **HireCrowd** | `React` `Node.js` `Express` `MongoDB` `TanStack Query` | Full-stack job portal & ATS featuring role-based access control (RBAC), multi-stage applicant filtering, and optimistic state mutations. | [Live App](https://job-portal-mern-sigma.vercel.app/) • [GitHub](https://github.com/AmitxParmar/job-portal-mern) |

---

### 🛠️ Tech Stack & Ecosystem

```text
AI & Retrieval  ── LangGraph · pgvector · Cohere Rerank · Multi-modal Ingestion · Model Gateways
Distributed     ── RabbitMQ · BullMQ · Redis Pub/Sub · Socket.IO · Event-Driven Sagas
Backend         ── Node.js · NestJS · FastAPI · Express.js · REST · WebSockets · SSE
Databases       ── PostgreSQL · Supabase · MongoDB · Prisma · Dexie.js (IndexedDB)
Frontend        ── Next.js · React · TypeScript · TanStack Query · Zustand · TailwindCSS
DevOps & Tools  ── Docker · Turborepo · AWS EC2 · Git · Linux
