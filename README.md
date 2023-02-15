# otto2023_giba

## OTTO – Multi-Objective Recommender System

## Factorization Machine, predicts next click.

This repo is part of team G.B.D.T. solution.

## Run notebooks in this order:

1) `preprocess_data.ipynb`: read competition data and convert to multiple parquet files

2) `fm-seq2seq.ipynb`: train a FM model using last 10 items + hour. Write embeddings table to disk.
