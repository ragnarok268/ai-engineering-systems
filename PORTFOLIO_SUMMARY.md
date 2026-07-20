# Engineering Evidence Summary

Independent engineering work completed 2023–Present, organized for three related review paths:

- **Primary:** AI Systems & Software Reliability Engineer
- **Additional:** Backend Software Engineer — Python, FastAPI, reliability engineering
- **Additional:** Developer Tooling / Repository Intelligence Engineer

These are positioning statements, not employment claims.

## Strongest Evidence

| Capability | Repository | Demonstrated implementation |
| --- | --- | --- |
| Reliable Python backend engineering | [TriageKit](https://github.com/ragnarok268/TriageKit) | FastAPI, JWT auth, SQLAlchemy, Alembic, logging, request IDs, bounded retries, health checks, Docker Compose, CI, and tests |
| Deterministic intent verification | [Intent Audit](https://github.com/ragnarok268/IA) | Local intent contract, deterministic detectors, Markdown/JSON receipts, Canary diagnostics, fixtures, and tests |
| Repository intelligence | [RepoLens](https://github.com/ragnarok268/RepoLens) | Deterministic indexing/chunking, Chroma persistence, offline embeddings, citations, architecture map, and tests |
| Failure investigation | [System Failure Analysis](https://github.com/ragnarok268/system-failure-analysis) | Five case studies separating direct evidence, reconstruction, missing verification, and regression proposals |
| Context and boundary preservation | [SCP](https://github.com/ragnarok268/scp) | Adoption-forward decision records, Canon validation, identity checks, preflight guards, CI, and tests |
| Dependency and authority analysis | [DS2](https://github.com/ragnarok268/DS2) | Dependency/import maps, exposure classification, reports, stable-hash receipts, golden artifacts, CI, and tests |
| Deterministic guardrails | [Safety Valve](https://github.com/ragnarok268/safety-valve) | Local `ALLOW`/`BLOCK`/`SANDBOX` routing, policy receipts, examples, and tests |

## Engineering Signals

- Explicit requirements, constraints, and invariants
- Architecture and boundary reasoning
- Deterministic validation where practical
- Automated tests and regression protection
- Inspectable receipts, reports, and citations
- Root-cause and failure-mechanism analysis
- Honest differentiation between observed evidence and future work

## Role Alignment

**AI systems and reliability:** Intent Audit, TriageKit, System Failure Analysis, Safety Valve, and SCP.

**Backend software engineering:** TriageKit is the clearest end-to-end backend implementation; RepoLens, SCP, and DS2 add Python tooling, persistence, validation, and CI evidence.

**Developer tooling and repository intelligence:** RepoLens, DS2, SCP, and Intent Audit.

## Boundaries

The work is independent and open source. Repository maturity and evidence depth vary. No production traffic, production-scale operation, employer or customer relationship, commercial deployment, enterprise adoption, submitted external pull request, or merged contribution is claimed. See [LIMITATIONS.md](LIMITATIONS.md).
