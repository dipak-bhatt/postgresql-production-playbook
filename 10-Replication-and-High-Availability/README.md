# 10 — Replication & High Availability

Keep data available and survive node failures.

## Topics

- Streaming replication and hot standbys
- Logical replication and publications/subscriptions
- Synchronous vs. asynchronous trade-offs
- `pg_basebackup` and standby bootstrap
- Failover with Patroni, repmgr, and pg_auto_failover
- Split-brain prevention and fencing
- Lag monitoring and conflict handling

## Layout

- `notes/` — topology and failover design
- `examples/` — replica configuration samples
- `labs/` — promote a standby, simulate failure
- `streaming/` — physical replication assets
- `logical/` — logical replication assets
- `failover/` — HA orchestration assets
