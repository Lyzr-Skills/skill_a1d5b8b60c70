# Contradiction Testing Guidelines

Tests contradiction resolution policy.

## Scenario
- **Source A (Official Pricing Page, 2026-08-20)**: "Pro starts at $99".
- **Source B (Reddit post, 2026-08-19)**: "Pro tier starts at $79".

## Assertions
1. The agent chooses $99 (newest, primary source).
2. The agent logs both inputs.
3. The agent does not silently merge or average the values to $89.
