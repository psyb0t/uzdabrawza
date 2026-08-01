# Changelog

All notable changes per release. Versions follow [semver](https://semver.org).

## 1.0.5 — 2026-08-01

CI/infrastructure only. No code in this repo changed — the whole diff since 1.0.4 is
under `.github/workflows/`.

- Split the pipeline: building and publishing stay in `pipeline.yml`, and everything
  that leaves the host now lives in its own file beside it.
- The repo is mirrored to Codeberg as well as GitLab.
- The repo is archived to the Wayback Machine, Software Heritage and archive.org.
- Issues opened on either mirror are copied back to GitHub every six hours, and closed
  here when the original closes.
- Pull requests are switched off on both mirrors — they are force-pushed from GitHub,
  so anything merged there would be destroyed by the next sync. Issues and forking stay
  enabled.

## 1.0.4 — 2026-07-31

Dependency security floors. No behaviour change.

- **Raised `Pillow` to `>=12.3.0`** and added floors for four packages that
  arrive transitively through `browser-use`: `aiohttp>=3.14.1`,
  `click>=8.3.3`, `mcp>=1.28.1`, `pypdf>=6.14.2`. `pip-audit --strict` was
  reporting 45 known advisories across them and failing the pipeline.
- Naming transitive packages in `dependencies` is the only way to raise their
  floor — the resolver has no reason to pick a newer version otherwise, and a
  vulnerability that arrives through a dependency counts the same as one
  depended on directly. Each entry should be dropped once `browser-use`'s own
  floor passes it, so the list doesn't rot into a set of stale pins.

## 1.0.3 — 2026-04-15

- Restricted CI to collaborators only.

## 1.0.2

- Maintenance release.

## 1.0.1

- Maintenance release.

## 1.0.0

- Initial release.
