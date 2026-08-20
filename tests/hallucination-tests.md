# Hallucination Testing Guidelines

Validates that the pipeline does not synthesize features, price points, or launch events not found in the raw text.

## Test Scenario
- **Input**: Page source of an official pricing page with plans: Free, Team ($15/mo).
- **Assertion**: Report must not contain references to "Enterprise" tier or custom prices. Any statement of enterprise support must be flagged as "Hypothesis" (unless directly stated in features list).
