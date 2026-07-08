# Itô Calculus Foundations

Expository paper and numerical simulations exploring the measure-theoretic
foundations of Itô's lemma. Outlines the proof of general Itô isometry for L2 integrable functions and
Itô's Lemma.

<!--, with
Python visualizations of quadratic variation, random fields, and Fokker-Planck diffusion. -->

## Paper

The full paper is available in [`paper/main.pdf`](paper/main.pdf). GitHub
truncates PDFs longer than 5 pages so "see more" will have to be repeatedly
clicked to view the full document in the GitHub interface.

The LaTeX source is in [`paper/main.tex`](paper/main.tex).

To compile:
```bash
cd paper
latexmk -pdf main.tex
```
<!--
## Structure

- `paper/` — LaTeX source and compiled PDF
 - `simulations/` — Python scripts for quadratic variation, random fields, and Fokker-Planck visualizations -->

<!--
## Dependencies

**Paper:** TeX Live or MiKTeX

**Simulations:** To be added.

## Usage

To be added once simulations are written.
-->
