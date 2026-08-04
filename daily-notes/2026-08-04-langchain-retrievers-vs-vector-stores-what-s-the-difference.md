---
date: 2026-08-04
topic: "LangChain: Retrievers vs Vector stores - what's the difference"
---

# LangChain: Retrievers vs. Vector Stores

In LangChain, **Vector Stores** and **Retrievers** are often used together, but they serve distinct architectural roles. A Vector Store is a physical or logical database abstraction that stores document chunks alongside their high-dimensional vector embeddings, optimized for similarity calculations. In contrast, a Retriever is a lightweight, read-only functional interface that accepts a query string as