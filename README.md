# ThinkFlowLabs · SEO Audits

Private client audit deliverables hosted on GitHub Pages.

Each subfolder of this repo is one engagement. Pages are blocked from search engines via `<meta name="robots" content="noindex">` + a top-level `robots.txt`.

## Audits — Ludlow Property Group self-storage portfolio (13 facilities)

| Client | Folder | URL |
|---|---|---|
| Delta Self Storage | [`/delta-self-storage-audit/`](./delta-self-storage-audit/) | https://lpgmarketing.github.io/SEO/delta-self-storage-audit/ |
| Elk Mountain Storage | [`/elk-mountain-storage-audit/`](./elk-mountain-storage-audit/) | https://lpgmarketing.github.io/SEO/elk-mountain-storage-audit/ |
| Slate River Storage | [`/slate-river-storage-audit/`](./slate-river-storage-audit/) | https://lpgmarketing.github.io/SEO/slate-river-storage-audit/ |
| Parachute Storage | [`/parachute-storage-audit/`](./parachute-storage-audit/) | https://lpgmarketing.github.io/SEO/parachute-storage-audit/ |
| Snowmass Self Storage | [`/snowmass-self-storage-audit/`](./snowmass-self-storage-audit/) | https://lpgmarketing.github.io/SEO/snowmass-self-storage-audit/ |
| Montrose Self Storage | [`/montrose-self-storage-audit/`](./montrose-self-storage-audit/) | https://lpgmarketing.github.io/SEO/montrose-self-storage-audit/ |
| Vail Airport Storage | [`/vail-airport-storage-audit/`](./vail-airport-storage-audit/) | https://lpgmarketing.github.io/SEO/vail-airport-storage-audit/ |
| Eagle Canopy RV Storage | [`/eagle-canopy-audit/`](./eagle-canopy-audit/) | https://lpgmarketing.github.io/SEO/eagle-canopy-audit/ |
| Estes Park Storage | [`/estes-park-storage-audit/`](./estes-park-storage-audit/) | https://lpgmarketing.github.io/SEO/estes-park-storage-audit/ |
| Moab Self Storage | [`/storage-moab-audit/`](./storage-moab-audit/) | https://lpgmarketing.github.io/SEO/storage-moab-audit/ |
| Friday Harbor Storage | [`/friday-harbor-storage-audit/`](./friday-harbor-storage-audit/) | https://lpgmarketing.github.io/SEO/friday-harbor-storage-audit/ |
| Moriches Storage | [`/storage-moriches-audit/`](./storage-moriches-audit/) | https://lpgmarketing.github.io/SEO/storage-moriches-audit/ |
| Discount Self Storage | [`/discount-self-storage-audit/`](./discount-self-storage-audit/) | https://lpgmarketing.github.io/SEO/discount-self-storage-audit/ |

## How to add a new audit

1. Create a new subfolder (e.g. `client-name-audit/`).
2. Drop the `index.html` deliverable inside.
3. Add a `.nojekyll` file in the subfolder (optional, repo root already has one).
4. Add a `<meta name="robots" content="noindex">` tag to the HTML head.
5. Commit + push to `main` — GitHub Pages rebuilds automatically.
6. Update the table above with the new audit URL.
