# Prince Nelson Aguinaldo Jr. — Portfolio

A static one-page portfolio site. No build step, no framework — plain HTML/CSS/JS.

## Structure

```
index.html      → all page content
styles.css      → design system + layout
script.js       → scroll-reveal animation + footer year
images/         → profile photo (profile.jpg used on the page, profile.png kept as a transparent-background alternate)
Prince_Nelson_Aguinaldo_Resume.pdf  → linked from the "Download résumé" button
```

## Deploy to Vercel

**Option A — drag and drop (fastest)**
1. Go to https://vercel.com/new
2. Drag this whole folder onto the upload area
3. Deploy — no framework preset or build command needed (it's a static site)

**Option B — Vercel CLI**
```bash
npm i -g vercel
cd portfolio
vercel
```
Follow the prompts and accept the defaults (no build command, output directory is the project root).

**Option C — GitHub**
1. Push this folder to a new GitHub repo
2. In Vercel, "Add New Project" → import the repo
3. Framework preset: **Other** — leave build command and output directory blank
4. Deploy

## Before you deploy

- Swap in your real domain / update the meta tags in `index.html` if you want a custom `og:url`.
- Replace `images/profile.jpg` if you ever want a different photo — keep it square for the layout to line up cleanly.
- Update the résumé PDF filename in `index.html` if you rename it.
