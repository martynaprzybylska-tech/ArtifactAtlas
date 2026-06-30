# ArtifactAtlas

ArtifactAtlas is a comprehensive, multi-source dataset and visual reference for histopathology artifacts in H&E staining. ArtifactAtlas showcases examples of the most common 11 types of artifacts from 5 critical workflow stages - from grossing to digital scanning. Use our browser to explore 330 examples of the characteristic morphology, etiology, and diagnostic impact of physical disruptions, contaminants, and digital errors.

## Overview

This repository contains a static web interface and image gallery documenting common artifacts encountered during microscopic slide preparation and whole-slide imaging. The site groups artifacts by workflow stage and provides descriptive explanations alongside curated example images.

## What is included

- `docs/index.html` — landing page with a responsive artifact directory and feature slideshow
- `docs/artifact.html` — artifact detail page that loads category-specific content via URL query parameters
- `docs/gallery/` — organized artifact galleries for each category
- `docs/icons/` — visual icons for artifact categories and for browser interface

## Artifact categories

The library covers the following histopathological artifacts:

- Ink
- Knife marks
- Tears
- Folds
- Precipitates
- Dust
- Marker
- Scratch
- Stitching
- Blurring
- Air Bubbles

## Usage

1. Open `docs/index.html` in a browser to explore the ArtifactAtlas interface.
2. Select any artifact category to open `docs/artifact.html?type=<artifact>` for detailed descriptions and examples.

## Publication-ready notes

- The `docs/` directory is ready for static site deployment, including GitHub Pages.
- The interface is organized for clear presentation of artifact categories, descriptions, and supporting images.
- Update any hard-coded local paths in the utility scripts before use.

## Contact

For project inquiries, update requests, or image curation notes, please edit this repository or open an issue.

