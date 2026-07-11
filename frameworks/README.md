# Frameworks — Agent Frameworks & Orchestration

Agent and multi-agent frameworks: orchestration, coordination, role-based systems. Curated tools and research.

## Tools & Libraries
<!-- add: agent/orchestration frameworks — LangGraph, CrewAI, AutoGen, OpenAI Agents SDK, Claude Agent SDK, smolagents, ... -->
- **[LangChain](https://github.com/langchain-ai/langchain)** — agent engineering platform; the de-facto entry point for LLM agent tooling. `tool-calling`
- **[LangGraph](https://github.com/langchain-ai/langgraph)** — low-level orchestration framework for building stateful, resilient agents as graphs. `multi-agent`
- **[AutoGen](https://github.com/microsoft/autogen)** — Microsoft's multi-agent framework, now in maintenance mode; succeeded by Microsoft Agent Framework. `multi-agent`
- **[CrewAI](https://github.com/crewAIInc/crewAI)** — framework for orchestrating role-playing autonomous agents that collaborate on shared tasks. `multi-agent`
- **[OpenAI Agents SDK](https://github.com/openai/openai-agents-python)** — provider-agnostic multi-agent framework with handoffs, guardrails, sessions, and built-in tracing. `multi-agent` `tool-calling`
- **[smolagents](https://github.com/huggingface/smolagents)** — barebones library for agents that think in code. `code-agents`
- **[Claude Agent SDK (Python)](https://github.com/anthropics/claude-agent-sdk-python)** — official Python SDK for building agents on the harness that powers Claude Code. `claude` `mcp`
- **[Deep Agents](https://github.com/langchain-ai/deepagents)** — opinionated, batteries-included agent harness on LangGraph that runs out of the box. `multi-agent`

## Protocols & Standards
<!-- framework-level interop conventions, agent definition formats, ... -->
- **[AGENTS.md](https://github.com/agentsmd/agents.md)** — open Markdown convention for giving coding agents project-specific instructions. `code-agents`
- **[Agent Protocol](https://github.com/langchain-ai/agent-protocol)** — framework-agnostic APIs for serving agents in production: runs, threads, store. `interop`
- **[OASF](https://github.com/agntcy/oasf)** — standardized schema system for defining agent capabilities, interactions, and metadata. `interop`

## Benchmarks & Leaderboards
<!-- framework comparisons, orchestration benchmarks, ... -->

## Papers & Research
<!-- key papers -->
- **[Why Do Multi-Agent LLM Systems Fail?](https://arxiv.org/abs/2503.13657)** — MAST failure taxonomy: 14 failure modes from 1,600+ traces across 7 multi-agent frameworks. `multi-agent`
- **[Generative Agents](https://arxiv.org/abs/2304.03442)** — interactive simulacra: 25 agents with memory, reflection, and planning in a simulated town. `multi-agent` `simulation`
- **[CAMEL](https://arxiv.org/abs/2303.17760)** — role-playing framework where communicative agents cooperate autonomously via inception prompting. `multi-agent`
- **[Reflexion](https://arxiv.org/abs/2303.11366)** — agents that self-improve via verbal self-reflection stored in episodic memory. `self-reflection`
- **[ReAct](https://arxiv.org/abs/2210.03629)** — interleaved reasoning traces and actions; the foundational agent-loop pattern. `reasoning` `tool-calling`

## Learning
<!-- tutorials, explainers -->
- **[Claude Cookbooks](https://github.com/anthropics/claude-cookbooks)** — notebooks and recipes for building with Claude, including agent and tool-use patterns. `claude`
- **[Claude Quickstarts](https://github.com/anthropics/claude-quickstarts)** — starter projects for the Claude API: customer-support agent, computer use, autonomous coding. `claude`

---
[← Agents hub](../README.md)
