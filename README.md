
<div align="center">

  <h1>Vivek Kumar</h1>
  <h3>AI Engineer | Applied AI · Backend Systems · Infrastructure</h3>

  <p>
    Building reliable AI-powered products — from application architecture and backend systems to intelligent workflows.
  </p>

  <a href="https://www.linkedin.com/in/vivek-kumar-tenacious/">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white" />
  </a>
  <a href="mailto:vickykumar7061@gmail.com">
    <img src="https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=gmail&logoColor=white" />
  </a>
  <a href="https://hashnode.com/@TenaciousDeveloper">
    <img src="https://img.shields.io/badge/Blog-2962FF?style=flat-square&logo=hashnode&logoColor=white" />
  </a>
  <a href="https://leetcode.com/u/Tenacious_Developer/">
    <img src="https://img.shields.io/badge/LeetCode-FFA116?style=flat-square&logo=leetcode&logoColor=black" />
  </a>
  <a href="https://github.com/Tenacious-Developer">
    <img src="https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white" />
  </a>

</div>

---

## About Me

I'm an **AI Engineer at Adnolgy**, building AI-powered products across product engineering, backend architecture, infrastructure, and applied AI.

I bring 4+ years of software engineering experience, primarily in backend development and distributed systems.

My approach to AI engineering is grounded in a simple idea:

**Building an AI demo is easy. Engineering a system that remains reliable when things fail is the real challenge.**

I work at the application engineering layer — integrating existing models into useful products and building the systems around them.

My interests include:

- Agentic AI and intelligent workflows
- Large Language Model applications
- Retrieval-Augmented Generation (RAG)
- LLM evaluation and observability
- AI application infrastructure
- Backend architecture and distributed systems
- System design and performance engineering

I care about the engineering details behind the product: concurrency, consistency, timeouts, retries, idempotency, observability, latency, and cost.

> AI systems have new failure modes. They also inherited all the old ones.

---

## Engineering Focus

| Domain | Areas of Interest |
|---|---|
| Applied AI | LLM applications, tool calling, agentic workflows, structured outputs |
| RAG & Evaluation | Hybrid retrieval, vector search, BM25, reranking, RAGAS |
| Backend Engineering | APIs, microservices, database design, domain boundaries |
| Distributed Systems | Concurrency, distributed locking, messaging, idempotency |
| AI Infrastructure | Model integration, tracing, evaluation pipelines, reliability |
| System Design | Scalability, availability, consistency, architecture trade-offs |

---

## Selected Engineering Projects

Projects where I focus on architecture, implementation details, and engineering trade-offs.

### 1. Airline Booking System — HLD + Runnable LLD

