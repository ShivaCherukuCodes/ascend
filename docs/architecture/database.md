---
Status: Draft
Owner: Human decision required
Version: 0.1.0
Last Updated: 2026-07-24
Related Documents: [Domain model](domain-model.md), [Security](security.md), [Deployment](deployment.md), [Backend](backend.md)
---
# Database
## Why
Personal data requires durable modeling, privacy controls, and recoverability.
## What
PostgreSQL is the planned primary relational store.
## How
Use explicit schema migrations, constraints, least-privilege access, backups, and data classification tied to domain boundaries.
## Future Considerations
Define tenancy, retention, audit, encryption, and restoration requirements when the MVP and compliance scope are known.
## Open Questions
Human decision required: confirm tenancy model, data residency, and retention policy.
