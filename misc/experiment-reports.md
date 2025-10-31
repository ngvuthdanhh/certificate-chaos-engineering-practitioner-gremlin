# Experiment Reports

A compilation of experiment outcomes, structured by hypothesis, metrics, and findings.

| ID | Experiment | Hypothesis | Result | Notes |
|----|-------------|-------------|---------|-------|
| 1 | CPU spike on checkout service | System maintains <500ms latency | ✅ Confirmed | Minor increase, within SLO |
| 2 | Network latency 250ms | Retry logic handles gracefully | ⚠️ Partial | Found timeout misconfig |
| 3 | Pod kill in payment service | Auto-recovery works within 30s | ✅ Confirmed | HA policy validated |

**Reflection:** These reports help track progress and identify systemic weaknesses.
