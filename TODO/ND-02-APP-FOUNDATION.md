# ND-02 — APP-FOUNDATION

Status: planned. Start only after ND-01 exit gate passes.
Goal: a buildable, tested local-first Windows desktop application skeleton.
No features from later phases may be implemented in ND-02.

[ ] **ND02-T01 — Supported runtime and dependency gate** (SP: 2)
- Research and document target Windows support matrix, supported .NET version, WPF toolchain, and support policy.
- Review GPLv3 compatibility criteria for planned libraries without introducing them yet.
- Acceptance: explicit and justified version decisions with evidence.
---

[ ] **ND02-T02 — Solution skeleton** (SP: 2)
- Bootstrap WPF app, domain/application abstractions, and tests as separate projects.
- Acceptance: solution builds on supported Windows development environment.
---

[ ] **ND02-T03 — DI and configuration** (SP: 2)
- Introduce startup DI, typed local configuration, and clear runtime error handling.
- Acceptance: smoke checks and unit tests pass.
---

[ ] **ND02-T04 — Local SQLite bootstrap** (SP: 3)
- Introduce local database lifecycle, migrations, and failure-safe handling.
- Acceptance: temporary database integration tests pass.
---

[ ] **ND02-T05 — App foundation validation** (SP: 2)
- Verify startup, clean shutdown, offline mode, tests, and documentation.
- Acceptance: all exit criteria and build/test evidence recorded.
---
