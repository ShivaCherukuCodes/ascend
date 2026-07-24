---
Status: Proposed
Owner: Human decision required
Version: 0.1.0
Last Updated: 2026-07-24
Related Documents: [Domain model](domain-model.md), [Security](security.md), [Observability](observability.md), [Product philosophy](../product/philosophy.md)
---
# AI Architecture
## Why
AI must strengthen trust and product value without controlling business logic or exposing private data carelessly.
## What
AI is an isolated capability behind domain services; providers, prompts, retrieval, memory, and tools are adapters, not domain dependencies.
## How
Use provider-neutral interfaces, versioned prompts, evaluation suites, scoped MCP tools, consent-aware memory, and safety/cost/quality telemetry.
## Future Considerations
Adopt RAG, embeddings, vector storage, or agent orchestration only for approved use cases with retention and evaluation rules.
## Open Questions
Human decision required: identify initial AI use cases, approved providers, and data-sharing boundaries.
