# Hiring Review Guide

Use this guide to evaluate independent engineering evidence for three role families.

## Role Fit

### AI Systems & Software Reliability Engineer

**Demonstrated evidence:** deterministic intent verification in Intent Audit; provider-failure and retry behavior in TriageKit; failure-mechanism case studies; deterministic guardrail routing.

**Supporting evidence:** SCP context preservation and DS2 authority-surface analysis.

**Growth areas:** operational deployment evidence, sustained production traffic, and external contribution outcomes.

### Backend Software Engineer

**Demonstrated evidence:** TriageKit's FastAPI API, authentication, persistence, migrations, structured logging, request IDs, health endpoints, bounded retries, Docker Compose, CI, and automated tests.

**Supporting evidence:** Python CLIs, schemas, persistence, deterministic outputs, and test suites in RepoLens, SCP, DS2, and Intent Audit.

**Growth areas:** deployed service telemetry, load testing, and production operations evidence.

### Developer Tooling / Repository Intelligence Engineer

**Demonstrated evidence:** RepoLens indexing/retrieval/citations; DS2 dependency and authority reports; SCP repository identity/preflight guards; Intent Audit verification receipts.

**Supporting evidence:** documentation quality, reviewer workflows, and committed examples.

**Growth areas:** broader repository fixtures, measured performance, packaging/adoption evidence, and external feedback.

## Suggested Review Order

1. [README.md](README.md) and its capability matrix.
2. [TriageKit](https://github.com/ragnarok268/TriageKit).
3. [Intent Audit](https://github.com/ragnarok268/IA).
4. [RepoLens](https://github.com/ragnarok268/RepoLens).
5. [System Failure Analysis](https://github.com/ragnarok268/system-failure-analysis).
6. [ARCHITECTURE.md](ARCHITECTURE.md), [ENGINEERING_PRINCIPLES.md](ENGINEERING_PRINCIPLES.md), and [LIMITATIONS.md](LIMITATIONS.md).

## Interview Topics

- Which transient failures TriageKit retries and why retries are bounded
- How Intent Audit converts explicit intent into deterministic findings
- How RepoLens keeps answers source-grounded
- What DS2 can and cannot infer from static dependencies and imports
- How SCP protects repository identity and preserves adoption-forward decisions
- How direct, inferred, and missing evidence are separated in failure case studies
- What additional evidence would be required before claiming production operation

## Evidence Boundary

These documents support hiring review; they do not claim employment under the target titles. No external pull requests have been submitted yet, and no production deployment, traffic, customer use, commercial adoption, or maintainer acceptance is claimed.
