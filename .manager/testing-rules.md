# Testing Rules

- Prefer deterministic tests, temporary directories, and generated non-copyrighted fixtures.
- Verify task correctness and migration safety before marking PASS.
- Never claim an automated UI or Windows build test was run if tooling is unavailable.
- Test offline operation, absent music folders, invalid/corrupt metadata, re-indexing, file-lock conflicts, and local privacy as features are added.
- Document actual test commands, exit codes, and failed checks.
- Only report PASS after acceptance criteria and checks have evidence.
