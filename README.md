# thecreativespace.org

The Creative Space — a coworking office in Downtown Bryan, Texas (2007–2012).
Static Jekyll site for GitHub Pages, preserving the site as it stood in
February 2012. The space is no longer operational; the site is maintained
for posterity.

## Provenance

Content was exported from the site's WordPress database when it moved to
static hosting in August 2026. Each content file keeps its original
`wordpress_id` and `original_url` in frontmatter for traceability. The look
and feel is the original cs-3.0 theme (a Genesis child theme by Bill
Erickson): paper background with watercolor artwork, black pill navigation,
white content card, and red accents.

## Structure

| Path | What |
| --- | --- |
| `_residents/` | 20 resident profiles |
| `_projects/` | 6 projects that grew out of the Space |
| `_data/` | Home-page highlights |
| `_layouts/` | Page templates |
| `assets/` | Stylesheet and original theme graphics |
| `media/` | Original WordPress uploads, referenced as `/media/YYYY/MM/...` |
| `*.md` | Pages: about, collaborations, contact, join, location |

## Local preview

```sh
bundle install
bundle exec jekyll serve
```

## Deploy

Push to `main`; GitHub Pages builds automatically. `CNAME` points the site
at thecreativespace.org.
