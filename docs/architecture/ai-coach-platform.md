# AI coach platform

## Responsibility

AI translates a person's context into options and explanations. It does not silently make high-impact decisions or bypass product rules.

## Guardrails

- Retrieve only the minimum relevant, consented context for a request.
- Identify the coach, source context, and reason behind each recommendation.
- Keep deterministic product rules—permissions, plans, safety checks, and state changes—outside model prompts.
- Allow the person to correct context and give feedback on advice.
- Escalate or constrain medical, mental-health, legal, and financial guidance; never present a coach as a professional substitute.

## Coach coordination

The orchestration layer resolves coach input into one clear user-facing recommendation. When goals conflict, Ascend should explain the trade-off and let the person choose.
