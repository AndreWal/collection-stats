# From Beta to Meaning

Practice-oriented articles on interpreting regression models and making defensible analytical decisions.

This repository contains the source for the Quarto book **"From Beta to Meaning: A Guide to Interpreting Regression Analysis"** by André Walter.

## Status

This is a living collection. New articles will be added over time.

The current set of chapters is intentionally selective and **not** an exhaustive map of statistics or regression topics.

## What you will find

- Concept-first explanations focused on interpretation and research decisions
- Worked examples with simulated data
- R code snippets that illustrate ideas
- A rendered website output in `docs/`

## Repository structure

- `_quarto.yml`: Book configuration and chapter order
- `index.qmd`: Landing page and framing of the collection
- `chapters/`: Article source files (`.qmd`)
- `styles.css`: Custom styling
- `docs/`: Rendered site output

## Build and preview locally

Prerequisite: [Quarto](https://quarto.org/docs/get-started/) installed.

```bash
quarto preview
```

Render the full site:

```bash
quarto render
```

By configuration, the rendered output is written to `docs/`.

## Notes

- All datasets in the chapters are simulated for learning purposes.
- Code is educational and should be adapted and validated for production use.
