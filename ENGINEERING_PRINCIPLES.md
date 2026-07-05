# Engineering Principles

## Architecture-First Engineering

Start with system boundaries, constraints, responsibilities, and expected evidence before implementation. AI-assisted coding is more useful when the architecture is explicit.

## Verification-First Engineering

Treat verification as part of the design, not a final checkbox. A change should be reviewable against intent, constraints, tests, and evidence.

## Cause to Effect Reasoning

Prefer explanations that connect cause, mechanism, and outcome. This is especially important when debugging AI-assisted changes or reviewing system failures.

## Deterministic Where Practical

Use deterministic checks, structured records, explicit schemas, and repeatable workflows where they provide clarity. Not every engineering concern can be fully deterministic, but practical determinism reduces ambiguity.

## Evidence Over Claims

Prefer public artifacts, tests, benchmark reports, receipts, examples, and documented limitations over broad claims.

## Engineering Memory

Important context should survive across sessions and contributors. Decisions, constraints, rationale, and future traps should be preserved when they are expensive to rediscover.

## Dependency Awareness

Dependencies carry behavior, authority, maintenance burden, and risk. AI-assisted development should include review of dependency surfaces and inherited execution authority.

## Failure Fingerprints

Failures should be converted into reusable patterns where possible. A good failure record helps future work avoid repeating the same mistake.

## Regression Prevention

Debugging is incomplete if the same issue can silently recur. Tests, receipts, documented failure patterns, and verification checks all contribute to regression prevention.

## Documentation as Engineering

Documentation is part of the system. It explains intent, constraints, architecture, review paths, evidence, limitations, and future work.

## AI as Accelerator, Not Authority

AI tools can accelerate implementation, exploration, summarization, and testing. They do not own architecture, acceptance, verification, or release decisions.
