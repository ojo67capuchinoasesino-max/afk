# Palette's Journal

## 2026-09-12 - Paired Numeric and Range Slider Accessibility in HTML Simulators
**Learning:** In scientific and simulation UI patterns where number inputs are paired with companion range sliders for the same parameter, the number input often has an `aria-label` while the range slider lacks one. Screen reader users navigating by form controls encounter unlabeled sliders or ambiguous duplicates.
**Action:** When pairing a numeric input and a range slider, distinguish the companion slider's accessible name (e.g. appending "(control deslizante)" or "(slider)") so users of assistive tech immediately recognize the control type and function.
