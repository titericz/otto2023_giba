# Factorization Machine, predicts next click.

# Run notebooks in this order:
1)- preprocess_data.ipynb: read competition data and convert to multiple parquet files
2)- fm-seq2seq.ipynb: train a FM model using last 10 items + hour. Write embeddings table to disk.
