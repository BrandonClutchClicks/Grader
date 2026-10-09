# Clutch Clicks Call Grades (Cloudflare Pages site)

A static site. No build step.

- `index.html` is the page.
- `grades/index.json` is the list of calls (one short entry per call, with no scores).
- `grades/<id>.json` is one full grade per call.

To add a grade: add its `grades/<id>.json` file and add its entry to `grades/index.json`. Cloudflare republishes the site on every commit.

Cloudflare Pages settings: framework preset None, build command empty, build output directory `/`.
