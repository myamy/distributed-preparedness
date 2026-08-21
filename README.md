# Distributed Preparedness

Living companion on preparedness infrastructure, offline connectivity, open hardware, and distributed manufacturing: framework, case studies, extended literature review, and recommendations.

This is the primary, continuously growing knowledge base for the project — not a companion to a single paper. The first publication drawn from it is a peer-reviewed paper submitted to the **Journal of Open Hardware (JoOH)**, distilling the framework into 6,000 words; further publications are expected to follow, each drawing on a different slice of this resource.

**Live site:** `https://myamy.github.io/distributed-preparedness/`

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
