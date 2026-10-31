# Palette's UX Journal

## 2026-10-31 - Accessible Name for Icon-Only Simulation Action Controls
**Learning:** Icon-only buttons used as quick action controls over canvas or simulation viewports frequently rely solely on visual cues (SVG icons) or generic HTML `title` attributes, leaving screen reader users without an explicit, programmatic accessible name.
**Action:** Always provide descriptive `aria-label` attributes on icon-only simulation action buttons (e.g., `aria-label="Iniciar simulación"`) rather than relying only on `title` or SVG graphics.
