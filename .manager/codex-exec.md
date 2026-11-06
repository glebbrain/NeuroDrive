# Codex Task Execution Protocol

1. Read `AGENTS.md`, the explicitly selected TODO file, and directly relevant docs.
2. Identify the **first** unchecked `[ ]` task. Do not work on other tasks.
3. Validate Entry Gate prerequisites and record uncertainty before changing files.
4. Implement only the scoped change. Prefer simplest maintainable solution.
5. Run the specified test and any relevant static checks; record actual outputs.
6. Check acceptance criteria individually.
7. If all pass, change only that task's `[ ]` to `[x]` and append concise evidence under the task; preserve its closing delimiter.
8. If blocked or unverified, leave `[ ]`, report BLOCKED and stop.
9. Final report: task ID, status, files changed, tests/results, risks and next unchecked task.

No hidden expansion of scope, unapproved network dependencies, artificial PASS, or destructive cleanup.
