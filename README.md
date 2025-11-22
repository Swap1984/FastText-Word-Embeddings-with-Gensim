# FastText-Word-Embeddings-with-Gensim

A hands-on project demonstrating FastText word embeddings using Gensim. Includes training custom embeddings, comparing with Word2Vec &amp; GloVe, visualizing vector spaces, and evaluating semantic similarity. Ideal for learning modern NLP embedding workflows end-to-end.  (298 characters)

This project demonstrates how to train, evaluate, and visualize FastText word embeddings using Gensim, and compares them with Word2Vec and GloVe embeddings. The goal is to build a strong conceptual understanding of how modern word vectors capture semantic relationships.

🧠 Key Learnings

FastText uses subword units, so it understands unseen / misspelled / rare words.

Word2Vec learns embeddings based on local context but cannot handle OOV.

GloVe captures global co-occurrence statistics.

Embeddings can be compared using cosine similarity, analogies, and clustering.

Visualization techniques (TSNE/PCA) reveal semantic grouping patterns.

Comparing with other Embedding methods

| Model        | Training Speed    | Handles OOV Words | Subword Info | Vector Quality | Best Use-case                          |
| ------------ | ----------------- | ----------------- | ------------ | -------------- | -------------------------------------- |
| **FastText** | Medium            | ✔ Yes             | ✔ Yes        | High           | Noisy text, morphology-heavy languages |
| **Word2Vec** | Fast              | ✖ No              | ✖ No         | Medium-High    | Large clean corpora                    |
| **GloVe**    | Slow (Pretrained) | ✖ No              | ✖ No         | High           | Global semantic meaning                |
