# fabianschilling.org

Personal website. Static HTML and CSS, no build step, no dependencies.

Hosted on [GitHub Pages](https://pages.github.com). The `.nojekyll` file tells Pages
to serve the files as they are instead of running them through Jekyll.

## Running locally

Open `index.html` in a browser, or serve the directory to get correct absolute paths
for the favicons:

```sh
python3 -m http.server 8000
```

Then visit <http://localhost:8000>.

## Layout

- `index.html` — the entire page.
- `style.css` — all styling, including the `prefers-color-scheme` dark variant.
- `assets/images/` — portrait.
- `assets/logos/` — institution logos for the timeline.

Everything else in the repo root is favicon and web-manifest files.
