# Latch — draft project site

[Read the draft](https://DeepakSingh98.github.io/latch-preview/)

This public repository contains the draft Latch project website for feedback, with public measurement summaries. It contains no compiler source, package archives, release manifests, raw internal receipts, model weights, datasets or private Git history. The compiler release is forthcoming.

## Local preview

Serve this directory with any static server and open `/site/`:

```sh
python3 -m http.server 8000 --bind 127.0.0.1
```

## Deployment

GitHub Pages serves the root of `codex/public-draft`; `index.html` redirects to `site/`. No build step is required. Push changes to that branch to update the draft.

The pages request that search engines not index them. This is a public website, not an access restriction. The compiler commands shown in the draft refer to the separately prepared, unpublished package.
