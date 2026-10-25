## 2025-10-25 - [Accessibility for Static HTML Exports]
**Learning:** Exported static single-page applications (such as physics simulation tools) often duplicate form controls (e.g. range sliders paired with numerical inputs) or use icon-only action buttons without explicit ARIA labels.
**Action:** Always ensure that range sliders and icon-only buttons receive explicit `aria-label` attributes corresponding to their label text or function, even when adjacent numerical inputs already have labels.
