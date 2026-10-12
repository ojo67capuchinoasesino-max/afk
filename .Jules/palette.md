## 2025-10-12 - Interactive Physics Controls Accessibility
**Learning:** In interactive simulation GUIs, range sliders (`<input type="range">`) accompanying number inputs are often rendered without `aria-label` attributes, causing screen readers to omit parameter context when navigating controls.
**Action:** Always provide explicit, localized `aria-label` attributes for both range inputs and icon-only trigger buttons in simulation dashboards.
