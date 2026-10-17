# Editing your homepage

This site is a standalone static GitHub Pages website inspired by the *layout direction* of chrockey.github.io, with its own implementation.

## Change content
- **Biography and links:** edit `index.html` (replace `YOUR_EMAIL@example.com`).
- **News:** edit `data/news.json`.
- **Publications:** edit `data/publications.json`. Provide an `image` path such as `/img/my-paper.png` when you have a thumbnail. Fill the `links` object with Paper, Code, Project, etc.
- **Projects:** edit `data/projects.json`.
- **Animated name:** change `NAME` in `hero.js`.
- **Design:** edit the CSS variables at the top of `style.css`.

Do not publish placeholder contact information or unverified author lists. The included entries are starter content, not a complete CV.

## Deployment
Merge this pull request into `main`. GitHub Pages should be configured in **Settings → Pages → Deploy from a branch → main → /(root)**. The `.nojekyll` file disables Jekyll so this site takes precedence over the old `index.md`. The old Jekyll files remain in the repository but are unused. Use relative-to-root asset paths on the user site https://yemokoo.github.io/.

## Local preview
From the project directory run `python3 -m http.server 8000` and open http://localhost:8000.
