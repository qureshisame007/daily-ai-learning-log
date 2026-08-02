---
date: 2026-08-02
topic: "LangChain: Memory types - Buffer vs Summary vs Vector memory"
---

# LangChain Memory: Buffer vs. Summary vs. Vector

In LLM application development, managing conversational state is critical because LLMs are inherently stateless. LangChain solves this through various *Memory* utilities. The three primary architectures for handling chat history are **Buffer Memory** (retaining exact, raw recent exchanges), **Summary Memory** (using an LLM to continuously compress historical context), and **Vector Memory** (storing past interactions in a vector database to retrieve semantically relevant snippets on demand). Choosing the right memory type balances token efficiency, latency, and context window constraints.

## Why it matters

For autonomous AI agents, memory is the backbone of planning, persona consistency, and tool execution:

*   **Context Window Management:**