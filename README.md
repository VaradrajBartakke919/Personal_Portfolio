# Personal Portfolio

Professional, recruiter-facing portfolio for a Data Science / ML / GenAI engineer.

## Structure

```
portfolio/
├── index.html          # Single-page portfolio
├── css/
│   └── styles.css      # Custom CSS overrides (optional)
├── assets/             # Favicon, images (optional)
└── README.md
```

## Run locally

- **Option A:** Open `index.html` in a browser (file protocol).
- **Option B:** Serve with a local server:
  ```bash
  npx serve .
  ```
  Then open http://localhost:3000

## Deploy

### GitHub Pages

1. Push this repo to GitHub.
2. **Settings → Pages → Source:** Deploy from branch.
3. **Branch:** `main` (or your default), folder **/ (root)**.
4. Save. The site will be at `https://<username>.github.io/<repo-name>/`.

### Vercel

1. Install Vercel CLI: `npm i -g vercel`
2. In the project root: `vercel`
3. Follow prompts (defaults are fine for a static site).
4. Your site will get a URL like `https://portfolio-xxx.vercel.app`.

## Customize before deploy

Optional customizations:

- **Resume:** Add your resume PDF as `assets/resume.pdf` so the "Download Resume" button works (or set the button `href` to a Google Drive / external URL).
- **LinkedIn / GitHub:** Update the Contact section URLs if your handles differ from `varadrajbartakke`.
- **Project links:** Replace each project's `href="#"` with the real GitHub (or demo) URL.

## Tech

- HTML5, semantic markup
- Tailwind CSS (CDN)
- Minimal JavaScript (smooth scroll, year in footer)
- SEO meta tags and structure
