# Digital Safety — Safer Browsing Experience

A standalone React + TypeScript + Vite + Tailwind CSS educational cybersecurity-awareness demo. This version is separated from Replit workspace configuration so it can be edited and hosted independently.

## Run locally

Requirements: Node.js 20 or newer and npm.

```bash
npm install
npm run dev
```

Open the local URL printed by Vite (normally `http://localhost:5173`).

## Build for hosting

```bash
npm run typecheck
npm run build
npm run preview
```

The production build is written to `dist/`. Upload the contents of that directory to a static host. Configure SPA fallback/rewrite rules so routes such as `/learn`, `/threat-library`, `/safety-check`, `/device-protection`, and `/privacy` serve `index.html`.

## What's included

- Responsive educational website with dark and light themes.
- Searchable library of 28 defensive lessons and topic imagery.
- Fictional phishing-awareness simulator.
- Self-reported safety check and browser checklist.
- Device-protection request wizard that explicitly remains a demo.
- Local-only demo registration (no account is created and no data is transmitted).
- DEVZIKKY owner section, portfolio links, related project links, and an in-session timer.
- Original-style SVG favicon and local image assets.

## Privacy and scope

This is not antivirus software. It does not scan, monitor, connect to, or modify devices. Demo registration asks only for a display name and does not send or save it. The optional device note is not sent to a server. Learning preferences may be stored locally in the browser.

## Project ownership links

- Portfolio: https://zikkytech.vercel.app
- ZikkyTech: https://zikkytech.xo.je
- CypherGuard: https://replit.com/@zikkystar0001/CypherGuard
- CypherX: https://replit.com/@zikkystar0001/CypherX-3
- TikTok Downloader: https://replit.com/@zikkystar0001/TikTok-Downloader
- Dev Journey: https://replit.com/@zikkystar0001/Dev-Journey

## Notes

The 10M counter is an illustrative milestone, not a verified user count. External references are educational resources. Review external project links and hosting-specific routing before publishing.
