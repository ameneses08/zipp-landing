# Zipp — Landing Page

Public marketing site for **Zipp**, a cross-border payment automation platform for Latin American SME importers paying European suppliers.

**Live:** [tryzipp.com](https://tryzipp.com)
**Product app:** `app.tryzipp.com` *(coming Q3 2026)*

## Stack

- Static single-page site (`index.html`) — no build step
- Hosted via GitHub Pages on the `main` branch
- Waitlist submissions handled by [Formspree](https://formspree.io)

## Local preview

```bash
open index.html
```

Or serve locally:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Deployment

Pushes to `main` auto-deploy via GitHub Pages within ~1 minute.

## Repo conventions

- Keep `index.html` self-contained — embed CSS and images inline where possible to keep the deploy a single static file.
- One commit per meaningful change. Descriptive commit messages (e.g. `Fix circular CTA link in hero`, not `update`).
- No secrets, API keys, or private data in this repo — it is public.

## Related repos

- `zipp-gateway` — React frontend (the product app)
- `zipp` — backend (invoice extraction, payment orchestration)

---

© 2026 Zipp
