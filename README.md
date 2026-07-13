# srijal27.github.io

Personal academic website for Sweta Rijal, Doctoral Candidate in Political Science at UC Berkeley.

## Structure

- `index.html` — Home / About page
- `research.html` — Research interests, projects, publications
- `contact.html` — Contact info and links
- `style.css` — Shared styling for all pages

## Editing content

Each page is plain HTML — open the file in any text editor and edit the text
between the tags. Look for `[bracketed placeholder text]` — those are the
spots meant to be filled in.

To add a new page (e.g. a CV or Teaching page):
1. Copy `contact.html` as a starting template (it has the shared header/nav/footer).
2. Rename it, e.g. `teaching.html`.
3. Replace the `<main>` content with your new content.
4. Add a link to it in the `<nav class="site-nav">` block on **every** page
   (index.html, research.html, contact.html, and any new pages) so the
   navigation stays consistent.

## Publishing changes

Any change pushed to the `main` branch on GitHub automatically updates the
live site within a minute or two, since this repo is named
`srijal27.github.io`.

```bash
git add .
git commit -m "Update research page"
git push
```

## Live site

https://srijal27.github.io
