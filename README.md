# Shiyu CV

An Astro-powered static CV site.

## Commands

| Command        | Action                                     |
| :------------- | :----------------------------------------- |
| `pnpm install` | Install dependencies                       |
| `pnpm dev`     | Start local dev server at `localhost:4321` |
| `pnpm build`   | Build the production site to `./dist/`     |
| `pnpm preview` | Preview the production build locally       |

## Source Files

- `src/pages/index.astro`: resume content and page structure
- `src/components/ResumeSection.astro`: timeline-style sections
- `src/components/KeyValueSection.astro`: compact label/value sections
- `src/styles/global.css`: Tailwind entrypoint and small global defaults
