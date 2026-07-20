# Capability and Repository Map

Capabilities are primary; repositories are linked evidence. Relationships described here support review and reasoning unless a repository documents an actual runtime integration.

| Capability | Primary evidence | What to inspect |
| --- | --- | --- |
| Backend and runtime reliability | [TriageKit](https://github.com/ragnarok268/TriageKit) | FastAPI routes, auth service, SQLAlchemy models, Alembic migration, provider retry classifier, logging, health checks, CI, and tests |
| Verification and intent preservation | [Intent Audit](https://github.com/ragnarok268/IA) | `intent.yaml`, detectors, Markdown/JSON receipts, Canary implementation, fixtures, and tests |
| Repository intelligence | [RepoLens](https://github.com/ragnarok268/RepoLens) | scanner, chunker, embeddings, Chroma storage, retrieval, citations, architecture map, and tests |
| Structural and dependency analysis | [DS2](https://github.com/ragnarok268/DS2) | manifest/import collectors, authority classifier, reports, graphs, receipts, golden artifacts, and tests |
| Engineering memory and context | [SCP](https://github.com/ragnarok268/scp) | YAML Canon, schema, CLI, identity verifier, preflight checks, examples, CI, and tests |
| Failure analysis | [System Failure Analysis](https://github.com/ragnarok268/system-failure-analysis) | case index, evidence manifests, root-cause documents, verification status, audit, and validation receipt |
| Workflow guardrails | [Safety Valve](https://github.com/ragnarok268/safety-valve) | routing pipeline, receipt fields, sandbox lane, examples, architecture decisions, and tests |

## Conceptual Relationships

- SCP records can supply constraints and decision context during a later review.
- DS2 reports can supply structural evidence during a later review.
- Intent Audit can evaluate declared intent and emit verification receipts.
- Failure case studies can inform future requirements and regression criteria.
- Safety Valve demonstrates a separate pre-inference policy boundary.
- TriageKit and RepoLens stand as independent implementations; this hub does not claim they call the other tools at runtime.

These relationships do not establish a single integrated product or deployed platform.

## Additional Supporting Work

[Agent Memory Layer](https://github.com/ragnarok268/agent-memory-layer), [GREEN](https://github.com/ragnarok268/GREEN-public), and [Halt Invariant](https://github.com/ragnarok268/halt-invariant) remain available as supporting context. They are not used to replace the stronger implementation evidence above.

## Review Navigation

See [README.md](README.md) for the central evidence matrix, [ARCHITECTURE.md](ARCHITECTURE.md) for system boundaries, [BENCHMARKS.md](BENCHMARKS.md) for measurement rules, and [LIMITATIONS.md](LIMITATIONS.md) for evidence boundaries.
