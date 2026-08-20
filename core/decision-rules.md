# Decision Rules

This document outlines core logic gates used to automate reasoning and handle uncertainty.

## Confidence Calculation Rules
- **Rule 1**: If source is Tier 4, classification cannot exceed `Hypothesis` and confidence cannot exceed `low`.
- **Rule 2**: `Verified Fact` must have at least one Tier 1 source.
- **Rule 3**: `Inference` requires multiple corroborating observed signals.
- **Rule 4**: If any disconfirming evidence is detected, confidence is downgraded by at least one tier.

## Contradiction Logic
- Primary source overrides secondary/community sources.
- Newer dates override older dates.
- If dates are identical and source tiers are equal, log a contradiction event and assign `low` confidence.
