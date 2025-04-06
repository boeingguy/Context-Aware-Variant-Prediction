# TP53 Context-Aware Variant Prediction
This project explores context-aware modeling of protein variants by integrating protein language models (pLMs) with gene expression and spatial transcriptomic data. TP53 is used as the primary case study.

## Project Structure

- `data/`: Raw and processed datasets
- `scripts/`: Reproducible scripts (downloading, preprocessing, etc.)
- `src/`: Model code, utilities, and training pipelines
- `notebooks/`: Jupyter notebooks for prototyping and EDA
- `results/`: Outputs (figures, tables)
- `references/`: Papers, notes, exported Zotero files

## Goals

- Build a dual-encoder ML model to predict variant effects in a tissue-aware manner
- Use TP53 deep mutational scan data from MaveDB as a benchmark
- Incorporate cell-type expression from Tabula Sapiens

## Status

🚧 Work in progress — setup and early data engineering underway