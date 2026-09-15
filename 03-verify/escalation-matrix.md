# Escalation matrix

| Risk | Example | Default behavior | Human approval |
|---|---|---|---|
| Low | Internal, reversible draft | Continue and log | Not required |
| Medium | Shared-state change | Prepare, verify, then execute | Required by workflow owner |
| High | Public, financial, sensitive, or irreversible action | Stop before execution | Explicit approval required |

## Automatic escalation triggers

- The same failure occurs twice.
- The source of truth is missing or contradictory.
- The output fails its evaluation.
- Required access expands beyond the approved scope.
- The destination receipt cannot be produced.

Name the person who owns each escalation before the workflow runs.

