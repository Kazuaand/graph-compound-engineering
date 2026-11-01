# GRAPH and RACI: <project name>

spec: <version>

> Nodes are pieces of work a person recognizes as one outcome — never agents or roles. See HANDBOOK.md §4.4–4.5.

## Nodes
| Node | Outcome | Criteria (AC IDs) | Depends on | Stakes (proto / prod) | Milestone | Status |
|---|---|---|---|---|---|---|
| N1 | Evaluation harness (put the evaluation node first) | | — | proto | M1 | |

## Sub-nodes and waves
| Sub-node | Node | Writes (owned files) | Depends on | Wave |
|---|---|---|---|---|

Wave contract: start from a committed state · each sub-node owns its files · workers commit only to their own branch · merging, publishing and deleting are for the manager and above · the manager verifies.

## Milestones
| Milestone | Nodes | What to revisit |
|---|---|---|

## RACI (exactly one A per row; the human column is never empty)
| Node | Human owner | Task lead | Manager | Worker | <project role> |
|---|---|---|---|---|---|
| N1 | C | A | R | R | |
