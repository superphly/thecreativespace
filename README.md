# thecreativespace.org

The Creative Space — a coworking office in Downtown Bryan, Texas. Static Jekyll
site for GitHub Pages, restored from the original WordPress site as it stood in
February 2012.

## Provenance

Content was exported directly from the WordPress MySQL database during the
2026-08 decommission of the old server (see the droplet salvage archive,
`1-site-content/thecreativespace/`). No PHP or executable code from that server
is present here — only Markdown, media files verified image/PDF-only, and
templates written fresh.

Each content file keeps its original `wordpress_id` and `original_url` in
frontmatter for traceability.

## Structure

- `_residents/` — 20 resident profiles (grouped Current / Adjunct / Alumnus)
- `_projects/` — 6 projects that grew out of the Space
- `_data/highlights.yml` — home-page highlights (the old rotator items)
- `about.md`, `collaborations.md`, `contact.md`, `join.md`, `location.md` — pages
- `media/` — original WordPress uploads, referenced as `/media/YYYY/MM/...`

## Local preview

```sh
bundle install
bundle exec jekyll serve
```

## Deploy

Push to GitHub, then Settings → Pages → deploy from branch `main`, root.
`CNAME` points the site at thecreativespace.org; add the matching DNS records
(A records to GitHub Pages IPs, or a CNAME for `www`) at the registrar.
