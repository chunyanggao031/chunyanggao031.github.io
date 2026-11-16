# Chunyang Gao — personal homepage (single-page version)

Plain HTML/CSS, no Jekyll, no build step. `.nojekyll` tells GitHub Pages to serve the files as-is.

```
index.html            all page content (edit text here)
assets/css/site.css   styles; colors are the variables at the top
assets/js/site.js     mobile menu toggle only
assets/images/        profile photo and project figures (keep each < ~300 KB)
files/                cv.pdf and project reports / posters / slides
```

Common edits:
- Update the CV: overwrite `files/cv.pdf` (keep the name so links never break).
- Add a project: copy one `<article class="project">…</article>` block in the Research section.
- Add a section: copy a `<section class="content-section" id="…">` block and add `<a href="#…">` to the nav.
- Preview locally: `python3 -m http.server` in this folder, then open http://localhost:8000.

Layout adapted from https://yunqianz728.github.io/.
