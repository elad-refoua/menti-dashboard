# MENTI Project Dashboard

Live status dashboard for the MENTI Project: Developing AI Tools for Enhancing Mentalization Skills (Bar-Ilan University, IRB 290125444, Grant #0008682).

**Live URL:** https://elad-refoua.github.io/menti-dashboard/

## What this is

A single-page, static HTML dashboard that tracks:

- All 13 MENTI articles (status, authors, journal, data, next steps)
- Live Qualtrics response counts (AI_PSYCH account)
- Key project metrics and totals
- Studies needing attention and upcoming timeline

The dashboard contains no participant data — only aggregated counts, article titles, author names, and project metadata. Safe to be public.

## Source of truth

The canonical file lives in the MENTI project Dropbox folder:

```
~/Dropbox/ARLAB shared folder/PhD students/EladR/menti/menti_dashboard.html
```

This repo is a mirror for GitHub Pages deployment. To update:

1. Edit `menti_dashboard.html` in the Dropbox folder (or ask the `menti-agent` to refresh it).
2. Copy it over `index.html` in this repo.
3. Commit and push — Pages auto-deploys.

## Regeneration

The `menti-agent` is the authoritative source for project state. When the agent updates its memory (article statuses, Qualtrics counts, new decisions), the dashboard should be regenerated from memory and re-deployed here.

## Maintained by

Elad Refoua · [refoua.elad@gmail.com](mailto:refoua.elad@gmail.com) · Bar-Ilan University
