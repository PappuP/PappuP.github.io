# Pappu Paul — academic website

A simple single-page site for GitHub Pages. It has no build step and does not need Jekyll.

## Files
- `index.html`: all the content
- `style.css`: the styling (light and dark mode switch automatically)
- `profile.jpg` (optional): your photo. If it's missing, the site uses your department profile photo, and if that can't load, it shows the initials "PP".
- `cv.pdf` (optional): to add your CV, upload it, then un-comment the CV link in `index.html`.

## Publish on GitHub Pages
1. Create a new **public** repository named exactly `yourusername.github.io`.
2. Upload these files using **Add file → Upload files**, then commit.
3. Open **Settings → Pages** and set Source to **Deploy from a branch**, with branch `main` and folder `/ (root)`.
4. After a minute or two, the site is live at `https://yourusername.github.io`.

## Updating
- To add a paper, copy one `<li>...</li>` block in the Publications section.
- When a paper under review is accepted, move its block from "Under Review & In Preparation" to "Peer-Reviewed" and add a DOI link.
