## 2025-10-22 - Accessibility for Icon-Only Simulation Control Buttons
**Learning:** Icon-only interactive buttons (such as simulation start/play controls) that rely only on `title` tags lack explicit accessible names for screen readers.
**Action:** Always add an explicit `aria-label` attribute (e.g. `aria-label="Iniciar simulación"`) to icon-only control buttons to ensure full WCAG accessibility.
