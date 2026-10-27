# 05 — Transactions & Concurrency

Correctness and throughput under concurrent access.

## Topics

- ACID, MVCC, and tuple visibility
- Isolation levels and their anomalies
- Row-level and table-level locks
- Deadlocks: detection, prevention, retries
- `SELECT ... FOR UPDATE` / `SKIP LOCKED` queues
- Serialization failures and idempotent retries
- Long-running transactions and transaction ID wraparound
- Advisory locks

## Layout

- `notes/` — concurrency models and pitfalls
- `examples/` — conflicting sessions demos
- `labs/` — reproduce and resolve deadlocks
