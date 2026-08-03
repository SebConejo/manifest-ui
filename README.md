# manifest-ui

Design system for the Manifest website. All components are plain HTML + BEM CSS — no framework, no React.

## Development

```bash
npm install
npm run dev
```

## Structure

- `src/pages/tokens/` — design tokens (colors, typography, spacing, breakpoints, borders)
- `src/pages/components/` — one page per component with preview and class reference
- `src/styles/manifest.css` — the complete design system CSS (sourced from mnfst/website)
- `src/styles/docs.css` — styles for the documentation shell only
- `registry/components.json` — machine-readable component index for agents

## For agents

Read `registry/components.json` for the complete machine-readable index. Read `llms.txt` for full instructions.
