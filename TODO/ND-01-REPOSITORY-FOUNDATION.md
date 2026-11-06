# ND-01 — REPOSITORY-FOUNDATION

Goal: establish a public GPLv3, Codex-ready repository without starting application development.
Entry Gate: public GitHub repository exists with the GNU GPLv3 license file.
Exit Gate: documentation, task contracts, safe ignores, and CI bootstrap are committed and reviewed.

[ ] **ND01-T01 — Verify GPLv3 and scope** (SP: 1)
- Verify the root LICENSE is GNU GPL version 3; do not modify its authoritative wording.
- Confirm README links to LICENSE, scope, and philosophy.
- Acceptance: coherent GPLv3 notices and no pay-to-win, music, cloud, or leaderboard promises.
- Verification: inspect LICENSE header and README references.
---

[ ] **ND01-T02 — Validate repository safety and collaboration docs** (SP: 1)
- Review .gitignore, CONTRIBUTING.md, AGENTS.md, and .manager docs.
- Acceptance: audio/user-data/secrets excluded; scope guards and collaboration instructions clear.
- Verification: list matching ignore patterns and docs.
---

[ ] **ND01-T03 — Validate product architecture and roadmap** (SP: 2)
- Review docs/PRODUCT-VISION.md, docs/PHILOSOPHY.md, docs/ARCHITECTURE.md, and docs/ROADMAP.md.
- Acceptance: offline first; manually assigned multi-tags; separate GLOBAL/CURRENT/PERSONAL progression; no server in MVP.
- Verification: inspect document consistency and task sequencing.
---

[ ] **ND01-T04 — Implement baseline CI workflow** (SP: 2)
- Add GitHub Actions workflow for safe documentation and source hygiene checks.
- Acceptance: validates required repo docs, enforces TODO delimiters/SP <= 3, prevents committed music files, and can run before .NET solution exists.
- Verification: run CI or a locally equivalent reproducible check.
---

[ ] **ND01-T05 — Foundation closure and next-phase handoff** (SP: 2)
- Verify project layout, all preceding tasks PASS, and the future app bootstrap phase is described.
- Acceptance: ND-02 scope and dependencies documented; clean git working tree after commit; evidence and limitations explicitly recorded.
- Verification: repository and task audit.
---
