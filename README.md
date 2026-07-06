# alexander-alleman.github.io

A clean, static academic site — plain HTML/CSS, no build step. GitHub Pages
serves it as-is.

## Files
```
index.html          About / home (profile sidebar + bio)
research.html       Research areas
publications.html   Full publication list (grouped by year, DOI links)
teaching.html       Courses + mentoring
cv.html             CV summary + embedded PDF
assets/css/style.css   All styling (edit the tokens at the top to re-skin)
assets/cv/Alleman_CV.pdf   Your CV (swap in an updated file anytime)
assets/img/            Put profile.jpg here (see below)
```

## Deploy
1. Copy everything in this `site/` folder into the **root** of your
   `alexander-alleman.github.io` repository (so `index.html` sits at the top level).
2. Commit and push to the `main` branch.
3. In the repo: **Settings → Pages →** Source = *Deploy from a branch*,
   Branch = `main` / `/ (root)`.
4. Your site goes live at `https://alexander-alleman.github.io/` within a minute or two.

No Jekyll, Ruby, or gems required. (If your repo still contains the old
AcademicPages files, delete them first so they don't conflict.)

## Add your photo
Drop a square headshot at `assets/img/profile.jpg`. Until you do, the sidebar shows
a teal "AA" monogram — it's designed to look intentional either way, so there's no
rush. A ~600×600 px JPG looks crisp.

## Customize
- **Accent color / fonts:** edit the `:root` tokens at the top of
  `assets/css/style.css`. Change `--accent` once and the whole site re-skins.
- **New publication:** copy a `.pub` block in `publications.html` and update the
  text + DOI. Add the DOIs for the two bioRxiv preprints once they're assigned.
- **Twitter/X, Bluesky, etc.:** add another `<a>` inside the `.social` block in
  `index.html` using any Tabler icon (e.g. `ti-brand-bluesky`).
- **Talks & outreach page:** easy to add later — same header/footer, a new list.
