---
description: "Workspace instructions for Ensemble-Bagging-model, a small data science repo centered on a Jupyter notebook exploring transformer-based text embeddings and model training."
---

# Workspace Instructions

This repository currently contains:

- `Transformer_model_pre_train.ipynb`: the main working notebook, including data loading, embedding model usage, and model training experiments.
- `README.md`: a simple example dataset sample schema and reference data.

## What to focus on

- Improve or extend the notebook workflow.
- Keep changes compatible with a Jupyter notebook environment.
- Prefer clear comments, reproducible data processing, and safe model/training steps.
- Avoid adding unrelated project scaffolding unless the user explicitly asks for it.

## Project context

- The notebook imports `pandas`, `numpy`, `matplotlib`, `seaborn`, `torch`, `transformers`, `sentence_transformers`, and `sklearn`.
- The repo does not currently include a Python package manifest (`requirements.txt`, `pyproject.toml`, or `environment.yml`).
- There is no existing automated build or test setup.

## Useful guidance for assistant tasks

- When asked to edit code, prefer updating the notebook cells in place and explain the notebook reasoning clearly.
- When asked to add setup instructions, note that the environment appears to be a Python/Jupyter data science workspace and recommend installing required packages with `pip` or `conda`.
- If the user asks for extra files, keep them minimal and relevant to the notebook workflow.
- If the user asks for new scripts or structure, first confirm whether they want a script-based project rather than a notebook-centered repo.
