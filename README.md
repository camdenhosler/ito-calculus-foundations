# Itô's Lemma

Expository paper and numerical simulations exploring the measure-theoretic
foundations of Itô's lemma. Outlines the proof of general Itô isometry and
Itô's Lemma for L2 integrable functions of standard Brownian motion, with
Python visualizations of quadratic variation, random fields, and Fokker-Planck diffusion.

## Paper

The full paper is available in [`paper/main.pdf`](paper/main.pdf). GitHub
truncates PDFs longer than 5 pages so "see more" will have to be repeatedly
clicked to view the full document in the GitHub interface.

The LaTeX source is in [`paper/main.tex`](paper/main.tex).

To recompile:
```bash
cd paper
latexmk -pdf main.tex
```

## Structure

- `paper/` — LaTeX source and compiled PDF
- `simulations/` — Python scripts for quadratic variation and GBM visualizations

## Dependencies

**Paper:** TeX Live or MiKTeX (full install recommended).

**Simulations:** To be added.

## Usage

To be added once simulations are written.
