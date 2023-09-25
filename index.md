---
title: "NNA Community Office on Open Source Webinar: Panelist slides"
listing:
  type: "table"
  contents:
    - "slides/*.md"
    - "slides/*.qmd"
  fields:
    - "title"
  sort: ["index", "title"]
  sort-ui: false
  filter-ui: false
format:
  html: default
  revealjs:
    # Hack: the `_metadata.yml` sets all files in this directory as `revealjs` format.
    # Without having this set, we get a `NotFound` error when using `quarto render`.
    output-file: "slides_duplicate_index.html"
# Disable link to RevealJS format on this index page
format-links: false
---
