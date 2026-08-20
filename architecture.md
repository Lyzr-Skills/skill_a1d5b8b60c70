# System Architecture

Describes layout, component relations, and design patterns.

## Engine Layers

- **Ingestion/Collection**: Direct scraper or search handler.
- **Evidence Vault**: Intermediary database saving structured evidence JSON objects. Ensures historical permanence.
- **Inference Engine**: Evaluates current signals vs. previous snapshots to construct new inferences.
- **Scoring Layer**: Evaluates formulas to calculate risk score values.
- **Reporting Engine**: Employs prompts to compile executive documents.
