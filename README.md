# muzz-yasir.github.io

Personal site built with [Zola](https://www.getzola.org/).

## Run it locally

Zola is already installed on this Mac. From this folder, run:

```sh
zola serve
```

Then open the local address printed by Zola (normally `http://127.0.0.1:1111`). It watches the site files and refreshes the browser after edits.

The main things to edit are:

- `content/` for pages and posts (Markdown)
- `templates/base.html` for the page shell
- `public/style.css` for styling
- `public/images/` for images

To produce a production build locally:

```sh
zola build --output-dir dist
```

`dist/` is generated and deliberately not committed.

## Free hosting on GitHub Pages

The workflow in `.github/workflows/zola.yml` builds the site and deploys it through GitHub Pages whenever `main` changes. It publishes at:

`https://muzz-yasir.github.io`

One-time GitHub setup: open the repository’s **Settings → Pages**, set **Source** to **GitHub Actions**, then push this configuration to `main`. The next workflow run publishes the site. The former `discretedeliberations.xyz` custom-domain configuration has been removed, so the expired domain is no longer involved.
