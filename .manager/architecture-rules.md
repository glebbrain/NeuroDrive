# Architecture Rules

- Domain logic remains independent of WPF and hardware-specific playback components.
- Define narrow adapter interfaces for media scanning, audio output, persistence, and task imports.
- Keep local data and media on-device; no network service is required by application startup.
- Every track supports multiple manual purpose tags; allow user-defined labels.
- Keep XP/gold separate from real-world goals and assessed personal capabilities.
- Choose supported Windows and .NET versions through explicit compatibility checks.
- New packages require a GPLv3 compatibility review.
- No external online integrations or user accounts in the current scope.
