# 05 — Failure Injection Methods

**Common types**
- CPU, Memory, Disk I/O saturation
- Network latency/loss, packet corruption
- Process / container / VM termination
- DNS failures, dependency outages
- Chaos at the orchestration layer (Kubernetes pod kill, node drain)

**Best practices**
- Start with low intensity; observe and increment.