[Repository](https://github.com/Tenacious-Developer/Airline-Booking-System-Design-HLD-LLD)

A system design and runnable implementation of an airline booking platform, with particular emphasis on correctness under concurrent bookings.

**Engineering problems explored:**

- CQRS and read-optimized flight search.
- Transactional seat reservations using PostgreSQL row-level locking.
- Seat holds and idempotency keys.
- Asynchronous payment processing using the Saga pattern.
- Compensation and seat release when payment fails.
- Concurrency testing: two users compete for the last available seat; exactly one succeeds.

**Stack:** TypeScript · Node.js · PostgreSQL · System Design

### 2. Airbnb Backend — Distributed Microservices

[Repository](https://github.com/Tenacious-Developer/Airbnb_Backend_Microservices_Architecture)

A distributed backend architecture demonstrating independently deployable services and service-level ownership.

**Engineering problems explored:**

- Five microservices with independent business responsibilities and databases.
- Go-based API Gateway with authentication, authorization and rate limiting.
- JWT, RBAC and identity propagation across service boundaries.
- Redis distributed locking for inventory coordination.
- BullMQ-based asynchronous notification processing.
- Retry handling, service communication and database query optimization.

**Stack:** Go · Node.js · TypeScript · Redis · BullMQ · MySQL · Prisma · Sequelize

### 3. TaskFlow — Go Backend API

[Repository](https://github.com/Tenacious-Developer/taskflow-vivek-kumar)

A Go REST API built with a focus on clean architecture, explicit database operations and maintainability.

**Engineering problems explored:**

- Handler → Service → Repository architecture.
- Interface-based dependency injection.
- PostgreSQL schema design and versioned migrations.
- Transactional updates using SELECT FOR UPDATE.
- Compound indexes for filtered database queries.
- Dockerized local development and automated tests.

**Stack:** Go · PostgreSQL · sqlx · Docker · REST API

---

## Professional Experience

### AI Engineer — Adnolgy
*October 2026 – Present*

- Building AI-powered products across product scope, backend architecture, infrastructure and AI integration.
- Working on applied AI engineering and product development.
- Training engineers in practical AI engineering workflows and development practices.

### Software Development Engineer I — GeeksforGeeks
*September 2022 – September 2026*

- Built Docker-sandboxed code execution workflows using BullMQ queues, supporting 10,000+ learners.
- Addressed booking race conditions using Redis distributed locking and idempotency keys.
- Reduced API latency by **40%** through N+1 query elimination and database index redesign, at 500+ RPS.
- Developed asynchronous notification processing with dead-letter queues and exponential backoff, supporting 15,000+ users.
- Contributed to a mentorship platform serving 5,000+ concurrent users.

### Software Development Engineer Intern — GeeksforGeeks
*March 2022 – August 2022*

- Improved a Next.js quiz portal to 18,000+ monthly attempts, representing 40% growth.
- Migrated 60+ PHP pages to Next.js SSR, reducing page load time by 45%.

---

## 🛠️ Technical Toolkit

Technologies and tools I use to design, build, deploy, and operate reliable software and AI-powered systems.

### 🧠 AI & LLM Engineering

<p align="center">
  <img src="https://img.shields.io/badge/LLM_Applications-412991?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Agentic_AI-6C47FF?style=for-the-badge" />
  <img src="https://img.shields.io/badge/RAG-1677C8?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Hybrid_Search-087E8B?style=for-the-badge" />
  <img src="https://img.shields.io/badge/LLM_Evaluation-7952B3?style=for-the-badge" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/OpenAI_API-412991?style=flat-square" />
  <img src="https://img.shields.io/badge/Anthropic_API-D97757?style=flat-square" />
  <img src="https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square" />
  <img src="https://img.shields.io/badge/pgvector-336791?style=flat-square" />
  <img src="https://img.shields.io/badge/BM25-087E8B?style=flat-square" />
  <img src="https://img.shields.io/badge/Pinecone-000000?style=flat-square" />
  <img src="https://img.shields.io/badge/FAISS-0467DF?style=flat-square" />
  <img src="https://img.shields.io/badge/RAGAS-7952B3?style=flat-square" />
  <img src="https://img.shields.io/badge/Langfuse-111111?style=flat-square" />
  <img src="https://img.shields.io/badge/promptfoo-5B46E8?style=flat-square" />
</p>

### 💻 Programming Languages

<p align="center">
  <img src="https://skillicons.dev/icons?i=ts,js,go,py&theme=dark&perline=4" />
</p>

### ⚙️ Backend & API Engineering

<p align="center">
  <img src="https://skillicons.dev/icons?i=nodejs,express,nestjs,graphql&theme=dark&perline=4" />
</p>

### 🗄️ Databases & Storage

<p align="center">
  <img src="https://skillicons.dev/icons?i=postgres,mysql,mongodb,redis&theme=dark&perline=4" />
</p>

### 🔄 Distributed Systems & Messaging

<p align="center">
  <img src="https://skillicons.dev/icons?i=kafka,rabbitmq&theme=dark&perline=2" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/BullMQ-E34F26?style=flat-square" />
  <img src="https://img.shields.io/badge/Microservices-2563EB?style=flat-square" />
  <img src="https://img.shields.io/badge/Event--Driven_Architecture-0D9488?style=flat-square" />
</p>

### ☁️ Cloud, DevOps & Infrastructure

<p align="center">
  <img src="https://skillicons.dev/icons?i=aws,azure,docker,kubernetes,githubactions&theme=dark&perline=5" />
</p>

### 🧪 Developer Tools & Testing

<p align="center">
  <img src="https://skillicons.dev/icons?i=git,github,vscode,postman,jest&theme=dark&perline=5" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Prisma-2D3748?style=flat-square" />
  <img src="https://img.shields.io/badge/Sequelize-52B0E7?style=flat-square" />
  <img src="https://img.shields.io/badge/CI%2FCD-2088FF?style=flat-square" />
</p>

---


## 📊 GitHub Engineering Activity

### GitHub Overview

<div align="center">
  <picture>
    <source
      media="(prefers-color-scheme: dark)"
      srcset="./assets/overview.dark.svg"
    />
    <img
      src="./assets/overview.light.svg"
      width="100%"
      alt="GitHub Engineering Overview"
    />
  </picture>
</div>

### Contribution Activity & Momentum

<div align="center">
  <picture>
    <source
      media="(prefers-color-scheme: dark)"
      srcset="./assets/momentum.dark.svg"
    />
    <img
      src="./assets/momentum.light.svg"
      width="100%"
      alt="GitHub Contribution Momentum"
    />
  </picture>
</div>

### Contribution Calendar & Streak

<div align="center">
  <picture>
    <source
      media="(prefers-color-scheme: dark)"
      srcset="./assets/contributions.dark.svg"
    />
    <img
      src="./assets/contributions.light.svg"
      width="100%"
      alt="GitHub Contribution Calendar and Streak"
    />
  </picture>
</div>

### Programming Language Distribution

<div align="center">
  <picture>
    <source
      media="(prefers-color-scheme: dark)"
      srcset="./assets/languages.dark.svg"
    />
    <img
      src="./assets/languages.light.svg"
      width="100%"
      alt="Programming Language Distribution"
    />
  </picture>
</div>

<div align="center">

  <a href="https://github.com/Tenacious-Developer?tab=repositories">Explore Repositories</a>
  ·
  <a href="https://github.com/Tenacious-Developer?tab=activity">Recent Activity</a>
  ·
  <a href="https://github.com/Tenacious-Developer">GitHub Profile</a>

</div>

---

## Engineering Principles

- **Correctness before optimization:** Get consistency, transactions, and failure handling right before optimizing throughput.
- **Design for failure:** Account for timeouts, retries, duplicate requests, partial failures and recovery.
- **Measure before optimizing:** Use query analysis, latency metrics, and system behaviour to guide performance improvements.
- **Build with clear boundaries:** Prefer maintainable components, explicit contracts and documented architectural decisions.
- **Learn by building:** Turn engineering concepts into working implementations and document the trade-offs.

---

## Writing & Knowledge Sharing

I write about backend engineering, system design, distributed systems, and applied AI.

- [LinkedIn — Technical Notes & Engineering Insights](https://www.linkedin.com/in/vivek-kumar-tenacious/)
- [Hashnode — Technical Articles](https://hashnode.com/@TenaciousDeveloper)

---

<div align="center">

  <h3>Build Fast → Break Fast → Fix Fast → Learn Fast</h3>

  <em>Tenacious Developer</em>

</div>
