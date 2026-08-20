# Executive Summary Prompt

```markdown
Compile the final executive report.

Input Data:
- Competitor profiles: {{ competitors }}
- Recent Events: {{ recent_events }}
- High-priority Threats: {{ threats }}
- High-priority Opportunities: {{ opportunities }}
- Inference engine results: {{ inferences }}

Strict Constraint:
- Explicitly split verified facts and inferences.
- List recommendations only when evidence supports an actionable conclusion.
- Embed citations to the Evidence Vault.
```
