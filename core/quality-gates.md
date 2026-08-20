# Quality Gates

Quality gates ensure that the intelligence pipeline halts or fails if raw data fails validation tests.

| Gate ID | Stage | Criteria | Action on Failure |
|---|---|---|---|
| **QG-1** | Collection | Valid URL and source hierarchy assigned | Exclude record |
| **QG-2** | Validation | Source authenticity checked | Mark as unverified |
| **QG-3** | Classification | Evidence matches Fact vs Signal classification definition | Fail classification step |
| **QG-4** | Correlation | Signal references valid evidence IDs | Exclude signal |
| **QG-5** | Inference | Disconfirming evidence checked explicitly | Downgrade confidence |
| **QG-6** | Report | No inferences reported as facts | Reject report compilation |
