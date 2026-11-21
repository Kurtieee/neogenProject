## Project guidelines

- Keep all routed pages as `.astro` files under `src/pages/`, preserving their current HTML markup; avoid client-side JavaScript unless requested.
- Keep visual styling in the external `public/styles.css`; avoid inline styles and `<style>` blocks.
- Preserve the shared navigation and footer across the main portfolio routes.
- Keep image assets local under `public/` and give images meaningful `alt` text.
- Preserve the untouched Stitch exports in `src/stitch-export/`.
- Verify page and asset routes with `npm run build` and test responsive layouts at 360px, 768px, and 1440px.
