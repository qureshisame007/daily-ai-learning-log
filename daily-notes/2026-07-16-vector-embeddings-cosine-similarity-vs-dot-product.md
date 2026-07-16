---
date: 2026-07-16
topic: "Vector embeddings: Cosine similarity vs dot product"
---

# Vector Embeddings: Cosine Similarity vs. Dot Product

When working with vector embeddings, measuring semantic similarity is fundamental to locating relevant information. Cosine similarity and dot product are the two primary mathematical metrics used to determine how close two vectors reside in a high-dimensional space. While dot product calculates the product of the vectors' magnitudes multiplied by the cosine of the angle between them, cosine similarity normalizes the vectors first, focusing exclusively on the angle and ignoring differences in magnitude.

## Why it matters

In Agentic AI and Retrieval-Augmented Generation (RAG) architectures, selecting the correct similarity metric directly impacts both retrieval accuracy and system latency:

*   **Semantic Consistency:**