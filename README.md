# Mohith N

Backend and systems engineer focused on **storage, distributed systems, and reliability**. I like building the durable, concurrent, failure-tolerant layer that sits underneath applications — and understanding exactly how it behaves when pushed past its limits.

B.Tech in Computer Science, Dayananda Sagar University (2025). Currently Founding Engineer at SiteSmart.

---

### Featured projects

**[WAL Engine](https://github.com/Mohith1612/wal)** &nbsp;·&nbsp; `Go`<br>
A crash-consistent Write-Ahead Log engine: segmented append-only storage, CRC32C corruption detection, concurrent group commit with strict LSN ordering, and checkpoint-assisted crash recovery. Validated with 90+ tests including fault injection and chaos testing. Models the durability internals found in systems like PostgreSQL WAL and RocksDB.

**[Distributed Job Queue](https://github.com/Mohith1612/job-queue-system)** &nbsp;·&nbsp; `Python` `FastAPI` `Redis` `PostgreSQL` `Kubernetes` &nbsp;·&nbsp; [Live](https://queue.mohith16.com)<br>
A priority job queue with exponential-backoff-with-jitter retries, idempotent request handling, per-job execution timeouts, and worker crash recovery. Multi-queue Redis scheduling, PostgreSQL-backed job state, and a Kubernetes (kind) deployment. Load-tested with k6 to find the worker-throughput scaling ceiling.

**[Collaborative Canvas](https://github.com/Mohith1612/canvas)** &nbsp;·&nbsp; `TypeScript` `Yjs` `uWebSockets.js` &nbsp;·&nbsp; [Live](https://canvas.mohith16.com)<br>
A real-time multi-user whiteboard using CRDTs over a binary WebSocket protocol, with per-socket backpressure handling and measured graceful degradation under load.

---

### Open source

**[floci](https://github.com/floci-io/floci)** &nbsp;·&nbsp; `Java` &nbsp;·&nbsp; local AWS emulator &nbsp;·&nbsp; [16 merged PRs](https://github.com/floci-io/floci/pulls?q=is%3Apr+author%3AMohith1612+is%3Amerged)<br>
DynamoDB performance work: [querying only the requested partition](https://github.com/floci-io/floci/pull/6668) and [keeping the live item map instead of copying the table](https://github.com/floci-io/floci/pull/6915) in memory mode. Also [ECS tasks through capacity provider strategies](https://github.com/floci-io/floci/pull/5500), [ephemeral task volumes](https://github.com/floci-io/floci/pull/5511), Cognito auth flows, S3 multipart validation, and SQS/EventBridge pagination fixes.

**[cloud-init](https://github.com/canonical/cloud-init)** &nbsp;·&nbsp; `Python` &nbsp;·&nbsp; Canonical &nbsp;·&nbsp; [9 merged PRs](https://github.com/canonical/cloud-init/pulls?q=is%3Apr+author%3AMohith1612+is%3Amerged)<br>
Fixed a bug where [unlocking an account wiped the user's password hash whenever `passwd -u` printed unrelated stderr](https://github.com/canonical/cloud-init/pull/7191), plus type annotations across the networking, datasource, and templating modules.

**[typeshed](https://github.com/python/typeshed)** &nbsp;·&nbsp; `Python` &nbsp;·&nbsp; [3 merged PRs](https://github.com/python/typeshed/pulls?q=is%3Apr+author%3AMohith1612+is%3Amerged)<br>
Return types for the `docker` library stubs.

In review: [LXD](https://github.com/canonical/lxd/pull/19480) · [SigNoz](https://github.com/SigNoz/signoz/pull/12356) · [SigNoz Helm charts](https://github.com/SigNoz/charts/pull/899) · [SigNoz dashboards](https://github.com/SigNoz/dashboards/pull/397)

---

### Writing

I write about storage internals, performance engineering, and real-world debugging at **[blog.mohith16.com](https://blog.mohith16.com)**.

---

### Tech

**Languages:** Go · Python · TypeScript · SQL<br>
**Infrastructure & tools:** Linux · Docker · Kubernetes · PostgreSQL · Redis · Prometheus · k6 · GitHub Actions · AWS

---

### Reach me

[LinkedIn](https://linkedin.com/in/Mohith16) &nbsp;·&nbsp; [Portfolio](https://mohith16.com) &nbsp;·&nbsp; mohith.work16@gmail.com
