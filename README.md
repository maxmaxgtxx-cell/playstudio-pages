# playstudio-pages

Free static hosting (GitHub Pages) for Play Studio concept pages, so the bots never spend Lovable credits on samples.

- Live base: https://maxmaxgtxx-cell.github.io/playstudio-pages/
- `g/<slug>/index.html` — corporate & community holiday gift concepts, built from `templates/corporate-gift.html`
- `c/<slug>/index.html` — gig concepts (landing pages, mockups) for freelance proposals
- Every page carries `noindex`, an honest "Concept by Play Studio — not affiliated" banner, the studio address and an opt-out line.

## Template placeholders (corporate-gift.html)

| Placeholder | Meaning |
| --- | --- |
| `{{ORG}}` | Organisation name exactly as on its own website |
| `{{ORG_SHORT}}` | Short form for small items (ornament, mug) |
| `{{ORG_URL}}` | URL-encoded org name for the mailto subject |
| `{{SEGMENT}}` | e.g. Senior living, Restaurant, University department |
| `{{LEAD}}` | One honest sentence about why this fits them |
| `{{YEAR}}` | 2026 |

Rules: no logos unless public on the organisation's own site, no invented facts, no prices until the Printify cost is confirmed, printed items are never called engraved.
