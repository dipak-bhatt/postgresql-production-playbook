# 04 — Performance & Optimization

Diagnose and fix slow queries, bloated tables, and misconfigured instances.

## Topics

- `pg_stat_statements` and query profiling
- Autovacuum tuning and bloat measurement
- Memory and planner settings (`work_mem`, `shared_buffers`, `effective_cache_size`)
- Connection pooling (PgBouncer)
- Lock and wait event analysis
- Batch loading and bulk operations
- `pg_prewarm`, `pg_repack`, `CLUSTER`

## Layout

- `notes/` — tuning guidance and checklists
- `examples/` — configs and diagnostic queries
- `labs/` — measure, change, re-measure
