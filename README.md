# Academic website

A simple, fast, single-page academic site for GitHub Pages. No build step, no Jekyll required.

## Files
- `index.html` — all the content (edit text here)
- `style.css` — styling (light/dark mode automatic)
- `profile.jpg` — add your photo (square works best). If missing, initials show instead.
- `cv.pdf` — add your CV

## Publish on GitHub Pages
1. Create a new public repository named exactly `yourusername.github.io`.
2. Upload these files (Add file → Upload files), then commit.
3. Go to **Settings → Pages**, set Source to "Deploy from a branch", branch `main`, folder `/ (root)`.
4. After a minute or two, the site is live at `https://yourusername.github.io`.

## Editing tips
- Search `index.html` for "Your Name", "Your Field", "Your University", and the placeholder links.
- Add a publication by copying one `<li>...</li>` block in the Publications section.
- Remove any section (News, Teaching) by deleting its `<section>...</section>` block — and its nav link.
