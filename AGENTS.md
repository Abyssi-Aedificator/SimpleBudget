## Repo overview

- Single-file PWA — all CSS, HTML, JS inline in `index.html` (~7800 lines). No framework, no build step, no `package.json`.
- Service worker in `sw.js` for offline caching (cache name `simplebudget-v2`).
- Manifest at `manifest.webmanifest`.
- State persisted to `localStorage` under key `simplebudget.v1`.
- Version displayed in sidebar as plain HTML (`Version X.X.X`). No JS version constant exists.
- Changelog lives in `changelog.txt` (external, not in the app).
- Dev banner toggled via `.dev-banner` CSS `display: flex/none`.

## Running the app

Open `index.html` directly in a browser via `file://` protocol. CORS warnings for `manifest.webmanifest` are expected and harmless.

## Commit rules

- Each bug fix or feature change must be committed individually (one commit per fix).
- Group only truly atomic, related changes (e.g. changelog + version bump for the same release) into the same commit when explicitly instructed.

## No tooling

There is no test runner, linter, typechecker, or formatter. No verification commands exist.
