# How to edit Yemo Koo's homepage

This version uses the HTML/CSS/JavaScript structure of [chrockey.github.io](https://github.com/chrockey/chrockey.github.io), with attribution in THIRD_PARTY_NOTICES.md.

- **Name and biography:** edit `index.html`. The visible animated name is in `hero.js` at `const text = 'Yemo Koo';`.
- **News:** edit `data/news.json`.
- **Publications:** edit `data/publications.json`, using `authors` as an array of names, and `links` as an object (e.g., `{"Paper":"https://..."}`). The current author list is incomplete; replace it with the correct one.
- **Coauthor links:** edit `data/coauthors.json`.
- **Design:** edit `style.css`. The reference animation depends on `--accent` and `--award` colors; do not rename those variables without updating `hero.js`.
- **Research links:** add real email/CV/Scholar links in `index.html` once available.
- **Hero animation:** the canvas ID `hero-cloud` must match `index.html`, `style.css`, and `hero.js`.

There is no Projects section in this version. The old project JSON file remains in the repository but is unused.

Merge the PR and check Settings → Pages → main / root. When editing, update `main` after merging.