# otto2023_giba

## OTTO – Multi-Objective Recommender System

## Factorization Machine, predicts next click.

This repo is part of team G.B.D.T. #3 place solution. `https://www.kaggle.com/competitions/otto-recommender-system/leaderboard`

## Run notebooks in this order:

1) `preprocess_data.ipynb`: read competition data and convert to multiple parquet files

2) `fm-seq2seq.ipynb`: train a FM model using last 10 items + hour. Write embeddings table to disk.


```
├── preprocess_data.ipynb        # preprocess data
├── fm-seq2seq.ipynb             # train FM model and extract embeddings
└── README.md
```
