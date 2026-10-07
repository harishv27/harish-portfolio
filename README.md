# Harish V: Portfolio

Personal portfolio of Harish V, AI Engineer. Live at **https://harishvelayutham.vercel.app**

A single static page (`index.html`) with no build step. Deployed on Vercel.

## Structure

| Path | Purpose |
|---|---|
| `index.html` | The whole site: markup, styles, scripts |
| `assets/images/` | Optimised profile photo (`harish.webp`) and social preview (`og.png`) |
| `assets/resume/` | Downloadable resume PDF |
| `vercel.json` | Security and cache headers, redirect from the old preview domain |
| `robots.txt`, `sitemap.xml` | Crawler files |

## Run locally

```bash
python3 -m http.server 8000
# open http://localhost:8000
```

## Maintenance notes

- Role durations are computed in the browser from each role's `data-start="YYYY-MM"` attribute. To add a role, copy an existing `.role-item` and set the attribute (omit it for past roles with a fixed end date).
- To add a project, copy a `.project-card` article inside `#projects`.
- The contact form posts to Formspree.

## License

Code is MIT-licensed (see `LICENSE`). Personal photo, resume and written content are © Harish V and not covered by the licence.
