# Brief: <one-line title>

<!-- One brief = one task. Hand this file's location to the agent; do not paste a summary of the spec. See HANDBOOK.md §7.1. -->

- **Purpose**: <why this task exists, 1–2 sentences>
- **Open questions**: <Q1 …, Q2 … — the unresolved points this task touches>
- **Task (one)**: <what to do>
- **Inputs**: <locations of the spec and source files — paths, not summaries>
- **Definition of done**: <a check whose result shows in the transcript, e.g. "`npm test` exits 0", plus one outside check by someone other than the maker>
- **Budget**: <tokens / time>
- **Stop point**: <where to stop and report, e.g. "When the checks pass, report and stop. Do not start additional reviews unless asked.">
- **Output**: <the only location(s) you may write to>
- **Prohibitions**: <what not to touch or do>

## Standing rules (paste into every brief)

- When unsure: if the answer changes the shape, boundary or whether to stop, return a blocked-record; otherwise register it as Undetermined and proceed.
- Stop and return a blocked-record on any return condition: 3 consecutive check failures on the same target / a decision outside the spec / no progress on an unknown problem for ~30 min / work beyond your scope / evidence that a settled decision no longer holds.
- If you find evidence that a settled decision no longer holds, do not stay silent — report it.

## Reply format

One-line conclusion → evidence (file and line, or check output) → risks and trade-offs → next step → unverified.
End with: `Open: Q1=closed(<where>) Q2=open(<why>)` and `spec: <version>`.

spec: <version or hash prefix>
