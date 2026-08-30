# AI Engineering Learnings

A growing, browsable collection of memory-first notes about AI engineering.

## Read locally

Open `index.html` in a browser, or serve the repository root with any static file server.

## Publish with GitHub Pages

In the repository settings, choose **Pages → Deploy from a branch**, select the branch you publish from, and use the repository root (`/`) as the folder. The site uses relative links, so it works both locally and at a GitHub Pages project URL.

## Add another chapter

1. Add a new HTML file under `chapters/` and link `../styles.css` in its `<head>`.
2. Use the shared `.site-header`, `.page`, `.hero`, `.section`, and `.card` classes for a consistent reading layout.
3. Add the chapter to the chapter list in `index.html`.
