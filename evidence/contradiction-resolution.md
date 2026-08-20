# Contradiction Resolution

Handles contradictory reports without silent merging or arbitrary deletion.

## Resolution Workflow

```mermaid
graph TD
    Conflict["Detect Contradiction"] --> Tiers["Compare Source Tiers"]
    Tiers -->|Tier 1 vs Tier 3| Primary["Prefer Primary Source"]
    Tiers -->|Equal Tiers| Dates["Compare Dates"]
    Dates -->|Newer vs Older| Newer["Prefer Newer Date"]
    Dates -->|Equal Dates| Warn["Log Contradiction & Lower Confidence"]
```

## Ground Rules
1. **Never Silently Merge**: Log both claims explicitly inside the report.
2. **Log Dates**: Flag older information as "stale" instead of deleting it.
3. **Trace Uncertainty**: Lower confidence of the related `Inference` to `low` or `unverified` if the contradiction is unresolved.
