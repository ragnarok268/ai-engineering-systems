# Project Map

This map lists the core and supporting systems in the AI Engineering Systems ecosystem.

## Core Systems

### Agent Memory Layer

Repository: [https://github.com/ragnarok268/agent-memory-layer](https://github.com/ragnarok268/agent-memory-layer)

One-sentence purpose: Repository-local engineering memory for AI-assisted software development.

Problem addressed: AI coding sessions often lose project context, architectural intent, workflow constraints, and handoff knowledge.

How it connects: Agent Memory Layer provides working project memory that complements SCP decision records and supports more consistent IA verification and AI-assisted implementation.

Best reviewer path: Start with its README, then review examples of repository-local memory and workflow preservation.

### SCP

Repository: [https://github.com/ragnarok268/scp](https://github.com/ragnarok268/scp)

One-sentence purpose: Persistent engineering knowledge and decision-preservation model.

Problem addressed: Important decisions, rationale, constraints, milestones, and future traps are often lost between sessions and contributors.

How it connects: SCP gives the ecosystem a durable reasoning layer that can inform Agent Memory Layer, IA verification context, and engineering review.

Best reviewer path: Read its README, Canon, schema, and example records.

### IA

Repository: [https://github.com/ragnarok268/IA](https://github.com/ragnarok268/IA)

One-sentence purpose: Deterministic verification system for checking AI-generated changes against engineering intent.

Problem addressed: AI-generated changes can appear plausible while drifting from the original intent, violating constraints, or changing architecture in unreviewed ways.

How it connects: IA consumes intent, constraints, and implementation evidence. It can be informed by Agent Memory Layer, SCP records, and DS2 structural reports.

Best reviewer path: Review the verification model, example receipts, tests, and any benchmark reports.

### DS²

Repository: [https://github.com/ragnarok268/DS2](https://github.com/ragnarok268/DS2)

One-sentence purpose: Dependency surface and structural analysis system.

Problem addressed: AI-assisted changes can miss dependency surfaces, inherited authority, framework behavior, and structural risk.

How it connects: DS² supports IA and human review by exposing dependency relationships, structural risk, and capability surfaces.

Best reviewer path: Review example reports, dependency graphs, receipts, and tests.

## Supporting Systems

### System Failure Analysis

Repository: [https://github.com/ragnarok268/system-failure-analysis](https://github.com/ragnarok268/system-failure-analysis)

One-sentence purpose: Framework for deterministic root-cause analysis, Failure Fingerprints, regression prevention, and evidence-driven debugging.

Problem addressed: Teams and AI sessions often rediscover the same failure patterns without converting them into reusable prevention knowledge.

How it connects: Failure analysis can feed future SCP records, improve verification criteria, and support regression prevention.

Best reviewer path: Review the failure taxonomy, examples, and regression-prevention artifacts.

### Safety Valve

Repository: [https://github.com/ragnarok268/safety-valve](https://github.com/ragnarok268/safety-valve)

One-sentence purpose: Deterministic guardrail concept for AI-assisted engineering workflows.

Problem addressed: AI-assisted workflows need bounded execution, constraint checks, and clear stop conditions.

How it connects: Safety Valve supports the ecosystem's guardrail layer and complements IA verification.

Best reviewer path: Review the core concept, examples, and limitations.

### GREEN

Repository: [https://github.com/ragnarok268/GREEN-public](https://github.com/ragnarok268/GREEN-public)

One-sentence purpose: Supporting engineering framework for reliable AI workflow development.

Problem addressed: Reliable AI workflow development benefits from explicit structure, repeatable practices, and reviewable artifacts.

How it connects: GREEN supports the broader workflow discipline behind the core systems.

Best reviewer path: Review the framework documentation and examples.

### Halt Invariant

Repository: [https://github.com/ragnarok268/halt-invariant](https://github.com/ragnarok268/halt-invariant)

One-sentence purpose: Research and engineering work related to deterministic stopping conditions and reliable AI behavior.

Problem addressed: AI systems and workflows can continue past useful boundaries without clear stopping criteria.

How it connects: Halt Invariant informs the guardrail and reliability research layer.

Best reviewer path: Review the research notes, examples, and stated limitations.
