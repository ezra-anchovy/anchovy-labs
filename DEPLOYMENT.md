# Anchovy Labs Website — Source of Truth

## Canonical live site repo
The live site for `anchovylabs.ai` is this nested git repo:

`/Users/al/clawd/projects/anchovy-labs`

This repo is the deploy source for GitHub Pages (`master` branch, repo root).

## Important
Do **not** assume the monorepo root homepage or other Anchovy-named folders are the deployed site.
The deployable source of truth is this nested repo.

## Safe update procedure
1. Edit files in this repo only.
2. Check `git status` here, not in the parent repo.
3. Commit in this repo.
4. Push `master` in this repo.
5. Verify both:
   - `https://anchovylabs.ai`
   - any newly added subpages

## Current primary pages
- `index.html`
- `science-and-ai.html`
- `press.html`
- `privacy.html`
- `terms.html`
- `sitemap.xml`
