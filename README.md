# KeyErrorFinn.github.io

A minimal GitHub Pages site for the `KeyErrorFinn` account.

## Current page

`index.html` is a small placeholder page titled “Main Page”. The `CNAME` file configures the custom domain used by GitHub Pages.

## How it works

GitHub Pages serves `index.html` directly from the configured publishing branch. There is no build system or server-side component.

## Local preview

Open `index.html` in a browser, or serve the directory with Python:

```bash
python -m http.server 8000
```

Then visit `http://localhost:8000`.

## Deployment

Push changes to the branch selected in the repository's **Settings → Pages** configuration. Keep `CNAME` in the published root if the custom domain should remain active.
