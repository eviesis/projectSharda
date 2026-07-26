# Project SHARDA — Website

Everything lives in ONE flat folder now — no subfolders — so that dragging
these files into GitHub's upload box (or replacing the ones already there)
always matches what the HTML expects. Don't put anything into a subfolder.

## Files
```
index.html         → homepage (short, single scroll)
about.html         → About page
programmes.html    → placeholder — content comes next pass
explorer.html      → placeholder — Heritage Explorer / interactive map, next pass
stories.html       → placeholder
impact.html        → placeholder
involved.html      → placeholder — Partner / Volunteer / Donate
resources.html     → placeholder
news.html          → placeholder
contact.html       → placeholder
style.css          → all design tokens, layout, components
main.js            → mobile nav toggle, scroll-reveal, impact counters
```

## Fixing your current repo (sharda-heritage)
Your repo currently has `style.css`, `main.js`, and `about.html` at the root
(good — flat is what we want), but the old `index.html` was pointing to
`assets/style.css` and `pages/about.html`, which don't exist there. That's
why the page loaded with no styling.

**To fix it:** in your repo, click into `index.html` → the pencil/edit icon →
select all → delete → paste in the new `index.html` content from this folder
→ commit. Do the same for `about.html` (its paths changed too). Then add the
7 new placeholder pages (`programmes.html`, `explorer.html`, `stories.html`,
`impact.html`, `involved.html`, `resources.html`, `news.html`, `contact.html`)
using **Add file → Upload files**, dragging them in directly — since
everything here is flat with no folders, there's nothing to lose this time.

## Publishing to GitHub Pages
Settings → Pages → Source → Deploy from branch → `main` → `/ (root)`.
Site will be live at `https://<your-username>.github.io/<repo-name>/`.
Your username stays visible in that URL unless you add a custom domain later.

## Next steps once homepage is approved
- Build out programmes.html, explorer.html, etc. with real content
- Replace placeholder `data-count-to="0"` in index.html with real numbers
- Swap SVG accents for real photography once available
