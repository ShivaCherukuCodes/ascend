---
Status: Draft
Owner: Human decision required
Version: 0.2.0
Last Updated: 2026-07-24
Related Documents:
  - [Documentation index](INDEX.md)
  - [Documentation-first ADR](decisions/ADR-001.md)
  - [Product philosophy](product/philosophy.md)
---

# Ascend Knowledge Base

> "We're not building software. We're designing a lifelong relationship between people and their future selves."

## Why

This knowledge base preserves the reasoning behind Ascend so contributors can build deliberately for the long term.

## What

`docs/` is the source of truth for product direction, architecture, design, engineering standards, decisions, and research. Start at the [documentation index](INDEX.md).

The system is organized into `vision`, `product`, `architecture`, `design`, `engineering`, `decisions`, and `research`. `decisions/` is the only ADR location. Architecture diagrams live in [architecture/diagrams](architecture/diagrams/README.md).

## How

Every document must state why it exists, what it covers, how it should be used, future considerations, and open questions. Important implementation and product choices must be recorded as ADRs before implementation when practical.

## Future Considerations

Add reusable templates only after the documentation structure and review workflow are finalized.

## Open Questions

Human decision required: define documentation ownership, approval rules, and review intervals.
