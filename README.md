# Mercer County Park Trails — GIS Pilot

This repository contains an editable Quarto/Reveal.js presentation for discussing a proposed trail-data collection and public-route methodology with Mercer County Parks.

## Purpose

The presentation uses a small Mercer County Park case study to show:

- how existing trail geometry can support a cleaner public-facing route structure;
- why GIS can infer some route relationships but cannot reliably reconstruct every trail without Parks input and field verification;
- how junction points and Trimble/Field Maps collection could improve the underlying network;
- why detailed internal trail segments and simplified public routes should be treated as related but separate concepts;
- why official route naming should remain a Parks decision.

The case-study route name **Proposed Loop A** is intentionally temporary and is not intended as an official trail name.

## Open in RStudio / Posit

Requirements:

1. Install Quarto: https://quarto.org/
2. Clone this repository.
3. Open the folder in RStudio.
4. Open `index.qmd`.
5. Click **Render** or run:

```bash
quarto preview
```

The presentation will open in a browser.

## Editing

Most content is in:

- `index.qmd` — slide text and layout
- `styles.css` — visual styling
- `_quarto.yml` — presentation settings

Because the presentation is HTML/Reveal.js, all text and layout remain directly editable.

## Suggested next addition

Add two screenshots from ArcGIS Pro to the case-study section:

1. **Before** — existing Red Trail geometry.
2. **After** — Proposed Loop A highlighted over the existing network.

A third screenshot showing the junction points would make the methodology especially clear.
