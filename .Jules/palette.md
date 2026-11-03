# Palette's Journal

## 2026-09-12 - Accessible naming for paired slider-number inputs & icon-only buttons
**Learning:** In dual-input controls (such as synchronized range slider and number input pairs), labeling only the number input leaves the range slider without an accessible name for assistive technology and screen readers. Additionally, icon-only action buttons relying solely on `title` attributes need explicit `aria-label` attributes to ensure consistent accessible naming across all user agents.
**Action:** When implementing dual slider/number controls, ensure both interactive inputs have distinct accessible names (e.g. specifying "Control deslizante de [parámetro]" on the range input), and always include `aria-label` on icon-only buttons.
