# Simple Budget

Offline-first personal budgeting app. All data stays on your device — no server, no account, no cloud.

## Features

- **Income & expense tracking** with multiple accounts, categories, and search/filter
- **Recurring transactions** with auto-post (daily, weekly, monthly, yearly)
- **CSV import** with auto-categorization rules
- **Category budgets** (monthly planification with progress tracking)
- **Upcoming forecast** — projected cash flow from scheduled transactions
- **Investment portfolio** with price snapshots and live price refresh (Alpha Vantage)
- **Debt payoff tracker** with progress bars and payoff estimates
- **Statistics** — spending patterns, category breakdowns, monthly summaries
- **Net worth chart** over custom periods
- **Multiple account types** (Checking, Credit, Line of Credit, REER, Investment)
- **Dark & light themes** with custom accent colors and tone presets
- **PWA** — installable, works fully offline
- **Backup & restore** (JSON export/import)

## Usage

Open `index.html` in any modern browser. No build step, no dependencies.

## How it works

Everything runs in your browser using `localStorage`. The service worker (`sw.js`) caches all assets so the app works offline after the first visit.

## License

MIT
