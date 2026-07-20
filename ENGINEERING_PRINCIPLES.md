# Engineering Principles

## Explicit Requirements

Define expected behavior, acceptance evidence, and non-goals before implementation.

## Constraints and Invariants

Identify boundaries that must remain true across implementation and failure paths. Encode them in tests, schemas, contracts, or review checklists where practical.

## Architecture Before Implementation Where Appropriate

Establish responsibilities, data flow, dependencies, and failure boundaries before editing when risk or complexity warrants it.

## Deterministic Validation Where Practical

Prefer repeatable checks, structured records, stable outputs, and explicit schemas when they reduce ambiguity. Do not imply that all engineering judgment can be automated.

## Evidence Over Claims

Use source, tests, CI, receipts, reports, examples, documented measurements, and commit history. Distinguish executed evidence from estimates, hypotheses, and plans.

## Cause-to-Effect Reasoning

Explain the mechanism connecting a condition to an outcome. Separate direct evidence from inference, especially during failure analysis.

## Regression Protection

A correction is incomplete when the same failure can silently recur. Add tests or deterministic checks where practical and document any remaining verification gap.

## Repository and Dependency Awareness

Verify the active repository before work. Treat dependencies as behavior, authority, maintenance, and risk surfaces that require review.

## Inspectable Engineering Context

Preserve expensive-to-rediscover decisions, constraints, rationale, and revisit conditions without pretending to reconstruct history that was not recorded.

## Human Responsibility for AI-Assisted Work

AI tools may accelerate drafting, exploration, testing, and mechanical edits. Humans remain responsible for architecture, constraints, review, verification, acceptance, and release decisions.

## Honest Boundaries

Distinguish production-oriented practices from production deployment. Do not infer users, scale, adoption, contribution status, or benchmark results from implementation intent alone.
