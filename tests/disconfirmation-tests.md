# Disconfirmation Testing Guidelines

Validates that the agent actively seeks and documents disconfirming evidence.

## Scenario
- **Hypothesis**: Competitor Z is sunsetting their Free tier.
- **Supporting signals**: Free tier limits reduced, user threads complaining about limit warnings.
- **Disconfirming signals**: Free signup button remains active, official changelog says "No plans to sunset Free".

## Assertions
1. The agent must list the disconfirming signal in the final inference.
2. Inference confidence must be downgraded to `medium` or `low`.
