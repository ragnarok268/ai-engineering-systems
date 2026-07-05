# Benchmarks

Benchmarks exist to make AI-assisted engineering claims reviewable.

This hub does not invent benchmark numbers. Where benchmark reports exist, they should be reviewed in the linked repositories. Where exact numbers are unknown or not documented, this repository describes the evaluated concern rather than claiming unsupported results.

## Why Benchmarks Exist

AI-assisted development can produce changes that look correct while failing more subtle engineering requirements. Benchmarks help test whether a system preserves intent, follows constraints, avoids architectural drift, and produces useful verification evidence.

Benchmarks also make it easier for hiring reviewers and engineers to separate stated goals from demonstrated behavior.

## What They Evaluate

Benchmark scenarios may evaluate:

- intent preservation
- constraint compliance
- architectural consistency
- verification quality
- regression prevention
- quality of engineering receipts
- repeatability of analysis
- usefulness of failure evidence

## Example Evaluated Concerns

Intent preservation: Does the resulting change still match the original engineering intent?

Constraint compliance: Did the implementation respect explicit boundaries, non-goals, and operating rules?

Architectural consistency: Did the change preserve expected structure and avoid unreviewed design drift?

Verification quality: Did the verification output identify meaningful mismatches and produce reviewable evidence?

Regression prevention: Did the workflow capture failure patterns in a way that helps prevent repeated mistakes?

## Where To Find Benchmark Evidence

Benchmark evidence, when present, should be reviewed in the relevant project repositories:

- [Agent Memory Layer](https://github.com/ragnarok268/agent-memory-layer)
- [SCP](https://github.com/ragnarok268/scp)
- [IA](https://github.com/ragnarok268/IA)
- [DS2](https://github.com/ragnarok268/DS2)
- [System Failure Analysis](https://github.com/ragnarok268/system-failure-analysis)

Look for benchmark reports, test fixtures, verification receipts, documented test outputs, and example workflows in each repository.

## Evidence Links

Do not invent metrics. Use the linked repository documentation as the source of truth:

- Agent Memory Layer benchmark evidence: see linked repository documentation.
- IA verification evidence: see linked repository documentation.
- DS² structural analysis evidence: see linked repository documentation.
- System Failure Analysis evidence: see linked repository documentation.

## What Reviewers Should Look For

- Whether the benchmark methodology is clearly described.
- Whether claims are supported by artifacts.
- Whether limitations are documented.
- Whether failure cases are captured.
- Whether results are reproducible from repository instructions.

## How Benchmark Evidence Supports Hiring Review

Benchmark evidence helps reviewers assess:

- whether the work is grounded in repeatable engineering concerns
- whether claims are supported by public artifacts
- how the systems behave under defined scenarios
- whether the author thinks in terms of verification rather than presentation alone

The absence of a benchmark number in this hub should be read plainly: no number is being claimed here unless it is documented in the linked project evidence.
