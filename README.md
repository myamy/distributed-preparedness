# Distributed Preparedness

An open knowledge base on preparedness infrastructure, offline connectivity, open hardware, and distributed manufacturing: framework, recommendations, literature reviews, case studies, and position papers.

**Live site:** `https://myamy.github.io/distributed-preparedness/`


## Repository structure

```
_quarto.yml            site configuration (navigation, theme, bibliography)
index.qmd              home page
framework.qmd          the framework (placeholder)
recommendations.qmd    audience-specific recommendations (placeholder)
about.qmd              contributors, funding, license, citation info
literature-reviews/    one subfolder per review (see CONTRIBUTING.md)
case-studies/          one subfolder per case study (see CONTRIBUTING.md)
position-papers/       one subfolder per position paper (see CONTRIBUTING.md)
references.bib         bibliography — auto-generated daily from the Zotero group library, do not edit by hand
styles.scss            theme (palette, typography, layout)
.github/workflows/     GitHub Actions workflow: syncs the bibliography, builds and publishes the site
```

## Adding content

See [CONTRIBUTING.md](CONTRIBUTING.md) — written for adding content entirely through the GitHub web interface, no local setup required.

## How publishing works

Every push to `main` triggers a GitHub Actions workflow that renders the site with Quarto and publishes it to GitHub Pages automatically. Nothing needs to be built locally.

## License

To be decided — see [about.qmd](about.qmd).
