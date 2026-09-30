# Finnley's developer portfolio

<p align="center">
  <a href="https://github.com/KeyErrorFinn/KeyErrorFinn.github.io/commits/main"><img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/KeyErrorFinn/KeyErrorFinn.github.io" /></a>
  <a href="https://git.finnley.co.uk/"><img alt="Live portfolio" src="https://img.shields.io/badge/live%20portfolio-open-22C55E" /></a>
  <img alt="HTML5" src="https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=fff" />
  <img alt="CSS" src="https://img.shields.io/badge/CSS-1572B6?logo=css&logoColor=fff" />
  <img alt="GitHub Pages" src="https://img.shields.io/badge/GitHub%20Pages-222222?logo=githubpages&logoColor=fff" />
</p>

The source for [git.finnley.co.uk](https://git.finnley.co.uk/), a responsive portfolio of selected engineering work and current projects.

## What it includes

- Professional positioning as a Software & AI Engineer.
- Compact project case studies covering browser, desktop, automation, and C# work.
- A restrained programmer-focused visual system using editor panels, monospace details, and code syntax colours.
- Screenshot cards and code-based previews so projects remain consistent even when no product image is available.
- Technical summaries for RepQuest and WoL Plus while they remain in development.
- Direct links to public source code and live applications where available.
- Quick link to LinkedIn from the hero and About sections.
- Project screenshots and social-preview artwork stored with the site rather than loaded from third-party hosts.
- Responsive, accessible HTML and CSS with no client-side framework.

## Local preview

~~~bash
python -m http.server 8000
~~~

Then open `http://localhost:8000`.

## Deployment

GitHub Pages serves `index.html` and `styles.css` directly from the configured publishing branch. The `CNAME` file keeps the custom domain attached.

## Files

- `index.html`, semantic page structure, project case studies, and social metadata.
- `styles.css`, responsive editor-inspired layout and visual design.
- `assets/projects/`, locally hosted project screenshots.
- `assets/social-card.png`, the sharing preview used by social platforms.
- `assets/favicon.svg`, the browser icon.
- `CNAME`, custom GitHub Pages domain.

## Updating the portfolio

When adding a featured project, keep its summary focused on the problem, implementation, and result. Link to a detailed repository README rather than duplicating setup instructions here.

No project-level licence is currently included.
