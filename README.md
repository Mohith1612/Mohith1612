# Mohith N

Backend and systems engineer focused on **storage, distributed systems, and reliability**. I like building the durable, concurrent, failure-tolerant layer that sits underneath applications — and understanding exactly how it behaves when pushed past its limits.

B.Tech in Computer Science, Dayananda Sagar University (2025). Currently Founding Engineer at SiteSmart.

---

### Featured projects

**[WAL Engine](https://github.com/Mohith1612/wal)** &nbsp;·&nbsp; `Go`
A crash-consistent Write-Ahead Log engine: segmented append-only storage, CRC32C corruption detection, concurrent group commit with strict LSN ordering, and checkpoint-assisted crash recovery. Validated with 90+ tests including fault injection and chaos testing. Models the durability internals found in systems like PostgreSQL WAL and RocksDB.

**[Distributed Job Queue](https://github.com/Mohith1612/job-queue-system)** &nbsp;·&nbsp; `Python` `FastAPI` `Redis` `PostgreSQL` `Kubernetes` &nbsp;·&nbsp; [Live](https://queue.mohith16.com)
A priority job queue with exponential-backoff-with-jitter retries, idempotent request handling, per-job execution timeouts, and worker crash recovery. Multi-queue Redis scheduling, PostgreSQL-backed job state, and a Kubernetes (kind) deployment. Load-tested with k6 to find the worker-throughput scaling ceiling.

**[Collaborative Canvas](https://github.com/Mohith1612/canvas)** &nbsp;·&nbsp; `TypeScript` `Yjs` `uWebSockets.js` &nbsp;·&nbsp; [Live](https://canvas.mohith16.com)
A real-time multi-user whiteboard using CRDTs over a binary WebSocket protocol, with per-socket backpressure handling and measured graceful degradation under load.

---

### Writing

I write about storage internals, performance engineering, and real-world debugging at **[blog.mohith16.com](https://blog.mohith16.com)**.

---

### Tech

**Languages:** Go · Python · TypeScript · SQL
**Infrastructure & tools:** Linux · Docker · Kubernetes · PostgreSQL · Redis · Prometheus · k6 · GitHub Actions · AWS

---

### Reach me

[LinkedIn](https://linkedin.com/in/Mohith16) &nbsp;·&nbsp; [Portfolio](https://mohith16.com) &nbsp;·&nbsp; mohith.work16@gmail.com
