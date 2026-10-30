# Hi, I'm Milad Ghaderi 👋
### Senior-Minded Backend Software Engineer | Go (Golang) Specialist

Experienced backend engineer passionate about high-concurrency systems, low-latency architectures, and resilient distributed services. I specialize in building robust microservices, scalable worker pipelines, and high-throughput data processing engines using idiomatic Go, modern relational databases, and real-time streaming protocols.

---

### 🛠️ Technical Arsenal

- **Languages:** Go (Golang 1.24+), SQL (PostgreSQL, SQLite), Python
- **Backend & Architecture:** Clean Architecture, Domain-Driven Design (DDD), Concurrency (Goroutines & Channels, Worker Pools, Actor-Style Hubs, SingleFlight), RESTful APIs, Graceful Shutdown
- **Data & Persistence:** PostgreSQL 17 (pgx, Window Functions, Composite Indexing, Query Optimization), GORM, SQLite (ACID Transactions), Redis
- **Streaming & Protocols:** WebSockets (Gorilla, Heartbeat / Non-blocking Broadcasts), HTTP/2 Keep-Alive
- **DevOps & Tooling:** Docker & Multi-stage Containerization, Docker Compose, GitHub Actions (CI/CD Pipelines), Bruno, Git

---

### 🛡️ Featured Flagship Projects

#### 🕷️ [LinkSentinel](https://github.com/milad-ghaderi-dev/link-sentinel)
> **Enterprise-Grade Asynchronous Web Crawler & Link Health Auditor**
- Engineered with **Clean Architecture** enforcing strict domain independence.
- **20-Worker Concurrency Pool:** Bounded external link health verification with backpressure channels, eliminating goroutine leaks.
- **SingleFlight Coalescing:** Eliminates thundering-herd duplicate crawls of identical URL targets.
- **Database Engineering:** Multi-column composite PostgreSQL indexing and `COUNT(*) OVER()` window function pagination for sub-millisecond query execution on millions of links.
- **Deterministic Testing:** 100% in-memory `http.RoundTripper` network simulation with zero network dependencies and race detection.

#### ⚡ [GridPulse](https://github.com/milad-ghaderi-dev/gridpulse)
> **Real-Time Smart Grid Energy Dispatching & Telemetry Microservice**
- **Actor-Model WebSocket Hub:** Real-time bi-directional telemetry streaming with non-blocking broadcast dispatching and automatic heartbeat (ping/pong) dead-socket reaping.
- **ACID Atomic Transactions:** Strict consistency guarantees (`tx.Commit` / `tx.Rollback`) balancing multi-station energy supply against consumer demand.
- **Structured Observability:** Integrated enterprise JSON logging utilizing Go's native `log/slog`.
- **Lightweight Production Container:** Multi-stage Docker image producing a secure non-root container under **25MB**.

---

### 📊 GitHub Activity & Metrics

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=milad-ghaderi-dev&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" alt="Milad's GitHub Stats" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=milad-ghaderi-dev&layout=compact&theme=tokyonight&hide_border=true" alt="Top Languages" />
</p>

---

### 📬 Get In Touch

- **Email:** milad.ghaderi.dev@gmail.com
- **GitHub:** [@milad-ghaderi-dev](https://github.com/milad-ghaderi-dev)
