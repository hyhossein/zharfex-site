# zharfex.com

Static site for [zharfex.com](https://zharfex.com). **Generated — do not edit
by hand.**

Source lives in the private `zharfex` repository under `web/`; this repo holds
only the rendered output. Rebuild and sync with:

```bash
.venv/bin/python web/build.py     # -> site/
./web/sync-site.sh                # -> pushes site/ here
```

18 pages, two languages (`/` English, `/fa/` Persian). No build step, no
framework, no external dependency but Google Fonts.
