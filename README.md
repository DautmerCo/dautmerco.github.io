# dautmerco.github.io

Source of my portfolio site: https://dautmerco.github.io

Plain HTML and CSS, no build step. Every push to `main` publishes the `site/` folder to GitHub Pages through the [Publish site](.github/workflows/pages.yml) workflow.

| Path | Content |
|---|---|
| `site/index.html` | English page |
| `site/es/index.html` | Spanish page |
| `site/assets/` | Styles, icon, and project screenshots |

To add a project, copy an `<article class="project">` block in both pages and add its screenshot to `site/assets/img/`.
