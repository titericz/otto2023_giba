Factorization Machine, predicts next click.

run notebooks in this order:
- preprocess_data.ipynb - read competition data and convert to multiple parquet files
- fm-seq2seq.ipynb - train a FM model using last 10 items + hour. Write embeddings table to disk.
