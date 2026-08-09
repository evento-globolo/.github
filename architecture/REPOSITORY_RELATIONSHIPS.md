# `evento-globolo` repository relationships

Generated from reviewed policy and the current **public** repository inventory.

- Public repositories declared: **17**
- Private repository names withheld: **0**
- Relationship edges: **63**

## Repository roles

| Repository | Role | Lifecycle |
|---|---|---|
| [`.github`](https://github.com/evento-globolo/.github) | `organization_governance` | `active` |
| [`evgl-interfaces`](https://github.com/evento-globolo/evgl-interfaces) | `interfaces` | `active` |
| [`evento-globolo-clients`](https://github.com/evento-globolo/evento-globolo-clients) | `client_sdk` | `active` |
| [`evgl-clients`](https://github.com/evento-globolo/evgl-clients) | `client_sdk` | `active` |
| [`evgl-api`](https://github.com/evento-globolo/evgl-api) | `api_service` | `active` |
| [`evgl-sync`](https://github.com/evento-globolo/evgl-sync) | `sync_service` | `active` |
| [`evgl-mcp-server.rs`](https://github.com/evento-globolo/evgl-mcp-server.rs) | `mcp_server` | `active` |
| [`evgl-cli`](https://github.com/evento-globolo/evgl-cli) | `cli` | `active` |
| [`evento-globolo.github.io`](https://github.com/evento-globolo/evento-globolo.github.io) | `site` | `active` |
| [`evgl-infra`](https://github.com/evento-globolo/evgl-infra) | `infrastructure` | `active` |
| [`evento-globolo-monorepo`](https://github.com/evento-globolo/evento-globolo-monorepo) | `composition_workspace` | `active` |
| [`evgl-monorepo`](https://github.com/evento-globolo/evgl-monorepo) | `composition_workspace` | `active` |
| [`evento-globolo-libs`](https://github.com/evento-globolo/evento-globolo-libs) | `uncategorized` | `active` |
| [`evgl-dioxus-web`](https://github.com/evento-globolo/evgl-dioxus-web) | `uncategorized` | `active` |
| [`evgl-leptos-web`](https://github.com/evento-globolo/evgl-leptos-web) | `uncategorized` | `active` |
| [`evgl-libs`](https://github.com/evento-globolo/evgl-libs) | `uncategorized` | `active` |
| [`evgl-mash-web`](https://github.com/evento-globolo/evgl-mash-web) | `uncategorized` | `active` |

## Declared edges

| From | Relationship | To | Status/basis |
|---|---|---|---|
| `evento-globolo/.github` | `governs` | `evento-globolo/evento-globolo-clients` | `inferred` / `role-convention`: organization defaults, safety, and relationship declarations |
| `evento-globolo/.github` | `governs` | `evento-globolo/evento-globolo-libs` | `inferred` / `role-convention`: organization defaults, safety, and relationship declarations |
| `evento-globolo/.github` | `governs` | `evento-globolo/evento-globolo-monorepo` | `inferred` / `role-convention`: organization defaults, safety, and relationship declarations |
| `evento-globolo/.github` | `governs` | `evento-globolo/evento-globolo.github.io` | `inferred` / `role-convention`: organization defaults, safety, and relationship declarations |
| `evento-globolo/.github` | `governs` | `evento-globolo/evgl-api` | `inferred` / `role-convention`: organization defaults, safety, and relationship declarations |
| `evento-globolo/.github` | `governs` | `evento-globolo/evgl-cli` | `inferred` / `role-convention`: organization defaults, safety, and relationship declarations |
| `evento-globolo/.github` | `governs` | `evento-globolo/evgl-clients` | `inferred` / `role-convention`: organization defaults, safety, and relationship declarations |
| `evento-globolo/.github` | `governs` | `evento-globolo/evgl-dioxus-web` | `inferred` / `role-convention`: organization defaults, safety, and relationship declarations |
| `evento-globolo/.github` | `governs` | `evento-globolo/evgl-infra` | `inferred` / `role-convention`: organization defaults, safety, and relationship declarations |
| `evento-globolo/.github` | `governs` | `evento-globolo/evgl-interfaces` | `inferred` / `role-convention`: organization defaults, safety, and relationship declarations |
| `evento-globolo/.github` | `governs` | `evento-globolo/evgl-leptos-web` | `inferred` / `role-convention`: organization defaults, safety, and relationship declarations |
| `evento-globolo/.github` | `governs` | `evento-globolo/evgl-libs` | `inferred` / `role-convention`: organization defaults, safety, and relationship declarations |
| `evento-globolo/.github` | `governs` | `evento-globolo/evgl-mash-web` | `inferred` / `role-convention`: organization defaults, safety, and relationship declarations |
| `evento-globolo/.github` | `governs` | `evento-globolo/evgl-mcp-server.rs` | `inferred` / `role-convention`: organization defaults, safety, and relationship declarations |
| `evento-globolo/.github` | `governs` | `evento-globolo/evgl-monorepo` | `inferred` / `role-convention`: organization defaults, safety, and relationship declarations |
| `evento-globolo/.github` | `governs` | `evento-globolo/evgl-sync` | `inferred` / `role-convention`: organization defaults, safety, and relationship declarations |
| `evento-globolo/evento-globolo-clients` | `generated_from` | `evento-globolo/evgl-interfaces` | `inferred` / `role-convention`: SDK bindings derive from canonical contracts |
| `evento-globolo/evento-globolo-monorepo` | `composes` | `evento-globolo/evento-globolo-clients` | `inferred` / `role-convention`: development workspace and release bill of materials |
| `evento-globolo/evento-globolo-monorepo` | `composes` | `evento-globolo/evento-globolo-libs` | `inferred` / `role-convention`: development workspace and release bill of materials |
| `evento-globolo/evento-globolo-monorepo` | `composes` | `evento-globolo/evento-globolo.github.io` | `inferred` / `role-convention`: development workspace and release bill of materials |
| `evento-globolo/evento-globolo-monorepo` | `composes` | `evento-globolo/evgl-api` | `inferred` / `role-convention`: development workspace and release bill of materials |
| `evento-globolo/evento-globolo-monorepo` | `composes` | `evento-globolo/evgl-cli` | `inferred` / `role-convention`: development workspace and release bill of materials |
| `evento-globolo/evento-globolo-monorepo` | `composes` | `evento-globolo/evgl-clients` | `inferred` / `role-convention`: development workspace and release bill of materials |
| `evento-globolo/evento-globolo-monorepo` | `composes` | `evento-globolo/evgl-dioxus-web` | `inferred` / `role-convention`: development workspace and release bill of materials |
| `evento-globolo/evento-globolo-monorepo` | `composes` | `evento-globolo/evgl-infra` | `inferred` / `role-convention`: development workspace and release bill of materials |
| `evento-globolo/evento-globolo-monorepo` | `composes` | `evento-globolo/evgl-interfaces` | `inferred` / `role-convention`: development workspace and release bill of materials |
| `evento-globolo/evento-globolo-monorepo` | `composes` | `evento-globolo/evgl-leptos-web` | `inferred` / `role-convention`: development workspace and release bill of materials |
| `evento-globolo/evento-globolo-monorepo` | `composes` | `evento-globolo/evgl-libs` | `inferred` / `role-convention`: development workspace and release bill of materials |
| `evento-globolo/evento-globolo-monorepo` | `composes` | `evento-globolo/evgl-mash-web` | `inferred` / `role-convention`: development workspace and release bill of materials |
| `evento-globolo/evento-globolo-monorepo` | `composes` | `evento-globolo/evgl-mcp-server.rs` | `inferred` / `role-convention`: development workspace and release bill of materials |
| `evento-globolo/evento-globolo-monorepo` | `composes` | `evento-globolo/evgl-monorepo` | `inferred` / `role-convention`: development workspace and release bill of materials |
| `evento-globolo/evento-globolo-monorepo` | `composes` | `evento-globolo/evgl-sync` | `inferred` / `role-convention`: development workspace and release bill of materials |
| `evento-globolo/evgl-api` | `implements_contracts_from` | `evento-globolo/evgl-interfaces` | `inferred` / `role-convention`: service boundary implements canonical contracts |
| `evento-globolo/evgl-cli` | `calls` | `evento-globolo/evgl-api` | `inferred` / `role-convention`: client uses the product service boundary |
| `evento-globolo/evgl-clients` | `generated_from` | `evento-globolo/evgl-interfaces` | `inferred` / `role-convention`: SDK bindings derive from canonical contracts |
| `evento-globolo/evgl-infra` | `deploys` | `evento-globolo/evgl-api` | `inferred` / `role-convention`: product infrastructure declares runtime resources |
| `evento-globolo/evgl-infra` | `deploys` | `evento-globolo/evgl-cli` | `inferred` / `role-convention`: product infrastructure declares runtime resources |
| `evento-globolo/evgl-infra` | `deploys` | `evento-globolo/evgl-mcp-server.rs` | `inferred` / `role-convention`: product infrastructure declares runtime resources |
| `evento-globolo/evgl-infra` | `deploys` | `evento-globolo/evgl-sync` | `inferred` / `role-convention`: product infrastructure declares runtime resources |
| `evento-globolo/evgl-mcp-server.rs` | `uses_sdk` | `evento-globolo/evento-globolo-clients` | `inferred` / `role-convention`: agent adapter reuses the typed product SDK |
| `evento-globolo/evgl-mcp-server.rs` | `calls` | `evento-globolo/evgl-api` | `inferred` / `role-convention`: agent tools use the authenticated product API |
| `evento-globolo/evgl-mcp-server.rs` | `uses_sdk` | `evento-globolo/evgl-clients` | `inferred` / `role-convention`: agent adapter reuses the typed product SDK |
| `evento-globolo/evgl-monorepo` | `composes` | `evento-globolo/evento-globolo-clients` | `inferred` / `role-convention`: development workspace and release bill of materials |
| `evento-globolo/evgl-monorepo` | `composes` | `evento-globolo/evento-globolo-libs` | `inferred` / `role-convention`: development workspace and release bill of materials |
| `evento-globolo/evgl-monorepo` | `composes` | `evento-globolo/evento-globolo-monorepo` | `inferred` / `role-convention`: development workspace and release bill of materials |
| `evento-globolo/evgl-monorepo` | `composes` | `evento-globolo/evento-globolo.github.io` | `inferred` / `role-convention`: development workspace and release bill of materials |
| `evento-globolo/evgl-monorepo` | `composes` | `evento-globolo/evgl-api` | `inferred` / `role-convention`: development workspace and release bill of materials |
| `evento-globolo/evgl-monorepo` | `composes` | `evento-globolo/evgl-cli` | `inferred` / `role-convention`: development workspace and release bill of materials |
| `evento-globolo/evgl-monorepo` | `composes` | `evento-globolo/evgl-clients` | `inferred` / `role-convention`: development workspace and release bill of materials |
| `evento-globolo/evgl-monorepo` | `composes` | `evento-globolo/evgl-dioxus-web` | `inferred` / `role-convention`: development workspace and release bill of materials |
| `evento-globolo/evgl-monorepo` | `composes` | `evento-globolo/evgl-infra` | `inferred` / `role-convention`: development workspace and release bill of materials |
| `evento-globolo/evgl-monorepo` | `composes` | `evento-globolo/evgl-interfaces` | `inferred` / `role-convention`: development workspace and release bill of materials |
| `evento-globolo/evgl-monorepo` | `composes` | `evento-globolo/evgl-leptos-web` | `inferred` / `role-convention`: development workspace and release bill of materials |
| `evento-globolo/evgl-monorepo` | `composes` | `evento-globolo/evgl-libs` | `inferred` / `role-convention`: development workspace and release bill of materials |
| `evento-globolo/evgl-monorepo` | `composes` | `evento-globolo/evgl-mash-web` | `inferred` / `role-convention`: development workspace and release bill of materials |
| `evento-globolo/evgl-monorepo` | `composes` | `evento-globolo/evgl-mcp-server.rs` | `inferred` / `role-convention`: development workspace and release bill of materials |
| `evento-globolo/evgl-monorepo` | `composes` | `evento-globolo/evgl-sync` | `inferred` / `role-convention`: development workspace and release bill of materials |
| `evento-globolo/evgl-sync` | `synchronizes_with` | `evento-globolo/evgl-api` | `inferred` / `role-convention`: sync exchanges state through the product service boundary |
| `evento-globolo/evgl-sync` | `uses_contracts_from` | `evento-globolo/evgl-interfaces` | `inferred` / `role-convention`: sync payloads follow canonical schemas |
| `organization://evento-globolo` | `reconciles_via` | `platform://opto-sync` | `platform-default` / `platform-policy`: product sync wraps the generic reconciliation engine |
| `organization://evento-globolo` | `deployed_via` | `platform://ORESoftware/k8s-cluster` | `platform-default` / `platform-policy`: immutable artifacts are promoted by digest through GitOps |
| `organization://evento-globolo` | `uses_transport_library` | `platform://ORESoftware/mcp-rust-libs` | `platform-default` / `platform-policy`: shared MCP transport and protocol hardening |
| `organization://evento-globolo` | `packaged_via` | `platform://zed-pkg` | `platform-default` / `platform-policy`: Zed resolves artifacts while submodules compose editable source |

## Composition, service, and observability contract

Git submodules compose editable source; Zed packages resolve packages/artifacts; dual-managed commits must match. Production deploys immutable image digests, not runtime source builds. Cross-service access uses APIs/SDKs/events rather than another service database. MCP uses the product API/SDK. Services emit OpenTelemetry traces, bounded metrics, and correlated structured logs.

## Privacy boundary

This public registry deliberately omits private repository names and edges; the count above makes the boundary explicit.
