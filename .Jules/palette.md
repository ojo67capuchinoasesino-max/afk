# Palette's Journal - Critical Learnings

## 2025-02-18 - Single-file Static HTML Icon-only Button Accessibility
**Learning:** Icon-only interactive controls (such as simulation header play/pause buttons) in single-file HTML applications often lack explicit `aria-label` attributes even if `title` is present, leaving screen reader users without an accessible name.
**Action:** Always verify that every `<button>` containing only SVG icons includes a clear, localized `aria-label` attribute describing its function.
