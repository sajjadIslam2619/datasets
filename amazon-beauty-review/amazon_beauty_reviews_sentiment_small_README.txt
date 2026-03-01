Amazon Beauty Reviews - Sentiment (Small Sample)
================================================

A small, proportionally balanced subset of the Amazon Beauty Reviews dataset,
with review text and 3-class sentiment labels (negative, neutral, positive).

Original dataset
----------------
Source: Hugging Face Datasets
https://huggingface.co/datasets/jhan21/amazon-beauty-reviews-dataset

File used: amazon_beauty_reviews_dataset.csv (via hf://datasets/jhan21/amazon-beauty-reviews-dataset/amazon_beauty_reviews_dataset.csv)

Preprocessing
-------------
- Sentiment mapping from 1–5 star ratings:
  - 1–2 stars  -> negative
  - 3 stars    -> neutral
  - 4–5 stars  -> positive
- Subset size: 10,000 positive reviews, with negative and neutral sampled in the same proportion as in the full dataset (~2,901 negative, ~1,126 neutral).
- Rows shuffled; random_state=42 for reproducibility.

Files
-----
- amazon_beauty_reviews_sentiment_small.csv: text, rating (sentiment label)

Columns
-------
- text:   Review text
- rating: Sentiment label — "negative", "neutral", or "positive"

License / attribution
---------------------
Respect the license and terms of the original dataset (jhan21/amazon-beauty-reviews-dataset) when using or redistributing this derived data.
