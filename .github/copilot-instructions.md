# Copilot instructions

- Keep this project as a single, self-contained `index.html`; do not add a server, build step, or external dependencies unless explicitly requested.
- Keep page structure, styling, and quiz logic in that file. Match the existing visual language and narrow, centered layout.
- Preserve responsive behavior, system light/dark theme support via `prefers-color-scheme`, visible keyboard focus, semantic controls, and accessible status announcements.
- Respect `prefers-reduced-motion` for animations. Keep decorative visuals hidden from assistive technology and non-interactive.
- Keep the 10-question quiz flow, answer feedback, score/progress updates, and results behavior in sync when changing quiz logic.
- Validate inline JavaScript syntax after script changes. When available, use the integrated browser to check the affected interaction and both relevant UI states.
