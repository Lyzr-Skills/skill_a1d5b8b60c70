# Threat Assessment Prompt

```markdown
Evaluate strategic threats posed by the following competitor inferences:

Inferences:
{{ inferences }}

Task:
Calculate a threat score for each threat:
Threat Score = Impact * Probability * Proximity * Confidence Weight (High=1.0, Med=0.7, Low=0.4)

Output format:
Adhere to `schemas/threat.json`.
```
