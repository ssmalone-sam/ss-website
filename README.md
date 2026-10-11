# ss-website

Personal site — static HTML/CSS, no build step. Deployed on Vercel.

## Structure

- `index.html` — page markup, including the project cards in `.project-grid`
- `style.css` — styles
- `vbmail.html` — vbMail project page; screenshots in `images/vbmail/` are copied from the vbMail repo's `public/landing/` (demo data only)
- `volleyscore.html` — VolleyScore project page; screenshots in `images/volleyscore/` are WebP copies of the volleyScore repo's `docs/screenshots/` (public ESPN data, shown as-is)

## Adding a project card

Add a new `<article class="project-card">` to `.project-grid` in `index.html`, with an `<h3>` title and a `<p>` description in the style of the existing cards.

## Run locally

Open `index.html` directly in a browser, or serve the directory with any static file server.
