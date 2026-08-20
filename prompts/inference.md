# Inference Prompt

```markdown
Formulate strategic inferences based on these signals: {{ signals }}.

De-biasing rules:
1. Search and list potential DISCONFIRMING evidence: what facts suggest this inference is WRONG?
2. Explicitly rate confidence: High, Medium, Low.
3. Keep inferences separated from verified facts.

Output format:
Adhere strictly to `schemas/inference.json`.
```
