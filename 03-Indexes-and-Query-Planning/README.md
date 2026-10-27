# 03 — Indexes & Query Planning

Understand how PostgreSQL chooses plans and how to index for real workloads.

## Topics

- B-tree, hash, GiST, GIN, BRIN, and SP-GiST indexes
- Composite, partial, expression, and covering indexes
- Index-only scans and visibility map
- `EXPLAIN` and `EXPLAIN (ANALYZE, BUFFERS)`
- Planner statistics, `pg_statistic`, and cost model
- Join strategies: nested loop, hash, merge
- Common causes of bad plans

## Layout

- `notes/` — index and planner theory
- `examples/` — before/after index experiments
- `labs/` — read a plan, then fix it
