# Architecture — Initial Constraints

**Status:** draft; technical decisions require verification in ND-02.

## Components
- Desktop UI: Windows WPF with MVVM and DI.
- Domain/Application: music tags and playback selection; tasks/sprints; achievements/XP; progression; analytics; recovery.
- Local infrastructure: file-system music index, local SQLite state/event journal, optional XLSX/Markdown task adapters.
- Audio backend: investigate LibVLCSharp or a license-compatible alternative. Playback backend must be replaceable.
- Testing: unit tests for domain and adapters; integration tests for persistence and import/export; targeted manual UI smoke tests.

## Contracts
- User owns music files; never copy or upload them automatically.
- Track may have multiple purpose tags. Track identity should survive safe folder rescans where feasible.
- Persist metadata and explicit user choices, not copyrighted audio payloads.
- Local data is authoritative for MVP; no online identity or server.
- XP and gold are gamification; skill measurements and real-world task verification are separate.
- No implicit analytics upload.
- Recovery suggestions cannot forcibly block tasks.

## Release gates
- Explicitly verify supported Windows OS versions, .NET runtime support lifecycle, licenses of audio dependencies, packaging and update strategy.
- Tests must run on the chosen supported environment; no claim of a working Windows build from a docs-only PR.
