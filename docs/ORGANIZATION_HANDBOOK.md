# evento-globolo organization handbook

> Shared operating defaults for repositories maintained under **evento-globolo**. Repository-local policy may strengthen these rules but should not silently weaken them.

## Mission

evento-globolo maintains event discovery, publishing, scheduling, registration, coordination, and community software. This `.github` repository is the canonical home for shared policy, reusable templates, community health files, and planning links.

## Repository contract

Each active repository must document purpose, ownership, maturity, supported platforms and locales, development and test commands, authoritative event and registration formats, release and rollback procedures, compatibility policy, and GitHub Project/Linear links. Event components should also document timezone and recurrence semantics, venue and organizer provenance, moderation, privacy and consent, capacity and waitlists, cancellation and refunds, notifications, accessibility, localization, retention, and degraded modes.

## Change workflow

1. Anchor work in an issue, Linear item, or documented maintenance objective.
2. Keep branches and pull requests focused.
3. Explain motivation, scope, attendee and organizer impact, validation, compatibility, migration, and rollback.
4. Test timezone, daylight-saving, recurrence, duplicate, cancellation, capacity, waitlist, permission, notification failure, localization, and accessibility paths as relevant.
5. Resolve conflicts semantically by reconstructing both sides' intent.
6. Prefer squash merges for focused work unless commit structure materially improves auditability.

## Evidence, security, and documentation

Pull requests should include reproducible commands, synthetic fixtures, expected and observed schedules and state transitions, negative-path coverage, documentation updates, and CI or local-equivalent results. Never commit credentials, attendee records, private contact details, payment data, or sensitive logs. Follow `SECURITY.md` for private reporting. Keep timezone, provenance, moderation, privacy, accessibility, compatibility, and important operational decisions explicit.

## Planning ownership

GitHub owns code, reviews, checks, releases, and delivery evidence. Linear owns priority, dependencies, sequencing, and cross-project planning. The organization GitHub Project is the cross-repository execution view; see `PROJECTS.md` for routing details.

## Organization health

- [ ] Profiles, descriptions, topics, and READMEs are current.
- [ ] Community health files and reusable issue/PR guidance are present.
- [ ] Timezone, recurrence, provenance, moderation, capacity, cancellation, privacy, and accessibility are documented.
- [ ] Required checks cover scheduling boundaries, notification failure, localization, compatibility, and supply-chain risk.
- [ ] Stale repositories are archived or clearly marked.
- [ ] GitHub Project and Linear links resolve and reflect completed work.
