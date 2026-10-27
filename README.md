# PostgreSQL Production Playbook

A hands-on, production-focused knowledge base for PostgreSQL: from fundamentals and query tuning to replication, security, scaling, and internals.

## Structure

| # | Section | Focus |
|---|---------|-------|
| 01 | [Fundamentals](./01-Fundamentals/) | Core concepts, data types, DDL, DML, psql |
| 02 | [Advanced SQL & CTEs](./02-Advanced-SQL-and-CTEs/) | Window functions, CTEs, recursive queries, JSON |
| 03 | [Indexes & Query Planning](./03-Indexes-and-Query-Planning/) | Index types, EXPLAIN, planner behavior |
| 04 | [Performance & Optimization](./04-Performance-and-Optimization/) | Tuning, profiling, vacuum, config |
| 05 | [Transactions & Concurrency](./05-Transactions-and-Concurrency/) | MVCC, isolation levels, locking |
| 06 | [Security & Row-Level Security](./06-Security-and-Row-Level-Security/) | Roles, privileges, RLS, auditing |
| 07 | [Database Architecture](./07-Database-Architecture/) | Schema design, normalization, patterns |
| 08 | [Multi-Tenancy](./08-Multi-Tenancy/) | RLS, schema-per-tenant, database-per-tenant |
| 09 | [Scaling & Partitioning](./09-Scaling-and-Partitioning/) | Partitioning, sharding, Citus |
| 10 | [Replication & High Availability](./10-Replication-and-High-Availability/) | Streaming, logical, failover |
| 11 | [Backup & Disaster Recovery](./11-Backup-and-Disaster-Recovery/) | pg_dump, basebackup, PITR |
| 12 | [Monitoring & Troubleshooting](./12-Monitoring-and-Troubleshooting/) | Metrics, queries, runbooks |
| 13 | [Production Best Practices](./13-Production-Best-Practices/) | Checklists, operations, reviews |
| 14 | [Real-World Use Cases](./14-Real-World-Use-Cases/) | Case studies and architectures |
| 15 | [PostgreSQL Internals](./15-PostgreSQL-Internals/) | MVCC, WAL, storage, processes |
| 16 | [PostgreSQL vs SQL Server](./16-PostgreSQL-vs-SQL-Server/) | Comparisons and migrations |
| 17 | [Docker & Deployment](./17-Docker-and-Deployment/) | Docker, Compose, Kubernetes, Ansible |
| 18 | [Scripts & Tools](./18-Scripts-and-Tools/) | Reusable psql, bash, Python, SQL |
| 19 | [Experiments & Benchmarks](./19-Experiments-and-Benchmarks/) | pgbench, datasets, results |

## Conventions

- Every section has a `README.md` describing its scope.
- `notes/` holds explanations and cheat sheets.
- `examples/` holds runnable SQL/setup snippets.
- `labs/` holds guided exercises.
- Use lowercase, hyphenated filenames (e.g. `partial-indexes.md`).
- Prefix ordered content with numbers when sequence matters (e.g. `01-intro.md`).

## Supporting Directories

- `docs/` — cross-section guides, glossary, and shared references.
- `assets/` — diagrams, images, and sample data.
