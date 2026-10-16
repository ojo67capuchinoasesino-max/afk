# Palette's Journal - Critical Learnings

## 2025-10-16 - ARIA Labels for Icon-Only Controls and Sliders in Static HTML App
**Learning:** Pure HTML/static applications often lack accessible names for icon-only buttons (`.round-play`) and range inputs paired with separate number inputs/labels. Adding explicit `aria-label`s significantly improves screen reader usability without altering layout or functionality.
**Action:** Always check icon-only buttons and unlabeled range inputs for missing `aria-label` attributes in static templates.
