# pondigo.github.io

Personal site and technical blog — built with [Astro](https://astro.build), deployed to GitHub Pages.

**Live at**: [pondigo.github.io](https://pondigo.github.io/)

## Structure

```text
src/
├── components/
│   ├── Header.astro
│   ├── About.astro
│   ├── Summary/
│   └── paper/          # Reusable blog layout components
├── layouts/
│   ├── Layout.astro    # Main site layout
│   └── PaperLayout.astro  # Blog post layout (sidebar, theme toggle)
├── pages/
│   ├── index.astro     # Landing page
│   └── blog/
│       ├── index.astro # Blog index
│       ├── ai/         # AI research & techniques
│       │   ├── ai-testing/
│       │   └── skimming-scanning/
│       └── specs/      # Proposals & speculative designs
│           └── daisy-chains/
└── styles/
    └── paper/          # Blog post styles
```

## Blog sections

- **ai/** — Research notes on AI agents, testing strategies, and developer workflows
- **specs/** — Proposals and speculative designs (daisy chains, flow testing)
- **opinion/** — Opinion column (coming soon)

## Commands

| Command             | Action                                       |
| :------------------ | :------------------------------------------- |
| `npm install`       | Install dependencies                         |
| `npm run dev`       | Start local dev server at `localhost:4321`    |
| `npm run build`     | Build production site to `./dist/`           |
| `npm run preview`   | Preview build locally before deploying       |

Deployments are automatic via GitHub Actions on push to `main`.
