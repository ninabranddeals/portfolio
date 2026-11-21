# Nina Carter website

Static site (single `index.html` + `assets/`). No build step.

## Publish on GitHub Pages
1. Create a new GitHub repository (e.g. `nina-carter`).
2. Upload everything in this folder (`index.html`, `assets/`, `.nojekyll`, `README.md`) to the repository root.
3. Go to **Settings → Pages**. Under **Build and deployment**, choose **Deploy from a branch**, select `main` and `/ (root)`, then **Save**.
4. After a minute your site is live at `https://<username>.github.io/<repo>/`.
5. Optional custom domain: add it under Settings → Pages and set the DNS records GitHub shows.

## After going live, update in `index.html`
- `<link rel="canonical" ...>` → your real URL
- `og:image` → full URL of an image, e.g. `https://<username>.github.io/<repo>/assets/nina-hero.jpg`
- Footer `© [Operator name placeholder]`

## Replacing images
Overwrite files in `assets/` using the same filenames.

## Notes
- The sign-up form opens the visitor's email app with a pre-filled message to ninabranddeals@gmail.com; the visitor must press Send. For automatic emails, connect a form service (Formspree, Web3Forms, etc.) or a backend.
- There is no payment checkout; add one only through an approved payment provider.
