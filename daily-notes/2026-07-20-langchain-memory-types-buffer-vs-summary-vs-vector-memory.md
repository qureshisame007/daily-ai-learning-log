---
date: 2026-07-20
topic: "LangChain: Memory types - Buffer vs Summary vs Vector memory"
---

# LangChain Memory: Buffer vs. Summary vs. Vector

In LangChain, memory components enable Large Language Models (LLMs) to maintain state across conversational turns. Because LLMs are natively stateless, developers must pass prior context back to the model with each new prompt. LangChain offers three primary paradigms to manage this context window efficiently: **Buffer Memory** (appending raw chat history), **Summary Memory** (condensing past interactions using an LLM), and **Vector Memory** (storing and retrieving historical turns via semantic search