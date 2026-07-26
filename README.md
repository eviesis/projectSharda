# Project SHARDA — Website

## Structure
```
index.html              → homepage (short, single scroll)
pages/                   → one file per nav destination (about, programmes,
                           explorer, stories, impact, involved, resources,
                           news, contact). All except about.html are
                           placeholder "coming soon" pages right now —
                           styled and linked, content comes in the next pass.
assets/style.css         → all design tokens, layout, components
assets/main.js           → mobile nav toggle, scroll-reveal, impact counters
```

## Publishing to GitHub Pages
1. Create a new repo on GitHub — name it whatever you like (e.g. `sharda-heritage`).
   The repo name is entirely your choice.
2. Push these files to the repo root (so `index.html` sits at the top level).
3. In the repo: **Settings → Pages → Source → Deploy from branch → main → / (root)**.
4. Your site will be live at `https://<your-username>.github.io/<repo-name>/`.

Your GitHub username will still show in that URL — that's how GitHub Pages
routes it. If you want the URL to show only your own domain (no GitHub trace
at all), buy a custom domain and add a `CNAME` file pointing to it, then set
it under Settings → Pages → Custom domain.

## Next steps once homepage is approved
- Build out each `pages/*.html` file with real content (About, Programmes,
  Heritage Explorer with the interactive map, etc.)
- Replace the placeholder `data-count-to="0"` values in the Impact section
  with real numbers.
- Swap the SVG motif/pattern accents for real photography once available.
