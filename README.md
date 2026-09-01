# Project PARC — Community Project Digital Summaries

Public digital one-pagers for all 15 Project PARC community projects (water access, food security, livelihoods and energy). Each page is linked from a QR code placed on-site and in the project's Excel record.

Live site: `https://projectparc.github.io/parc-community-projects/`

## Structure

Everything lives in the repository root (kept flat on purpose, so uploads and edits stay simple):

```
index.html        Landing page — card grid linking to every project
<slug>.html        One digital summary page per project (e.g. esiteti.html)
<slug>.jpg          Hero photo for each project (e.g. esiteti.jpg)
```

## Updating a project page

1. Edit the project's HTML file directly (e.g. `apiary.html`), or regenerate it from source data.
2. Commit and push to the `main` branch — GitHub Pages redeploys automatically within a minute or two.

## Adding a new project

1. Add a new hero photo to the repo root (JPEG, ~1400px wide), named `<slug>.jpg`.
2. Add a new page `<slug>.html` following the same structure as the existing ones.
3. Add a card for it to `index.html`.
4. Generate a QR code pointing to `https://projectparc.github.io/parc-community-projects/<slug>.html` and add it to the project's Excel sheet.
