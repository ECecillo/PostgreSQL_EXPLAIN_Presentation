# PostgreSQL EXPLAIN — the life of a SQL query

Slides for a talk (in French, *« La vie d'une requête SQL »*) on how PostgreSQL
turns a query into a plan: parser, rewriter, planner/optimizer, executor, and how
to read `EXPLAIN` / `EXPLAIN ANALYZE` output. Built with [Astro](https://astro.build).

**Live:** <http://ececillo.me/PostgreSQL_EXPLAIN_Presentation/>

## Run locally

```bash
npm install
npm run dev      # http://localhost:4321
npm run build    # static site in dist/
```

Diagrams (Excalidraw sources and exports) live in `doc/excalidraw-schema/`.
Pushes to `main` build the site and deploy it to GitHub Pages
(`.github/workflows/deploy.yml`).
