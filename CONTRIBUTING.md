# Contributing (browser-only workflow)

Everything here can be done through github.com — no git or terminal required.

## Adding a case study

1. Go to the repository on github.com.
2. Click **Add file → Create new file**.
3. In the "Name your file" box, type a path like:
   `case-studies/2024-nepal-earthquake-response/index.qmd`
   (GitHub creates the folder automatically from the path. Use a short, dated, descriptive slug — lowercase, hyphens, no spaces.)
4. Paste this template into the file and fill it in:

   ```markdown
   ---
   title: "Your case study title"
   author: "Your name"
   date: "2026-08-21"
   description: "One-sentence summary shown in the case studies listing."
   tags: [makerspaces, connectivity, disaster-response]
   ---

   ## Context

   ## What happened

   ## What it shows for preparedness infrastructure

   ## Sources
   ```
5. Scroll down to "Commit changes." You can commit directly to `main`, or select "Create a new branch and start a pull request" if you'd like someone to review it first.
6. The site rebuilds automatically within a few minutes and your entry appears on the [Case Studies](case-studies/index.qmd) listing page, newest first.

## Adding a position paper

Same steps, under `position-papers/` instead of `case-studies/`, e.g.:
`position-papers/nathan-federated-hardware-repositories/index.qmd`

## Adding a reference

Add a standard BibTeX entry to `references.bib` (edit the file directly on github.com — click the pencil icon), then cite it anywhere with `[@citekey]`. If the Zotero group library has Better BibTeX auto-export configured, this file can instead be kept in sync automatically — ask Vicy if you're not sure whether that's set up yet.

## Editing an existing page

Open the file on github.com and click the pencil (edit) icon top right, make your change, and commit.

## Questions

If something doesn't render as expected, check the "Actions" tab on the repository for the build log, or ask Vicy.
