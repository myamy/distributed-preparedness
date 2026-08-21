# Distributed Preparedness

Living companion on preparedness infrastructure, offline connectivity, open hardware, and distributed manufacturing: framework, case studies, extended literature review, and recommendations.

This is the open, continuously updated companion to a paper submitted to the **Journal of Open Hardware (JoOH)**. The journal article carries the peer-reviewed core; this site carries everything that doesn't fit inside its word limit, and keeps growing afterward.

**Live site:** `https://<your-username-or-org>.github.io/distributed-preparedness/` (active once GitHub Pages is enabled — see below).

## Repository structure

```
_quarto.yml           site configuration (navigation, theme, bibliography)
index.qmd             home page
framework.qmd         the framework (placeholder)
literature-review.qmd extended literature review (placeholder)
recommendations.qmd   audience-specific recommendations (placeholder)
about.qmd             authors, funding, license, citation info
case-studies/          one subfolder per case study (see CONTRIBUTING.md)
position-papers/       one subfolder per position paper (see CONTRIBUTING.md)
references.bib         shared bibliography (sync target for the Zotero group library)
styles.scss            minor theme overrides
.github/workflows/      GitHub Actions workflow that builds and publishes the site
```

## Adding content

See [CONTRIBUTING.md](CONTRIBUTING.md) — written for adding content entirely through the GitHub web interface, no local setup required.

## How publishing works

Every push to `main` triggers a GitHub Actions workflow that renders the site with Quarto and publishes it to GitHub Pages automatically. Nothing needs to be built locally.

## License

To be decided — see [about.qmd](about.qmd).
