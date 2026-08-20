# State Management

This document defines how the Market Intelligence Agent manages competitive state snapshots over time.

## Snapshots and Events

1. **Competitor State Snapshot**:
   - Stores the current known profile of a competitor (Positioning, Pricing, Capabilities).
   - Saved as a JSON object adhering to `schemas/competitor.json`.

2. **Intelligence Events**:
   - Represents changes (`schemas/intelligence-event.json`).
   - Stores `previous_state`, `current_state`, and the delta.

## Delta Detection & Merging

When new evidence is processed:
- Compare the new evidence attributes against the current state snapshot.
- If a change is validated, create a new `IntelligenceEvent`.
- Apply the event to update the state snapshot.
- Archival: Retain past snapshots to trace trajectory.
