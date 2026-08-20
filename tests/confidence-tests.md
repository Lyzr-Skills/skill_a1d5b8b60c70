# Confidence Testing Guidelines

Tests confidence allocation rules.

## Scenarios
1. **Tier 4 Source Only**: Speculation of feature launch on Twitter.
   - *Assert*: Confidence must be `low` or `unverified`.
2. **Multiple Corroborating Sources**: Press announcement + Documentation page.
   - *Assert*: Confidence must be `high`.
