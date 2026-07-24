---
Status: Draft
Owner: Human decision required
Version: 0.1.0
Last Updated: 2026-07-24
Related Documents:
  - [Documentation home](../INDEX.md)
  - [Documentation guide](../README.md)
  - [ADR index](../decisions/README.md)
---
# Documentation Quality Standard
## Why
Documentation needs a shared standard to prevent drift, empty scaffolding, and unsupported claims.
## What
Every document must include front matter with `Status`, `Owner`, `Version`, `Last Updated`, and relative `Related Documents` links. Status is exactly: `Draft`, `Review`, `Approved`, `Implemented`, `Deprecated`, or `Archived`.

Every document must answer: why it exists; what it solves or defines; who owns it; how it is maintained; related decisions; open questions; and future considerations.
## How
Use the headings `Why`, `What`, `How`, `Future Considerations`, and `Open Questions`. State ownership in front matter; link relevant ADRs; write `Human decision required.` for unknowns; and update version/date/status after material changes. Do not fabricate requirements, decisions, owners, evidence, or implementation status.
## Future Considerations
Create reusable templates only after the documentation structure and governance are finalized.
## Open Questions
Human decision required: define review cadence, version semantics, and approval authority.
