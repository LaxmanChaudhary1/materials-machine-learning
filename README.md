# Machine Learning for Materials Science

Research and development repository for applying classical machine-learning and neural-network methods to materials-property prediction.

## What is here

- `code/` — Python scripts for model training, tuning, analysis, and plotting.
- `data/` — datasets used by the workflows.
- `image/` — generated figures and visualizations.
- `xbgm.slurm` and related files — HPC job scripts retained from the original workflow.

Representative methods in `code/` include artificial neural networks, LightGBM, stochastic-gradient methods, random forests, and XGBoost-based workflows, together with preprocessing and error-analysis utilities.

## Purpose

This repository documents an earlier materials-informatics workflow and serves as a research archive. It is not intended to be a polished Python package. The emphasis is on preserving the computational workflow while making the repository easier to understand and navigate.

## Suggested navigation

1. Start in `code/` to identify the model or analysis workflow of interest.
2. Check `data/` for the corresponding input datasets.
3. Use files in `image/` to inspect generated results and diagnostics.
4. Treat HPC submission scripts as environment-specific examples rather than portable defaults.

## Repository hygiene

Generated Python cache files and Jupyter checkpoints should not be committed. A `.gitignore` is included to prevent these artifacts from being added in future work.

## Author

**Laxman Chaudhary**  
Computational materials physics, machine learning for materials, and scientific computing.
