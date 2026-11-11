# Notice from Axia Growth / OperationKit maintainers (2026-11-11)

This fork (`o-soft/operationkit`) was created from `Axia-Growth/OperationKit` before a
history re-root we ran upstream on 2026-11-11, so it still carries the old commit history.
See the accompanying pull request for details and a request to delete-and-re-fork.

Separately: we'd originally flagged that this fork's `docs/api/README.md` and
`docs/api/AGENT-PROMPT.md` still named one of our actual clients ("Shabo DL"). As of this
check, that's already gone from `main` — an earlier upstream sync (`c5f31e0`, 2026-09-02)
already replaced it with the anonymized "Example5 DL", and a case-insensitive search for
"shabo" over the current tree returns nothing. No further edit is needed for that part;
this file exists only to open this PR and record that check.
