# ADR-0002: Start as a modular monolith

**Status:** Accepted

**Date:** 2026-07-24

## Context

Ascend needs clear product boundaries and dependable iteration, but early product learning does not justify the operational cost of distributed services.

## Decision

Begin with a modular monolith: a Next.js experience layer and Spring Boot application with explicit domain modules and an isolated AI orchestration boundary. Extract services only when measured scale, ownership, or reliability needs justify it.

## Consequences

- Faster iteration and simpler operations during the foundation stage.
- Module boundaries must be maintained deliberately to prevent a tangled codebase.
- Future extraction remains possible without making it a present cost.

## Alternatives considered

Starting with microservices was rejected because it would add operational complexity before the product and domain boundaries are validated.
