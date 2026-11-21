# Prince Kurt Sherlock G. Ceria — Portfolio

## Live website

[View the portfolio](https://neogenproject.princekurtgceria18.workers.dev/)

## What I built

This is a responsive, multi-page portfolio for my Computer Engineering studies and projects at the University of the Immaculate Conception in Davao. It presents my background, skills, projects, engineering notes, contact information, and blog posts. Astro renders the `.astro` pages as a static website, with shared styling in an external CSS file.

The portfolio includes:

- `/` — overview and portfolio highlights
- `/about/` — background and interests
- `/skills/` — skills and technical tools
- `/projects/` — engineering and research projects
- `/engineering-log/` — engineering notes with CSS-only topic filters
- `/contact/` — contact information and email handoff form
- `/blog/` and `/blog/<post>/` — blog index and posts

## Project structure

- `src/pages/` contains the active Astro routes.
- `public/styles.css` contains the shared external stylesheet.
- `public/images/` contains images used by the site.
- `src/stitch-export/` contains the original Stitch HTML exports for reference. The active routes do not depend on these copies to build or run.

## Run locally

Use Node.js `22.23.4` or newer and npm:

```sh
npm ci
npm run dev
```

Open the local URL printed by Astro, usually `http://localhost:4321`.

To create and preview the production build:

```sh
npm run build
npm run preview
```

Astro writes the static site to `dist/`.

## Deployment

The portfolio is deployed on Cloudflare at the live URL above. The project is built with `npm run build`, and the generated static files are in `dist/`. There is no separate deployment command configured in `package.json`.

## Contact form behavior

The contact and dispatch forms use `mailto:` actions. Submitting them opens the visitor's default email application; this static site does not store or send form data through a backend.

## Reflection

- **What was the hardest part?** Fine-tuning the details and information so the portfolio represented me accurately.
- **What would I improve?** I would improve readability by reducing or organizing some of the longer text, since some visitors may not want to read as much. I still like the portfolio as it is now.

## AI use acknowledgement

Google Stitch was used to generate the initial design and HTML exports. GitHub Copilot AI assistance was used to integrate the pages, images, and navigation; convert the page routes to Astro while preserving the design and external CSS; and check responsive behavior and accessibility. I am responsible for reviewing and understanding the code in this project.
