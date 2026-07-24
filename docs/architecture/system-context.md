# System context

Ascend will begin as a modular web application, separating the experience layer, product domain, AI orchestration, and durable data access while avoiding premature distributed complexity.

## Logical boundaries

- **Experience:** Next.js frontend for Today, Journey, Plans, Inbox, and Me.
- **Application domain:** Spring Boot services for identity, plans, check-ins, progress, preferences, and audit-worthy decisions.
- **AI orchestration:** a controlled layer that prepares relevant context, calls approved models/tools, validates outputs, and records explanations.
- **Data:** PostgreSQL for core product data; additional storage is introduced only with a documented need.
- **Operations:** configuration, observability, deployment, and incident response practices that protect reliability and privacy.

External integrations and model providers are treated as dependencies, not sources of truth. Product data and user choices remain governed by Ascend's domain boundaries.
