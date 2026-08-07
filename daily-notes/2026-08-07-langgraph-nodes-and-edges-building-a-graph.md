---
date: 2026-08-07
topic: "LangGraph: Nodes and edges - building a graph"
---

# LangGraph: Nodes and Edges — Building a Graph

LangGraph is a library designed to build stateful, multi-actor applications with LLMs by modeling agent workflows as graphs. At its core, a graph consists of **nodes** and **edges**. Nodes represent isolated units of computation—such as calling an LLM, executing a database query, or running a local tool. Edges define the control flow and