# Contributing (browser-only workflow)

Everything here can be done through github.com — no git or terminal required.

## The three content sections

| Section | Folder | What belongs there |
| --- | --- | --- |
| Literature Reviews | `literature-reviews/` | Full reviews of a field or topic, with citations |
| Case Studies | `case-studies/` | Documented examples of what happened somewhere specific |
| Position Papers | `position-papers/` | Standalone argued contributions, kept in the author's voice |

All three work identically: one folder per contribution, containing an `index.qmd`.

## Adding a literature review

1. Go to the repository on github.com.
2. Click **Add file → Create new file**.
3. In the "Name your file" box, type a path like:
   `literature-reviews/offline-connectivity/index.qmd`
   (GitHub creates the folder automatically from the path. Use a short, descriptive slug — lowercase, hyphens, no spaces.)
4. Paste this template into the file and fill it in:

```markdown
   ---
   title: "Your review title"
   author: "Your name"
   date: "2026-08-21"
   description: "One-sentence summary shown in the listing."
   ---

   Your text. Cite sources with [@citekey] — see "Citing sources" below.
```
5. Scroll down to "Commit changes." You can commit directly to `main`, or select "Create a new branch and start a pull request" if you'd like someone to review it first.
6. The site rebuilds automatically within a few minutes and your entry appears on the Literature Reviews listing page, newest first.

## Adding a case study

Same steps, under `case-studies/`, e.g. `case-studies/nepal-earthquake-response/index.qmd`. Suggested structure:

```markdown
---
title: "Your case study title"
author: "Your name"
date: "2026-08-21"
description: "One-sentence summary shown in the listing."
tags: [makerspaces, connectivity, disaster-response]
---

## Context

## What happened

## What it shows for preparedness infrastructure

## Sources
```

## Adding a position paper

Same steps, under `position-papers/`, e.g. `position-papers/federated-hardware-repositories/index.qmd`.

## Citing sources

The bibliography is generated automatically from the shared Zotero group library ([Distributed Disaster Response](https://www.zotero.org/groups/6184418/distributed_disaster_response/library)). A scheduled job pulls it into `references.bib` once a day, so:

- **Add your source to Zotero**, not to `references.bib` — anything written into that file by hand is overwritten on the next sync.
- **Cite it in your text** as `[@citekey]`, using the citation key Zotero shows for the item.
- If you have just added something to Zotero and need it on the site immediately, ask Vicy to trigger the sync manually (Actions tab → "Publish site" → Run workflow), or wait for the next daily run.

## Writing tips

- Leave a **blank line** before and after every heading, paragraph, and list — without it, Markdown runs things together and lists do not render as lists.
- `*text*` is italic, `**text**` is bold.
- Mark a phrase in the project's red with `[your phrase]{.hl}` — use it sparingly.

## Editing an existing page

Open the file on github.com and click the pencil (edit) icon top right, make your change, and commit.

## Questions

If something doesn't render as expected, check the "Actions" tab on the repository for the build log, or ask Vicy.
