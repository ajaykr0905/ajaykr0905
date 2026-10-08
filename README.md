# Ajay Kumar Pondugala

**Software Engineer at Cisco | Backend & Distributed Systems | Go, Java, PostgreSQL, Kubernetes**

Bengaluru, India. I build and debug backend services, messaging workflows, durable state, and observable Kubernetes systems. My public engineering work focuses on failure recovery, safe retries, resource lifecycle, and reproducible tests.

[Live portfolio](https://ajaykr-engineering-portfolio.vercel.app) · [LinkedIn](https://www.linkedin.com/in/ajay-kumar-pondugala-3b3b711b8/) · [Email](mailto:ajaykumar.rob27@gmail.com)

Earlier GitHub work: [@ajaykr2712](https://github.com/ajaykr2712).

[![AI Journey CI](https://github.com/ajaykr0905/ai-journey/actions/workflows/ci.yml/badge.svg?branch=main)](https://github.com/ajaykr0905/ai-journey/actions/workflows/ci.yml)
[![Transformer Lab CI](https://github.com/ajaykr0905/fault-tolerant-transformer-lab/actions/workflows/ci.yml/badge.svg?branch=main)](https://github.com/ajaykr0905/fault-tolerant-transformer-lab/actions/workflows/ci.yml)
[![Scale Lab CI](https://github.com/ajaykr0905/distributed-scale-validation-lab/actions/workflows/ci.yml/badge.svg?branch=main)](https://github.com/ajaykr0905/distributed-scale-validation-lab/actions/workflows/ci.yml)
[![Portfolio CI](https://github.com/ajaykr0905/ajay-engineering-portfolio/actions/workflows/ci.yml/badge.svg?branch=main)](https://github.com/ajaykr0905/ajay-engineering-portfolio/actions/workflows/ci.yml)

## Current work

- Finishing the [Distributed Scale Validation Lab](https://github.com/ajaykr0905/distributed-scale-validation-lab) as a durable asynchronous Go backend: separate API, outbox dispatcher, and workers with RabbitMQ and PostgreSQL. External-path recovery and benchmarks are being developed; the existing 10,000-job result is an in-memory functional run, not a broker/database throughput claim.
- Contributing reliability fixes to NATS and Prometheus through reproductions, regression tests, and maintainer review.
- Maintaining the [Fault-Tolerant Transformer Lab](https://github.com/ajaykr0905/fault-tolerant-transformer-lab) as a second case study in deterministic checkpoints and restart verification.

## Open source

- **Merged:** [NATS Python PR #1043](https://github.com/nats-io/nats.py/pull/1043) preserves explicit passwords alongside signed CONNECT credentials. Maintainer-reviewed and merged **2026-10-01 21:36:34 UTC**.
- **Merged:** [Prometheus PR #19882](https://github.com/prometheus/prometheus/pull/19882) restores the active timestamp of previously firing alerts with short `for` durations so they resume firing on the next scheduled evaluation. Maintainer-reviewed and merged **2026-10-05 10:20:20 UTC**; pending-alert restoration and grace-period behavior remain unchanged.
- **Closed, not merged:** [TorchTitan PR #4864](https://github.com/pytorch/torchtitan/pull/4864) was superseded by upstream RL CI work. It is not counted as an accepted contribution.
- [Public pull requests](https://github.com/pulls?q=is%3Apr+author%3Aajaykr0905) track work submitted for external review.

## Core stack

`Go` `Java` `PostgreSQL` `RabbitMQ` `NATS` `Kubernetes` `Prometheus` `OpenTelemetry` `Python`

## Featured engineering

| Project | What it proves | Status |
| --- | --- | --- |
| [Distributed Scale Validation Lab](https://github.com/ajaykr0905/distributed-scale-validation-lab) | Durable acceptance, idempotency, outbox publication, commit-before-ack, failure recovery | Durable path building; memory lab runnable |
| [Merged infrastructure contributions](https://ajaykr-engineering-portfolio.vercel.app/opensource_dev) | NATS credential serialization and Prometheus alert-state restoration, accepted under normal upstream review | Merged |
| [Fault-Tolerant Transformer Lab](https://github.com/ajaykr0905/fault-tolerant-transformer-lab) | Gradient checks, atomic checkpoints, deterministic restart equivalence | Runnable CPU recovery lab |
| [Engineering Portfolio](https://ajaykr-engineering-portfolio.vercel.app) ([source](https://github.com/ajaykr0905/ajay-engineering-portfolio)) | Case studies with exact code, evidence, and limitations | Live |

Every featured claim should resolve to code, a test, a reproducible command, or a versioned artifact. Planned work is labelled as planned rather than shipped.
