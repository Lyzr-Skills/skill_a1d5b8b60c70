# Evidence Validation Prompt

```markdown
Validate the following raw competitive intelligence data.

Raw Evidence:
- Content: {{ raw_content }}
- Source: {{ source }}
- Source Type: {{ source_type }}
- Published Date: {{ published_date }}

Task:
Assess if the data is authentic, fresh, and meets quality guidelines.
Output a JSON object complying with `schemas/evidence.json` containing:
- evidence_id
- claim
- evidence_detail
- source
- source_type
- published_date
- observed_date
- confidence
- classification
- reasoning
```
