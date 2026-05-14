# project-explainers

Interactive walkthroughs of three production-shaped projects I built — the backend API, the distributed job-queue system, and the React dashboard that consumes the API. Single static HTML file, no framework.

**Live:** https://gabrielchangamire-arch.github.io/project-explainers/

## What's covered

- [#aws-task-manager-api](https://gabrielchangamire-arch.github.io/project-explainers/#aws-task-manager-api) — FastAPI + SQLAlchemy + AWS (EC2, RDS, S3, IAM). Architecture diagram + file walkthrough + request flow.
- [#distributed-job-queue-system](https://gabrielchangamire-arch.github.io/project-explainers/#distributed-job-queue-system) — producer/worker with SQS + DynamoDB, idempotency keys, bounded retries.
- [#react-task-manager-dashboard](https://gabrielchangamire-arch.github.io/project-explainers/#react-task-manager-dashboard) — React + Vite frontend consuming the API. Component tree + state flow + Vitest layers.

Companion to the portfolio at [gabrielchangamire-arch.github.io](https://gabrielchangamire-arch.github.io). Each card on the portfolio deep-links into the matching section here.

## Style

Same dark-mode interactive aesthetic as the [sentiment-tracker-explainer](https://gabrielchangamire-arch.github.io/sentiment-tracker-explainer/). Hand-built HTML, embedded CSS, no JS framework — animations are pure DOM + CSS transitions.

## Run locally

```bash
# Any static server works. Easiest:
python -m http.server 8080
# then open http://localhost:8080/
```
