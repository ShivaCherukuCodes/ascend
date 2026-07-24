---
Status: Draft
Owner: Human decision required
Version: 0.1.0
Last Updated: 2026-07-24
Related Documents: [Diagrams](diagrams/README.md), [Security](security.md), [Observability](observability.md), [Engineering standards](../engineering/coding-standards.md)
---
# Deployment
## Why
Reliable delivery and safe recovery are required before Ascend stores sensitive personal data.
## What
Docker and AWS are planned, with separate development, staging, and production environments.
## How
Use immutable builds, managed secrets, controlled configuration, monitoring, backups, and tested rollback paths.
## Future Considerations
Document approved AWS topology, deployment workflows, disaster recovery, and cost controls.
## Open Questions
Human decision required: select the AWS service model, environment accounts, and deployment owner.
