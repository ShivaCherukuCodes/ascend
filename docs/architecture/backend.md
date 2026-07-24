---
Status: Proposed
Owner: Human decision required
Version: 0.1.0
Last Updated: 2026-07-24
Related Documents: [Overview](overview.md), [Domain model](domain-model.md), [API](api.md), [Database](database.md)
---
# Backend
## Why
The backend must protect domain behavior from delivery and vendor concerns.
## What
The planned backend is Java and Spring Boot, organized as a modular monolith.
## How
Organize modules around bounded contexts; keep application, domain, infrastructure, and API adapters explicit; do not let business logic depend directly on LLM providers.
## Future Considerations
Document module contracts, dependency rules, build tooling, and coding conventions after they are approved.
## Open Questions
Human decision required: confirm Java/Spring Boot versions, build tool, and first bounded contexts.
