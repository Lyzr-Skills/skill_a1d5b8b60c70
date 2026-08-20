# Regression Testing Guidelines

Maintains consistency in threat and opportunity scoring across code updates.

## Setup
Mock standard signals for five competitor runs. Assert that the threat and opportunity score calculations remain identical and prioritize the same risks.
- **Critical threat** must remain ranked higher than **medium threat** under the scoring model formula.
