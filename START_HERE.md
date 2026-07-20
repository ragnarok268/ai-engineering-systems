# Start Here

This guide routes reviewers through public evidence from independent engineering work completed 2023–Present.

## Recruiter or Hiring Manager — approximately 5 minutes

Start with capabilities and role fit:

1. Read [README.md](README.md).
2. Scan its capability-to-evidence matrix.
3. Review [TriageKit](https://github.com/ragnarok268/TriageKit) for backend reliability.
4. Review [Intent Audit](https://github.com/ragnarok268/IA) for deterministic verification.
5. Open [HIRING_REVIEW_GUIDE.md](HIRING_REVIEW_GUIDE.md).

## Backend or Python Review — approximately 15 minutes

Focus on implementation evidence:

1. TriageKit: FastAPI, JWT authentication, SQLAlchemy persistence, Alembic migration, structured logging, request IDs, bounded retries, health endpoints, Docker Compose, CI, and tests.
2. RepoLens: local indexing, Chroma persistence, citations, retrieval tests, and architecture mapping.
3. DS2: manifest/import scanning, authority classification, deterministic outputs, and golden tests.
4. SCP: YAML decision records, repository identity checks, preflight guards, CI, and tests.

## AI Systems and Reliability Review — approximately 15 minutes

1. Intent Audit: explicit intent, constraint checks, receipts, Canary diagnostics, and tests.
2. TriageKit: provider boundaries, transient-failure handling, reliability metadata, and observability.
3. System Failure Analysis: evidence-bounded case studies and verification gaps.
4. Safety Valve: deterministic pre-inference routing and receipt invariants.
5. [ARCHITECTURE.md](ARCHITECTURE.md) and [ENGINEERING_PRINCIPLES.md](ENGINEERING_PRINCIPLES.md).

## Developer Tooling Review — approximately 15 minutes

Review [RepoLens](https://github.com/ragnarok268/RepoLens), [DS2](https://github.com/ragnarok268/DS2), [SCP](https://github.com/ragnarok268/scp), and [Intent Audit](https://github.com/ragnarok268/IA), following the tests and artifact links in the README.

## Full Technical Review — 30 minutes or more

Read [ARCHITECTURE.md](ARCHITECTURE.md), [PROJECT_MAP.md](PROJECT_MAP.md), [AI_NATIVE_WORKFLOW.md](AI_NATIVE_WORKFLOW.md), [ENGINEERING_PRINCIPLES.md](ENGINEERING_PRINCIPLES.md), [BENCHMARKS.md](BENCHMARKS.md), [LIMITATIONS.md](LIMITATIONS.md), and [ROADMAP.md](ROADMAP.md). Compare hub claims with linked source, tests, CI, receipts, and limitations.

## Evidence Boundary

This is independent and open-source work. Production-oriented practices are identified where code supports them, but no production deployment, production traffic, customers, commercial adoption, or external pull-request activity is claimed.
