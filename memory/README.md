# Memory — Memory & State

Long-term memory, context management, and state for agents.

## Tools & Libraries
<!-- add: memory frameworks, retrieval layers, context managers, ... -->
- **[LangMem](https://github.com/langchain-ai/langmem)** — long-term memory SDK from LangChain; extracts and consolidates knowledge from agent conversations. `long-term-memory` `langgraph`

## Protocols & Standards
<!-- memory/state interchange formats, ... -->
- **[Agent File (.af)](https://github.com/letta-ai/agent-file)** — open file format for serializing stateful agents with persistent memory across frameworks. `serialization` `long-term-memory`

## Benchmarks & Leaderboards
<!-- long-context / memory benchmarks, ... -->
- **[LoCoMo](https://github.com/snap-research/locomo)** — very-long-term conversational memory benchmark; the de-facto eval for agent memory systems. `long-term-memory` `multi-session`
- **[LongMemEval](https://github.com/xiaowu0162/LongMemEval)** — ICLR 2025 benchmark testing five long-term memory abilities of chat assistants. `long-term-memory` `multi-session`
- **[RULER](https://github.com/NVIDIA/RULER)** — synthetic benchmark measuring the real usable context size of long-context models. `long-context`
- **[Needle In A Haystack](https://github.com/gkamradt/needle-in-a-haystack)** — simple retrieval test measuring recall of planted facts at varying context depths. `long-context`

## Papers & Research
<!-- key papers -->
- **[Mem0](https://arxiv.org/abs/2504.19413)** — scalable memory architecture that extracts, consolidates, and retrieves salient conversation facts (2025). `long-term-memory`
- **[HippoRAG](https://arxiv.org/abs/2405.14831)** — hippocampus-inspired long-term memory combining knowledge graphs with Personalized PageRank retrieval (NeurIPS 2024). `knowledge-graph` `retrieval`
- **[A Survey on the Memory Mechanism of LLM-based Agents](https://arxiv.org/abs/2404.13501)** — systematic survey of memory design, evaluation, and applications in agents (2024). `long-term-memory`
- **[MemGPT](https://arxiv.org/abs/2310.08560)** — virtual context management that pages data between context window and external storage (2023). `long-term-memory` `context-management`
- **[CoALA: Cognitive Architectures for Language Agents](https://arxiv.org/abs/2309.02427)** — framework organizing agents around working, episodic, semantic, and procedural memory (2023). `cognitive-architecture`

## Learning
<!-- tutorials, explainers -->
- **[LLMs as Operating Systems: Agent Memory](https://www.deeplearning.ai/short-courses/llms-as-operating-systems-agent-memory/)** — DeepLearning.AI short course on self-editing, persistent agent memory, taught by MemGPT's authors. `long-term-memory`
- **[Long-Term Agentic Memory with LangGraph](https://www.deeplearning.ai/short-courses/long-term-agentic-memory-with-langgraph/)** — DeepLearning.AI short course building an email agent with semantic, episodic, and procedural memory. `langgraph`
- **[LangChain Docs: Memory](https://docs.langchain.com/oss/python/langgraph/memory)** — conceptual guide to short-term and long-term memory patterns in LangGraph agents. `langgraph`
- **[Agent Memory (Letta blog)](https://www.letta.com/blog/agent-memory/)** — explainer on memory blocks, recall and archival storage, and sleep-time compute. `long-term-memory`

---
[← Agents hub](../README.md)
