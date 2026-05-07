# Ultimate Search Operator Builder

A dependency-free, single-file HTML app for visually building advanced Google search queries.

## Cloudflare Pages deployment

Use these settings in Cloudflare Pages:

| Setting | Value |
| --- | --- |
| Framework preset | `None` |
| Build command | `npm run build` |
| Build output directory | `dist` |
| Root directory | `/` or leave blank |

The build script copies the root `index.html` into `dist/index.html`, which gives Cloudflare Pages a concrete output folder to publish and prevents the root URL from returning a 404.

## Local preview

Open `index.html` directly in a browser, or run any static file server from the repository root.
