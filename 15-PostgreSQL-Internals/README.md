# 15 — PostgreSQL Internals

How PostgreSQL actually works under the hood.

## Topics

- Process model: postmaster, backends, background workers
- Memory: shared buffers, WAL buffers, work_mem
- Storage: pages, tuples, TOAST, free space map
- MVCC: xmin/xmax, snapshots, tuple visibility
- WAL, checkpoints, and crash recovery
- Vacuum, freezing, and transaction ID wraparound
- Planner and executor internals

## Layout

- `notes/` — internals explanations
- `examples/` — pageinspect and WAL demos
- `labs/` — inspect pages and WAL
- `mvcc/` — concurrency internals assets
- `wal/` — write-ahead logging assets
- `storage/` — physical storage assets
