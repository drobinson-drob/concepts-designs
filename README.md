# Concepts Designs

This repository contains standalone HTML concept explorations and design prototypes.

## Primary Experience

- `index.html`
  - Root entrypoint for static hosting.
  - Redirects to the main Spotnana concept deck and provides fallback links.

- `vercel.json`
  - Explicit static routing for Vercel deployment.
  - Maps `/` to `index.html` and lets filesystem routes handle the rest.

- `spotnana_ai_travel.html`
  - Primary concept deck for AI-native travel.
  - Uses the Spotnana logo in the header.
  - Includes embedded `Roadmap` and `Gallery` tabs plus an in-page lightbox.
  - Focuses on UI/UX design outcomes, near-term design opportunities, and future interface concepts.

## Supporting Files

- `concepts_gallery.html`
  - Standalone gallery source file for weekly concept snapshots.

- `voice_ui_concept.html`
  - Focused voice interaction concept prototype.

- `assets/spotnana-primary.svg`
  - Local Spotnana logo asset used in the main header.

- `Sharing Design/April/Week 1/`
  - Local image assets used by the embedded gallery and standalone gallery page.

## Recommended Starting Point

Open `spotnana_ai_travel.html` first for the main narrative and merged gallery experience.
