# PBMC3k single-cell RNA-seq analysis with Scanpy

A step-by-step and reproducible analysis of the 10x Genomics PBMC3k dataset using Python and Scanpy.

## Project status

**Work in progress**

The repository structure and computational environment have been configured successfully. The biological analysis is currently being developed.

## Objective

This project reconstructs the PBMC3k single-cell RNA-seq workflow as a transition from visual analysis in Galaxy to a fully code-based workflow in Python.

The analysis will cover:

- Data loading and inspection
- Quality control
- Cell and gene filtering
- Normalisation and log transformation
- Highly variable gene selection
- Principal component analysis
- Neighbourhood graph construction
- Leiden clustering
- UMAP visualisation
- Marker-gene identification
- Cell-type annotation
- Exploration of parameter sensitivity

## Repository structure

```text
pbmc3k-scanpy-workflow/
├── data/
│   ├── raw/
│   └── processed/
├── docs/
├── figures/
├── notebooks/
│   └── 00_environment_check.ipynb
├── results/
├── src/
├── environment.yml
├── LICENSE
└── README.md

