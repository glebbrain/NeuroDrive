# Codex Instructions — NeuroDrive

Read this file before changing the repository, then read `.manager/codex-exec.md`, the applicable task file, and relevant design documents.

## Execution contract
- Execute **only the first unchecked task** in the explicitly requested TODO phase.
- Each task has StoryPoints <= 3. Do not expand scope or silently implement later phases.
- Keep TODO task boundaries intact: an unchecked task starts with `[ ]` and ends with a line containing exactly `---`. Do not use `---` elsewhere in TODO files.
- Follow task acceptance criteria and report evidence (commands, results, files changed).
- Mark complete only when acceptance criteria and relevant tests pass. If blocked, leave unchecked, provide the specific blocker, and stop.
- Prefer small, reversible, testable changes. Do not modify GitHub configuration, publish releases, or merge PRs without an explicitly scoped task.

## Product invariants
- GPL-3.0-only source; validate third-party dependency licenses.
- Local-first and offline-first. No online backend, ratings, Google Sheets, account creation, or leaderboard in current scope.
- No bundled music and no automatic AI-based audio classification in MVP.
- A track may have many manually assigned user-defined purpose tags.
- Gameplay XP, achievement, and ability metrics are distinct. No pay-to-win.
- Personal analytics are private by default. No telemetry without explicit consent.
- No unauthorized copying of copyrighted audio, game effects, or visuals.

See `docs/ARCHITECTURE.md` and `docs/ROADMAP.md` for boundaries.
