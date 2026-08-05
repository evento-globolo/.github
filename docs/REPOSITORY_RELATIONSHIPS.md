<!-- ore-org-baseline:begin -->
# Repository relationships for `evento-globolo`

This file is rendered from `repository-relationships.json`. The JSON registry is authoritative.

- Audience: `public`
- Repositories represented: **16**
- Relationships represented: **20**
- Inventory digest: `sha256:d95eebec792414f0d23de257ad1fdb70909113ef15b464fae5ebca0e352a0708`

## Immutable routing identity

| Field | Value |
|---|---|
| Mapping ID | `context:evento-globolo` |
| GitHub owner ID | `313128930` |
| Linear project ID | `ca99596f-9b70-4df9-9d1f-b6e76bd30e82` |
| Linear team ID | `eb8ab169-5afe-4b6f-9cab-3f2aa3e887dc` |

## Repositories

| Repository | Visibility | Roles | Archived |
|---|---|---|---|
| `evento-globolo/.github` | `public` | `community-health`, `governance`, `relationship-registry` | no |
| `evento-globolo/evento-globolo-clients` | `public` | `clients` | no |
| `evento-globolo/evento-globolo-libs` | `public` | `repository` | no |
| `evento-globolo/evento-globolo-monorepo` | `public` | `monorepo` | no |
| `evento-globolo/evento-globolo.github.io` | `public` | `documentation-site` | no |
| `evento-globolo/evgl-api` | `public` | `api-server` | no |
| `evento-globolo/evgl-cli` | `public` | `repository` | no |
| `evento-globolo/evgl-clients` | `public` | `clients` | no |
| `evento-globolo/evgl-dioxus-web` | `public` | `repository` | no |
| `evento-globolo/evgl-infra` | `public` | `infrastructure` | no |
| `evento-globolo/evgl-interfaces` | `public` | `interfaces` | no |
| `evento-globolo/evgl-leptos-web` | `public` | `repository` | no |
| `evento-globolo/evgl-libs` | `public` | `repository` | no |
| `evento-globolo/evgl-mash-web` | `public` | `repository` | no |
| `evento-globolo/evgl-monorepo` | `public` | `monorepo` | no |
| `evento-globolo/evgl-sync` | `public` | `sync` | no |

## Relationships

| From | Type | To | Status | Required |
|---|---|---|---|---|
| `evento-globolo/.github` | `governs` | `evento-globolo/evento-globolo-clients` | `declared` | yes |
| `evento-globolo/.github` | `governs` | `evento-globolo/evento-globolo-libs` | `declared` | yes |
| `evento-globolo/.github` | `governs` | `evento-globolo/evento-globolo-monorepo` | `declared` | yes |
| `evento-globolo/.github` | `governs` | `evento-globolo/evento-globolo.github.io` | `declared` | yes |
| `evento-globolo/.github` | `governs` | `evento-globolo/evgl-api` | `declared` | yes |
| `evento-globolo/.github` | `governs` | `evento-globolo/evgl-cli` | `declared` | yes |
| `evento-globolo/.github` | `governs` | `evento-globolo/evgl-clients` | `declared` | yes |
| `evento-globolo/.github` | `governs` | `evento-globolo/evgl-dioxus-web` | `declared` | yes |
| `evento-globolo/.github` | `governs` | `evento-globolo/evgl-infra` | `declared` | yes |
| `evento-globolo/.github` | `governs` | `evento-globolo/evgl-interfaces` | `declared` | yes |
| `evento-globolo/.github` | `governs` | `evento-globolo/evgl-leptos-web` | `declared` | yes |
| `evento-globolo/.github` | `governs` | `evento-globolo/evgl-libs` | `declared` | yes |
| `evento-globolo/.github` | `governs` | `evento-globolo/evgl-mash-web` | `declared` | yes |
| `evento-globolo/.github` | `governs` | `evento-globolo/evgl-monorepo` | `declared` | yes |
| `evento-globolo/.github` | `governs` | `evento-globolo/evgl-sync` | `declared` | yes |
| `evento-globolo/evento-globolo.github.io` | `documents` | `evento-globolo/.github` | `inferred` | no |
| `evento-globolo/evgl-api` | `depends_on` | `evento-globolo/evgl-interfaces` | `inferred` | no |
| `evento-globolo/evgl-clients` | `depends_on` | `evento-globolo/evgl-interfaces` | `inferred` | no |
| `evento-globolo/evgl-infra` | `deploys` | `evento-globolo/evgl-monorepo` | `inferred` | no |
| `evento-globolo/evgl-sync` | `depends_on` | `evento-globolo/evgl-interfaces` | `inferred` | no |

## Editing relationships

Put reviewed public declarations in `repository-relationships.manual.json`; do not edit the generated registry directly.
Private repository names and private-only relationships belong in the private `approved-private-registry` mirror.
Inferred edges are advisory and must remain visibly labeled until reviewed.
<!-- ore-org-baseline:end -->
