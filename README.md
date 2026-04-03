# alexeihoffman.github.io

Personal site for Alexei Hoffman — aerospace, defense, and geopolitical risk.

## Deployment

1. Create a new repository on GitHub named `a-novi13-byte.github.io`
2. Push this entire folder to the repo's `main` branch
3. Go to **Settings → Pages** and set source to `main` branch, root folder
4. Your site will be live at `https://a-novi13-byte.github.io`

## To-Do Before Launch

- [ ] Replace `assets/images/headshot.png` with your professional photo (already included)
- [ ] Update `files/Alexei_Hoffman-CV.pdf` if needed (already included)
- [ ] Review all links on Research and Writing pages
- [ ] Add any forthcoming publications when ready

## Editing Content

All pages are plain HTML files in the root directory. The bio, publications, and writing entries can be edited directly. The site uses Jekyll with GitHub Pages — no build step needed on your end.

## Structure

```
├── _config.yml          # Site settings
├── _layouts/
│   └── default.html     # Main template (nav + footer)
├── assets/
│   ├── css/main.css     # All styles
│   └── images/          # Headshot, etc.
├── files/               # CV PDF
├── index.html           # Home page
├── cv.html              # CV page
├── research.html        # Publications & conferences
├── writing.html         # Policy writing & ISW entries
└── contact.html         # Contact info
```
