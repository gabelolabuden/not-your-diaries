# Not Your DIARIES

A responsive static prototype for a NutriLens-style health and food tracking app.

## Run locally

Open `index.html` directly in a browser.

Camera access may require browser permission. Some browsers restrict camera access on `file://`; if that happens, serve the folder locally:

```bash
npx serve .
```

## Deploy to Cloudflare Pages

Recommended Cloudflare Pages settings:

- Framework preset: `None`
- Build command: leave empty
- Build output directory: `/`
- Root directory: `/`

## GitHub Actions deployment

The included workflow deploys to Cloudflare Pages when code is pushed to `main`.

Required GitHub repository secrets:

- `CLOUDFLARE_API_TOKEN`
- `CLOUDFLARE_ACCOUNT_ID`

The Cloudflare Pages project name is configured as `not-your-diaries`.
