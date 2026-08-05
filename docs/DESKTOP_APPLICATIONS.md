# Desktop application allocation

Verified **2026-08-05**.

Evento Globolo **might** benefit from paired native desktop applications for organizer-heavy workflows after the core web/mobile event experience is established:

- Rust: [`evento-globolo/evento-desktop.rs`](https://github.com/evento-globolo/evento-desktop.rs) — **proposed**, not yet verified as a published repository.
- Flutter: [`evento-globolo/evento-flutter`](https://github.com/evento-globolo/evento-flutter) — **proposed**, not yet verified as a published repository.

These names are optional allocation targets, not proof that either remote exists and not a commitment to build them. Native clients should be promoted only when bulk event imports, keyboard-heavy administration, cross-posting, ticketing operations, attendee exports, local printing, or check-in hardware materially outperform the web/mobile workflow.

## Potential product boundary

A future pair could cover semantic parity for event and venue management, bulk imports and edits, calendar operations, cross-posting, ticket inventory, attendee lists, exports, badge and receipt printing, scanner/check-in hardware, offline check-in, notifications, synchronization, and recovery.

A shared Rust local-sync, import, or hardware-integration core may sit behind an explicit library, FFI, or local-service boundary, but any Flutter application must remain independently buildable, testable, and releasable. Shared schemas, clients, fixtures, sample events, ticket/check-in contracts, and conformance tests should be versioned deliberately.

## Promotion rule

Promote this pair from optional proposal to planned only when the organizer workflow, hardware boundary, ownership, milestones, and repository creation are accepted. Once planned, desktop-facing changes must inspect both implementations, define shared acceptance criteria, update both or record an explicit no-change rationale, and report Rust and Flutter status separately.

## Project routing

- GitHub Project: [`evento-globolo-project` — Project 1](https://github.com/orgs/evento-globolo/projects/1)
- Linear project: `github.com/evento-globolo`
- Central registry: [`ORESoftware/project-registry`](https://github.com/ORESoftware/project-registry/blob/main/registry/desktop-applications.json)
- Portfolio rollout: [`DEN-2469`](https://linear.app/denman/issue/DEN-2469/roll-out-paired-rust-flutter-desktop-repositories-across-the-portfolio)

Promotion, repository creation, renames, transfers, archival, hardware-boundary changes, or platform-status changes must update this document, Linear, the central registry, and both companion repositories together.
