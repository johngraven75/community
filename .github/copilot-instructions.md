# Repository Engineering Standard

Mandatory for AI-assisted engineering. Define goal, user, success criteria, non-goals, assumptions and missing requirements before code; propose architecture before implementation. Use **Frontend**, **Connector / integration**, and **Backend** structure where applicable and independently testable vertical slices/worktrees with exact files, interfaces, error handling, observability, security implications and definition of done.

Use fresh idiomatic production code following SOLID/DRY, explicit types, secure defaults, validation, null safety, deterministic cleanup and separation of concerns. No TODOs, placeholders, fabricated integrations, credentials or incomplete production paths. Preserve compatibility unless an explicit migration is approved.

Include appropriate unit, integration, contract, security, performance and manual QA validation. Self-review races, leaks, resource disposal, permissions, lifecycle, interrupted operations and rollback. Production readiness requires diff summary, changelog/migration notes, API/config docs, rollback/monitoring plans, test evidence and checksums where applicable. Keep commits atomic/conventional, commit before builds, never bypass required checks, and never claim unverified completion.
