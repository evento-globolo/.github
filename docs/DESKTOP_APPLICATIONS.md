# Evento Globolo desktop applications

Verified **2026-08-06**.

## Required pair

- Rust: [`evento-globolo/evgl-desktop.rs`](https://github.com/evento-globolo/evgl-desktop.rs) — **planned**, not yet verified as published.
- Flutter: [`evento-globolo/evgl-flutter`](https://github.com/evento-globolo/evgl-flutter) — **planned**, not yet verified as published.

These names supersede the earlier `evento-desktop.rs` and `evento-flutter` proposals. Do not mark either implementation live until the remote, native build, packaging, tests, and platform matrix are verified.

## Rust desktop kit: Tauri 2 without React

The Rust application uses **Tauri 2**.

- React, JSX, React-derived stacks, Vue, and Svelte are prohibited.
- Use vanilla HTML, CSS, and TypeScript.
- HTMX is allowed for authenticated server-driven fragments where it reduces client code.
- Rust/Tauri commands own local persistence, secure storage, import/export, printing, check-in peripherals, notifications, deep-link validation, and privileged operations.
- Do not introduce an unauthenticated loopback HTTP service.

This strategy fits event and venue forms, bulk organizer operations, calendars, ticketing, attendee lists, badge/receipt printing, check-in dashboards, and offline synchronization.

The future Rust repository must contain `docs/DESKTOP_TOOLKIT.md` documenting the Tauri major-version policy, capability/CSP rules, no-React policy, privilege boundary, deep links, packaging, platform tests, and Flutter companion.

## Parallel Rust and Flutter development

The Rust and Flutter applications are first-class side-by-side implementations. They are developed against the same features to compare local integration, performance, accessibility, Flutter mobile reuse, developer velocity, release reliability, and long-term maintenance.

Every desktop-facing feature must inspect both repositories, share acceptance criteria and fixtures, and normally update both. A one-sided change requires an explicit no-change rationale and parity gap. The future `evgl-desktop.rs` README, `AGENTS.md`, pull-request template, and `docs/DESKTOP_TOOLKIT.md` must state this rule prominently.

## HTTPS-first deep links

Canonical route family:

```text
https://<verified-evgl-owned-host>/open/<route>?<bounded-query>
```

Fallback scheme:

```text
evgl://<route>?<bounded-query>
```

Rust and Flutter must consume the same versioned route types and fixtures.

Initial route families may include events, venues, organizer workspaces, tickets, attendees, check-in sessions, calendars, imports, exports, and authenticated notifications.

Required behavior:

- cold-start and already-running/single-instance delivery;
- exact host, route/version, event/venue/ticket/attendee identifiers, action, and bounded-query validation;
- authenticated resume and browser fallback;
- replay, expiry, role, tenant, and unsafe-return validation;
- explicit confirmation before imports, ticket state changes, refunds, attendee edits, printing, or destructive actions; and
- macOS, Windows, Linux, Android, and iOS tests.

Passwords, bearer tokens, payment credentials, attendee private data, ticket secrets, or scanner credentials are prohibited in URLs. Invitations, payment continuation, and ticket/check-in handoffs must use short-lived, single-use, audience-bound codes.

## Product boundary

Both implementations should converge on:

- event and venue management;
- bulk imports, edits, and cross-posting;
- calendars and schedules;
- ticket inventory, attendees, check-in, badges, receipts, and local peripherals;
- offline operation, notifications, synchronization, and recovery;
- schemas, generated clients, route fixtures, privacy-safe sample events, and conformance tests.

## Project routing

- GitHub Project: [`evento-globolo-project` — Project 1](https://github.com/orgs/evento-globolo/projects/1)
- Linear project: `github.com/evento-globolo`
- Central registry: [`desktop-applications.json`](https://github.com/ORESoftware/project-registry/blob/main/registry/desktop-applications.json)
- Toolkit strategy: [`rust-desktop-strategies.md`](https://github.com/ORESoftware/project-registry/blob/main/docs/rust-desktop-strategies.md)
- Portfolio rollout: [`DEN-2469`](https://linear.app/denman/issue/DEN-2469/roll-out-paired-rust-flutter-desktop-repositories-across-the-portfolio)

Repository creation, toolkit/frontend changes, deep-link changes, renames, transfers, archival, or platform-status changes must update this document, Linear, the central registry/strategy, and both companion repositories together.
