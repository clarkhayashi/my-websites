# Clark's Reading Notes

A portable, static version of Clark Hayashi's reading-notes site. The complete site uses no build tools or third-party JavaScript libraries. Book covers are stored locally under `assets/covers`, so the page does not need external network access.

## Run locally

Open `index.html` directly in a browser, or serve the directory with:

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## Publishing

This project is designed to live inside Clark's `my-websites` repository. With GitHub Pages enabled for that repository, it appears at:

`https://clarkhayashi.github.io/my-websites/clark-reading-notes/`

The search and status filters run entirely in the browser.
