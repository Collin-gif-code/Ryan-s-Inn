# Ryan's Inn Starter

Static one-file web app for Netlify + GitHub.

## Structure

- `index.html` — all HTML, CSS and JavaScript
- `data/whiskeys.json` — whiskey database
- `images/pub/` — pub photos
- `images/bottles/` — bottle cutouts/photos
- `images/history/` — history/timeline images
- `images/ui/` — logos and decorative assets

## Important

Open the project through a web server rather than by double-clicking `index.html`,
because the browser may block `fetch("data/whiskeys.json")` from `file://`.

On Netlify this works normally.

For local testing you can use, for example:

    python -m http.server 8000

and then open:

    http://localhost:8000
