# Temporal Testing Guidelines

Validates timeline construction.

## Scenario
- **Event 1 (June 2026)**: Launches Beta API.
- **Event 2 (July 2026)**: Updates pricing limits.
- **Event 3 (August 2026)**: Deprecates Beta API, launches Version 1.

## Assertions
1. Timeline must order events chronologically.
2. The agent must show trajectory (e.g., transition from beta to launch).
