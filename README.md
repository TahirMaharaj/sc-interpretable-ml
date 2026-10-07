# Interpretable ML on single-cell RNA-seq (early stage)

Early-stage self-project exploring interpretable machine learning for
single-cell data. This project was developed with AI assistance (Claude) 
as a learning exercise. I ran and adapted the code and worked through
each step to understand it.

## What is done
- Loaded the public PBMC 3k single-cell dataset (scanpy)
- Trained a logistic regression classifier to predict cell type
- Test accuracy: [93%]
- Inspected the top-weighted genes per cell type, e.g. [B cells: CD79A, MS4A1, CD79B, HLA-DQB1, HLA-DQA1
CD14+ Monocytes: S100A8, LGALS2, MS4A6A, GPX1, FCN1]

## Next steps
- Build a model constrained by gene sets (pathway-informed)
- Compare with a baseline neural network

## How to run
Open pbmc_classifier.ipynb in Google Colab and run all cells.
Requires: scanpy, scikit-learn.
