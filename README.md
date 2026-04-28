# Ensemble-Bagging-model

A small data science repository centered on a Jupyter notebook exploring transformer-based text embeddings and model training.

## Contents

- `Transformer_model_pre_train.ipynb` — main notebook demonstrating data loading, embedding generation with `sentence-transformers`, and basic model workflows.
- `requirements.txt` — Python package dependencies used by the notebook.

## Setup

1. Create a Python environment, for example:

   ```bash
   python -m venv .venv
   source .venv/bin/activate
   ```

2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Start Jupyter and open the notebook:

   ```bash
   jupyter notebook
   ```

## Notes

- The notebook uses `sentence-transformers` for embedding generation and `transformers` for model support.
- If the dataset file referenced in the notebook is not available in the repo, update the notebook path or provide the expected CSV file locally.

## Dataset source

- The notebook currently expects a review dataset file named `movie_reviews.csv` in the working directory.
- If you are using a different dataset, update the path inside `Transformer_model_pre_train.ipynb` accordingly.

## Recommended next step

Open `Transformer_model_pre_train.ipynb` and run the cells sequentially to reproduce the notebook workflow.
