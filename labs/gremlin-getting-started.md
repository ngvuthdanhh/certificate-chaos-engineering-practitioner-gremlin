# Lab — Gremlin: Getting Started (Safe First Attack)

## Objective
Install Gremlin agent in a staging environment and run your first safe CPU attack with minimal blast radius.

## Prerequisites
- Gremlin organization or trial account.
- Staging host or Kubernetes cluster under your control.
- Monitoring (Prometheus/Grafana) hooked into service.

## Steps
1. Create Gremlin account, invite team members.
2. Install Gremlin agent on a staging host (follow Gremlin docs).
3. Verify agent online in Gremlin UI.
4. Run a “Hello World” attack: 1% CPU for 30s on a single host.
5. Observe metrics and verify rollback/kill-switch ability.

## Deliverable
- Screenshot of successful attack in Gremlin UI.
- Short report: hypothesis, SLI selected, outcome, learnings.
