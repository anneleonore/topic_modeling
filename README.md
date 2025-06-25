## Topic Modeling

This repository contains a collection of topic modeling scripts using both classical and modern approaches:

- **Latent Dirichlet Allocation (LDA)**: A probabilistic model for discovering latent topics in text corpora.
- **BERTopic**: An embedding-based approach that combines transformer embeddings with class-based TF-IDF for interpretable topic modeling.

### Files and Structure

- `LDA.py` – Implements LDA topic modeling using `gensim`.
- `BERTopic.py` – Applies BERTopic using `bertopic`.
- `contextualized_topic_models.py` - Contextualized Topic Models (CTM) using the `contextualized-topic-models` library, combining BERT embeddings with traditional topic modeling techniques.

### Requirements

See `requirements.txt` for package dependencies.
