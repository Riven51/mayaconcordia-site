# Maya Concordia — founding circle site

Static site (no build step). Deploys to Netlify as-is.

- `index.html` — the whole page (CSS and JS inline)
- `assets/` — images (`og-image.jpg` is the social share preview)
- `thanks/index.html` — fallback page after the form is submitted without JavaScript
- `netlify.toml` — publish settings and security headers

## Things to edit
- Instagram and LinkedIn links: search `index.html` for `instagram.com` and `linkedin.com` (two places each: the success message and the footer).
- Form: handled by Netlify Forms (form name `founding-circle`). Turn on email alerts in Netlify: Forms > Form notifications.
