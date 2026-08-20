# Classification Prompt

```markdown
Classify the following evidence record into one of the four competitive intelligence levels:
1. Verified Fact
2. Observed Signal
3. Inference
4. Hypothesis

Evidence:
{{ evidence }}

Rules:
- Level 1 (Verified Fact): Direct primary source.
- Level 2 (Observed Signal): Measurable change (e.g. pricing page delta).
- Level 3 (Inference): Strategic deduction.
- Level 4 (Hypothesis): Strategic possibility.

Assign the level and explain your reasoning.
```
