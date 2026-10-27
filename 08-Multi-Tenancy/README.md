# 08 — Multi-Tenancy

Isolation models and operational trade-offs for shared PostgreSQL.

## Topics

- Model comparison: shared table, schema-per-tenant, database-per-tenant
- RLS-based tenancy and policy performance
- Tenant context propagation (`SET LOCAL`)
- Noisy-neighbor management and per-tenant limits
- Migrations across many schemas/databases
- Tenant onboarding and offboarding

## Layout

- `notes/` — model selection guidance
- `examples/` — end-to-end tenancy samples
- `labs/` — build isolation with RLS
- `rls/` — row-level security specific content
- `schema-per-tenant/` — schema isolation assets
- `database-per-tenant/` — database isolation assets
