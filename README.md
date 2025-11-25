# IBDAL Lab Website

This repository hosts the landing page for the Intelligent Biomedical Data & AI Lab. The site highlights lab news, research areas, publications, members, and contact details in an elegant, concise style.

## Getting started

Open `index.html` in a modern browser to view the site. All styles are defined in `assets/style.css`; update the content directly in the HTML to tailor news, publications, and team information.

### Add to a designated repository
If you want this site to live in a different GitHub repository for testing or publishing:
1. **Create or open the target repository** (empty or existing).
2. Copy the project contents into that repository root:
   ```bash
   cp -R index.html assets README.md /path/to/target-repo/
   ```
3. From the target repository, commit and push:
   ```bash
   cd /path/to/target-repo
   git add .
   git commit -m "Add lab website"
   git push origin main  # or your preferred branch
   ```
4. To preview locally, open `index.html` directly in a browser or serve the folder (e.g., `python -m http.server 8000`).
5. To publish with GitHub Pages, enable Pages in the repository settings and point it to the branch that contains `index.html` (typically `main`), using the root directory.
