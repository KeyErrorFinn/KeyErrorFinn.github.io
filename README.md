# KeyErrorFinn.github.io

<p align="center">
  <a href="https://github.com/KeyErrorFinn/KeyErrorFinn.github.io/commits/main"><img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/KeyErrorFinn/KeyErrorFinn.github.io" /></a>
  <a href="https://github.com/KeyErrorFinn/KeyErrorFinn.github.io/issues"><img alt="GitHub issues" src="https://img.shields.io/github/issues/KeyErrorFinn/KeyErrorFinn.github.io" /></a>
</p>

<p align="center">
  <img alt="HTML5" src="https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=fff" />
  <img alt="GitHub Pages" src="https://img.shields.io/badge/GitHub%20Pages-222222?logo=githubpages&logoColor=fff" />
  <img alt="Custom domain" src="https://img.shields.io/badge/Custom%20domain-0EA5E9?logoColor=fff" />
</p>

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

## Project flow

```mermaid
flowchart LR
    Source["index.html and CNAME"] --> Pages["GitHub Pages"]
    Pages --> Domain["git.finnley.co.uk"]
```
