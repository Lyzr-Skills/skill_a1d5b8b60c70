# Change Detection Prompt

```markdown
Compare the previous state snapshot of Competitor {{ competitor_name }} with current observations.

Previous State:
{{ previous_state }}

Current Observations:
{{ current_observations }}

Output:
Extract any verified changes. Format each change as an `IntelligenceEvent` adhering to `schemas/intelligence-event.json`.
```
