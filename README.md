# Fixibl 🦫

**Anything is Fixibl.** Fixibl is a repair service site: send a fix
request (sign in first), a fixer claims it and sends you a bid, you chat
until it's ready, then pick it up. Fixers work from a hidden portal at
`/fixer`.

Live at **https://www.fixifyit.org** (GitHub Pages — every push to `main`
deploys automatically, usually within a minute).

## What's in this repo

| File | What it is |
|---|---|
| `index.html` | The whole app — landing page, fix-request form, My items + chat, and the fixer portal/board. Uses Firebase Auth + Firestore. |
| `fixer/index.html` | Redirects www.fixifyit.org/fixer to the hidden fixer sign-in. |
| `firestore.rules` | Security rules for the Firestore database. **Not active until published — see below.** |
| `logo.png` / `favicon.png` / `apple-touch-icon.png` | The beaver. |
| `CNAME` | Tells GitHub Pages to serve the site at www.fixifyit.org. |
