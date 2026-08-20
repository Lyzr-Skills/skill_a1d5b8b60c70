# Inference Testing Guidelines

Validates that inferences are not merged with fact.

## Test Scenario
- **Input**: "Competitor Y hired an Enterprise VP Sales. They also added a governance page."
- **Fact check**: "Competitor Y hired VP of Enterprise Sales" -> Verified Fact.
- **Inference check**: "Competitor Y is shifting strategy to target enterprise customers" -> Inference (Level 3).
- **Assertion**: If the report outputs "Competitor Y is targeting enterprise customers" as a Fact, the test fails.
