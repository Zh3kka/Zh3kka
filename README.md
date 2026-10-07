# Evgeniy Seleznev

Software engineer. Go and TypeScript. I build backend systems that survive the next order of magnitude — and I usually ship the interface on top of them too.

Currently at **SunsetHQ**, a US platform automating startup wind-downs, where I work on event-driven infrastructure on AWS and on the tooling our engineering team uses to work with LLM agents.

---

### What I work on

**Distributed backends.** Monolith decomposition along domain boundaries, guaranteed event delivery, idempotent processing, orchestration that survives partial failure. Go in fintech and IoT; TypeScript on AWS today.

**Event-driven architecture.** Queue-based execution with backpressure and dead-letter handling, domain event buses, state machines for long-running workflows with human-in-the-loop steps. Migrations done as strangler rollouts — no big-bang releases.

**LLM agent infrastructure.** Agent harnesses, MCP tool servers, structured-output review gates — and evaluation suites that measure the agents themselves, because prompt changes validated by impression aren't validated at all.

---

### Selected work

Most of my production work lives in private repositories. What I can describe:

**Event-driven export platform** — replaced synchronous orchestrator calls from the API, status polling, and workflow state held in a JSON blob with a queued execution path, webhook callbacks, and a normalised data model with a transactional outbox. Migrated platform by platform, no downtime.
`TypeScript · AWS Step Functions · EventBridge · SQS · ECS Fargate · Terraform · PostgreSQL`

**Payment processing platform** — decomposed a monolith into domain microservices, implemented distributed transactions with guaranteed delivery, built a WebSocket server streaming financial data to thousands of concurrent connections.
`Go · gRPC · Kafka · PostgreSQL · ClickHouse · Kubernetes · OpenTelemetry`

**IoT telemetry platform** — backend for a distributed vending machine fleet: telemetry ingestion, an analytical store for reporting, event-driven service communication, and an offline-capable PWA for field technicians.
`Go · PostgreSQL · ClickHouse · NATS · Next.js · Service Workers`

---

### Stack

**Languages** — Go, TypeScript, Python, SQL

**Backend** — gRPC, WebSocket, REST, tRPC, Fastify, microservices, DDD, event-driven architecture, transactional outbox, CQRS

**Data** — PostgreSQL, ClickHouse, MongoDB, Redis, Kafka, NATS, Prisma

**Infrastructure** — AWS, Terraform, Kubernetes, Docker, GitLab CI, GitHub Actions, OpenTelemetry, Prometheus

**Frontend** — React, Next.js, Module Federation, Feature-Sliced Design, TanStack Query, Tailwind

---

### Contact

[Telegram](https://t.me/zh_go_dev) · [Email](mailto:zheseleznev@gmail.com)
