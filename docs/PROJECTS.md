<!-- org-project-routing:start -->
# Project routing

- **GitHub organization:** [evento-globolo](https://github.com/evento-globolo)
- **Canonical GitHub Project:** [evento-globolo-project](https://github.com/orgs/evento-globolo/projects/1) (project 1)
- **Canonical Linear project:** [planning workspace](https://linear.app/denman/project/githubcomevento-globolo-4daaf1952e29)
- **Organization documentation repository:** [evento-globolo/.github](https://github.com/evento-globolo/.github)

## Source-of-truth boundaries

GitHub is authoritative for repositories, commits, pull requests, reviews, CI checks, releases, deployable artifacts, and runtime evidence. Linear is authoritative for product planning, priorities, ownership, dependencies, milestones, and status reporting. The GitHub Project is the organization-level execution board and should contain the governance issue maintained by this repository.

## Change and merge policy

Documentation branches must be reviewed through pull requests and merged after checks pass. Concurrent edits are reconciled semantically against the latest default branch: this managed routing block is regenerated while all unrelated prose outside the block is preserved. Do not resolve conflicts by blindly choosing one side.
<!-- org-project-routing:end -->

## Active delivery ledger

### `evgl-mcp-server.rs`

- **GitHub tracking issue:** [evento-globolo/.github#4](https://github.com/evento-globolo/.github/issues/4)
- **Executable repository seed:** [`repository-seeds/evgl-mcp-server.rs/`](../repository-seeds/evgl-mcp-server.rs/)
- **Canonical repository target:** `evento-globolo/evgl-mcp-server.rs`
- **Dependency contract:** clients + interfaces + libs + CLI + sync + `shared-auth/shared-auth-clients`
- **Materialization:** `.vendor/.zed`
- **Publication:** run the seed's `publish.sh` only from an authenticated GitHub CLI environment; it refuses to overwrite an existing repository and does not embed credentials.
- **Composition:** committed canonical gitlinks are allowed as source transport and must be adopted with `zed overtake --git-submodules`; duplicate package identities and long-name aliases are prohibited.

GitHub Project #1 tracks execution. The Linear project tracks priority, ownership, dependencies, milestones, and delivery status. Repository, pull-request, CI, release, and runtime evidence remains in GitHub.


## Delivery record — `evgl-mcp-server.rs` (2026-08-07)

- **Canonical repository published:** https://github.com/evento-globolo/evgl-mcp-server.rs
- **Initial commit (seed bootstrap via `publish.sh`):** `81159c12eade2e8db7cad9c00b12945d913f41d3`
- **CI-green commit:** `6e69697b525ce696f98a8e74b35c888487240796` — formatting, Clippy, tests, and Zed manifest checks all passing
- **Delivery issue:** [evento-globolo/.github#4](https://github.com/evento-globolo/.github/issues/4), added to organization GitHub Project #1
- **Outstanding:** `.zpkg.lock` generation awaits a real successful Zed resolver run (DEN-2290)
