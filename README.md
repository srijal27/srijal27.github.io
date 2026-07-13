# srijal27.github.io

Personal academic website for Sweta Rijal, Doctoral Candidate in Political Science at UC Berkeley.

## Structure

This is a single-page site — everything lives in `index.html`, split into
sections you scroll (or jump to) via the nav bar:

- **Header** — name, one-line title, bio, CV link
- **Research** (`#research`) — research interest tags + publications list
- **Works in Progress** (`#projects`) — working papers / dissertation chapters
- **Contact** (`#contact`) — email and department info
- `style.css` — all styling (fonts, colors, layout, animations)

## Editing content

Open `index.html` in any text editor. Look for `[bracketed placeholder text]`
or `<!-- comments -->` — those mark the spots meant to be filled in:

- Add your real email in the header and Contact section
- Link your actual CV PDF in the "CV (PDF)" link
- Add publications by copying an existing `<div class="paper">...</div>`
  block under Research and filling in the title, venue, year, authors,
  links, and abstract
- Add working papers the same way under Works in Progress

To add a whole new section (e.g. Teaching):
1. Copy one of the existing `<section>` blocks as a template.
2. Give it a new `id` (e.g. `id="teaching"`).
3. Add a matching link in the `<ul class="nav-links">` block, e.g.
   `<li><a href="#teaching">Teaching</a></li>`.

## Publishing changes

Any change pushed to the `main` branch on GitHub automatically updates the
live site within a minute or two, since this repo is named
`srijal27.github.io`.

```bash
git add .
git commit -m "Update research section"
git push
```

## Live site

https://srijal27.github.io
