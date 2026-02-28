# AGENTS.md

## Cursor Cloud specific instructions

This is a **static HTML/CSS/JS** CV Generator with no build step, no backend, no npm dependencies, and no linter/test framework configured.

### Running the dev server

```bash
npx serve . -p 3001
```

The app is served at `http://localhost:3001/`. Key pages:
- `/` — Landing page
- `/cv-generator` — Form to enter details and fetch GitHub repos
- `/cv` — Generated CV (reads from `localStorage`, set by the generator page)

The `serve` package uses clean URLs (strips `.html` extensions).

### Notes

- There are **no automated tests or lint checks** in this project. The `package.json` has zero `dependencies` or `devDependencies`.
- The only external API call is to `https://api.github.com` (public, unauthenticated, 60 req/hr rate limit).
- Data flows between pages via `localStorage` — the generator page writes `cvData` and the CV page reads it.
- No environment variables or secrets are required.
