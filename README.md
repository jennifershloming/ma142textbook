# MA 142 Geometry QuartoBook

This repository now contains a starter Quarto book for a geometry course.

## Book Structure

- `_quarto.yml` - book configuration, chapter order, and output formats
- `index.qmd` - landing page for the textbook
- `chapters/` - chapter files for core geometry topics
- `references.qmd` and `references.bib` - citation pages and sources
- `styles.css` - small styling customizations

## Render the Book

From the repo root, run:

```bash
quarto render
```

Rendered output is written to `_book/`.

## Live Preview During Edits

```bash
quarto preview
```

This starts a local preview server and automatically reloads as you edit `.qmd` files.

## Publish Options

You can publish to Quarto Pub, GitHub Pages, or another static host after rendering.

If using GitHub Pages, a common approach is publishing the `_book/` output.

## Next Editing Steps

1. Update book title/author in `_quarto.yml`.
2. Replace placeholder examples with your course content.
3. Add figures/diagrams in a `figures/` folder and reference them from chapter files.
4. Add homework sets or checkpoints at the end of each chapter.
