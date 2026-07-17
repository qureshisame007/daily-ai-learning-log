---
date: 2026-07-17
topic: "Prompt engineering: Few-shot vs zero-shot prompting"
---

# Prompt Engineering: Zero-Shot vs. Few-Shot Prompting

Zero-shot and few-shot prompting are foundational techniques used to guide Large Language Models (LLMs) toward desired outputs. **Zero-shot prompting** feeds an instruction directly to the model without any examples, relying entirely on the model's pre-trained internal representations to understand and execute the task. In contrast, **few-shot prompting** provides a small set of input-output exemplars (typically 1 to 5) within the prompt context, demonstrating the exact format, style, or reasoning pattern expected before asking the model to process a new instance.

## Why it matters

For developers building GenAI applications and autonomous agents, choosing between zero-shot and few-shot prompting is a critical trade-off between latency, cost, and reliability. Agentic workflows require predictable structured outputs (such as JSON schemas) and consistent tool-calling behaviors. 

While zero-shot prompting is computationally cheaper and faster (saving input tokens), it often fails under complex logical constraints or