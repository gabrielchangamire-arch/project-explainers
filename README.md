# project-explainers

Interactive walkthroughs of seven production-shaped projects I built, spanning backend, distributed systems, frontend, GenAI, production engineering, modern C++, and Solana. Single static HTML file, no framework.

**Live:** https://gabrielchangamire-arch.github.io/project-explainers/

## What's covered

- [#aws-task-manager-api](https://gabrielchangamire-arch.github.io/project-explainers/#aws-task-manager-api) — FastAPI + SQLAlchemy + AWS (EC2, RDS, S3, IAM). Architecture diagram + file walkthrough + request flow.
- [#distributed-job-queue-system](https://gabrielchangamire-arch.github.io/project-explainers/#distributed-job-queue-system) — producer/worker with SQS + DynamoDB, idempotency keys, bounded retries.
- [#react-task-manager-dashboard](https://gabrielchangamire-arch.github.io/project-explainers/#react-task-manager-dashboard) — React + Vite frontend consuming the API. Component tree + state flow + Vitest layers.
- [#genai-ad-creative-studio](https://gabrielchangamire-arch.github.io/project-explainers/#genai-ad-creative-studio) — FastAPI + React creative workspace with mock/provider generation modes.
- [#cpp-matching-engine](https://gabrielchangamire-arch.github.io/project-explainers/#cpp-matching-engine) — C++20 price-time matching, deterministic concurrent ingestion, differential testing, fuzzing, and benchmarks.
- [#fleetpulse](https://gabrielchangamire-arch.github.io/project-explainers/#fleetpulse) — Linux fleet telemetry, durable ingestion, stream workers, SLOs, and controlled recovery drills.
- [#solana-developer-passport](https://gabrielchangamire-arch.github.io/project-explainers/#solana-developer-passport) — Rust/Anchor Passport and Milestone PDAs, Wallet Standard signing, authority constraints, LiteSVM security tests, and live devnet evidence.

Companion to the portfolio at [gabrielchangamire-arch.github.io](https://gabrielchangamire-arch.github.io). Each card on the portfolio deep-links into the matching section here.

## Style

Same dark-mode interactive aesthetic as the [sentiment-tracker-explainer](https://gabrielchangamire-arch.github.io/sentiment-tracker-explainer/). Hand-built HTML, embedded CSS, no JS framework — animations are pure DOM + CSS transitions.

## Run locally

```bash
# Any static server works. Easiest:
python -m http.server 8080
# then open http://localhost:8080/
```
