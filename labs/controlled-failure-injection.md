# Lab — Controlled Failure Injection

## Objective
Run controlled latency and network partition tests against a microservice, measure effects on SLOs.

## Steps
1. Choose target microservice with known SLO (e.g., p99 latency < 500ms).
2. Plan blast radius: 1 pod in staging.
3. Inject 200ms–500ms latency with Gremlin for 2 minutes.
4. Measure throughput, errors, latency in dashboards.
5. Incrementally increase intensity if stable.

## Deliverable
- Graphs showing SLI impact
- Recommendation for resilience improvements
