## 2024-10-17 - Icon-only buttons accessibility
**Learning:** Icon-only control buttons in static HTML simulations missing explicit ARIA labels reduce screen reader accessibility, even if `title` is provided. Adding `aria-label` ensures explicit, accessible descriptions.
**Action:** Always verify icon-only buttons have explicit `aria-label` attributes alongside `title` or tooltip attributes.
