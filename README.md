# SATELLARIO — Space Landing Page

Marketing landing page for **SATELLARIO**, a space-tech venture providing real-time global GNSS jamming and spoofing detection through a constellation of edge-AI-powered PocketQube satellites.

## Live Site

**[satellario.space](https://satellario.space)**

Deployed via GitHub Pages from the `master` branch root.

## Contents

```
index.html   — Fully self-contained landing page (no external dependencies)
README.md    — This file
CLAUDE.md    — AI assistant context (git-ignored)
```

## Sections

1. **Hero** — Animated orbital globe with value proposition
2. **Mission Brief** — Three-segment capability overview
3. **Architecture** — Three core principles of on-orbit signal integrity
4. **Live Intelligence** — Simulated real-time GNSS threat alert feed
5. **Access** — Operator contact CTA

## Technology

- Pure HTML / CSS / JavaScript — no build step required
- Space Grotesk + Space Mono (Google Fonts, bundled as blobs)
- Animated orbital globe (SVG + CSS keyframes)
- Live alert feed simulation (client-side JS)
- Responsive: viewport meta + CSS `@media` overrides via `data-dc-tpl` selectors
- Bundled format: assets base64+gzip compressed, unpacked at runtime

## Responsive Design

Mobile support is added via CSS `@media` rules injected into `<head>` that override the bundled inline styles using `!important` and `data-dc-tpl` attribute selectors. The design is identical on desktop — only layout reflows at ≤ 768 px (tablet) and ≤ 480 px (phone).

Key breakpoints:
- **≤ 768 px** — nav links hidden, hero goes single-column, 3-col grids collapse, footer 2-col
- **≤ 480 px** — footer single-column

## Brand

| Token | Hex | Usage |
|---|---|---|
| Prussian Blue | `#112F56` | Authority, depth |
| Sky Blue | `#2F6DD0` | Signal, interaction (Calcio Lecco) |
| Amber | `#B7791F` | Alerts, highlights |
| White | `#FAFBFC` | Clarity, space |

## Contact

[access@satellario.space](mailto:access@satellario.space)

---

© 2026 SATELLARIO · Signal Integrity from Orbit
