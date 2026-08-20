# Pipeline Workflow Execution

Defines the sequence of operations run by the agent.

## Execution Sequence

1. **Initialize**: Ingest configuration targets.
2. **Scope**: Define landscape targets.
3. **Discover**: Classify direct/indirect/potential competitors.
4. **Collect**: Scraping official documentation, pricing, and PR lines.
5. **Validate**: Run validation criteria (Authenticity, dates, details).
6. **Classify**: Assign classification level.
7. **Extract Signals**: Extract pricing and product shifts.
8. **Correlate**: Correlate signals across files.
9. **Infer**: Formulate inference objects. Run disconfirming evidence searches.
10. **Prioritize**: Compute risk/potential metrics.
11. **Draft**: Create the executive brief report.
