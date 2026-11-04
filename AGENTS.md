# Agent instructions

Before working in this repository, read and follow these shared Lunchbox Labs documents:

- [Common agent guidance](https://github.com/lunchbox-labs/.github/blob/main/agent-guidance/common.md)
- [Workflow conventions](https://github.com/lunchbox-labs/.github/blob/main/agent-guidance/workflows.md)

Read these documents explicitly; GitHub does not automatically inherit them into this repository.

## Site

This repository is the Lunchbox Labs website, built with [Zensical](https://zensical.org) from the Markdown pages in `docs/` and configured in `zensical.toml`. Keep pages in Markdown; do not add hand-written HTML. The only stylesheet is `docs/stylesheets/brand.css`, which maps the [Lunchbox Labs brand colors](https://github.com/lunchbox-labs/.github/blob/main/brand/colors.md) onto the theme; keep it to color tokens and the overrides they need, and recheck contrast when it changes.

Build and preview locally:

```sh
python3 -m pip install -r requirements.txt
zensical build --clean --strict
zensical serve
```

The `Pages` workflow (`.github/workflows/pages.yml`) runs the same strict build on pull requests and deploys `site/` to GitHub Pages from `main`.
