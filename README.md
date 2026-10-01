# Select Dental

Static website — no build step.

## Deploy to Hostinger
1. hPanel → Websites → your site → **Files → File Manager** (or Git → connect this repo).
2. Upload the contents of this repo into `public_html/`: `index.html`, `.htaccess`, and the `media/` folder.
3. Visit your domain. Pages use hash routes (e.g. `/#/services`), so no server rewrites are needed.

Using Hostinger's **Git** deployment: set repository to this repo, branch `main`, install path empty (deploys to `public_html`).
