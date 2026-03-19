# alt:V Website Clone

A clone of the [alt:V](https://altv.mp) website — the free GTA:V multiplayer modification. Built with Astro and Tailwind CSS as a fully static site.

Powered by [vertex](https://vertexmods.com)

## Preview
<img width="3126" height="1632" alt="CleanShot 2026-03-19 at 07 58 38@2x" src="https://github.com/user-attachments/assets/dc61c2de-32a0-4d35-a0a9-c583c674bd0f" />

## Tech Stack

- **[Astro](https://astro.build)** v5 — Static site generator
- **[Tailwind CSS](https://tailwindcss.com)** v4 — Utility-first styling
- **TypeScript** — Strict mode

## Project Structure

```
src/
├── components/
│   ├── Header.astro
│   ├── Hero.astro
│   ├── Showcase.astro
│   ├── Features.astro
│   ├── Developers.astro
│   ├── FAQ.astro
│   └── Footer.astro
├── layouts/
│   └── Layout.astro
├── pages/
│   └── index.astro
└── styles/
    └── global.css
```

## Getting Started

```bash
npm install
npm run dev
# → http://localhost:4321
```

## Commands

| Command           | Action                                     |
| :---------------- | :----------------------------------------- |
| `npm run dev`     | Start local dev server at `localhost:4321` |
| `npm run build`   | Build production site to `./dist/`         |
| `npm run preview` | Preview production build locally           |

## Deployment

Fully static — no environment variables required. Deploy to any static host:

- **Vercel**: `vercel deploy`
- **Netlify**: `netlify deploy --dir=dist`
- **GitHub Pages**: push `./dist/` to `gh-pages` branch

Note: The site is static without functions (yet). Feel free to develop and add features via PR
