# Protocols — Tool Calling & Interop

MCP, A2A, tool/function calling — the standards and integrations that let agents talk to tools and to each other.

## Tools & Libraries
<!-- add: MCP servers & clients, tool libraries, function-calling helpers, ... -->
- **[MCP Servers](https://github.com/modelcontextprotocol/servers)** — official reference server implementations for the Model Context Protocol. `mcp`
- **[MCP Python SDK](https://github.com/modelcontextprotocol/python-sdk)** — official Python SDK for building Model Context Protocol servers and clients. `mcp`
- **[MCP TypeScript SDK](https://github.com/modelcontextprotocol/typescript-sdk)** — official TypeScript SDK for building Model Context Protocol servers and clients. `mcp`
- **[MCP Inspector](https://github.com/modelcontextprotocol/inspector)** — visual testing and debugging tool for MCP server development. `mcp` `debugging`
- **[MCP Registry](https://github.com/modelcontextprotocol/registry)** — community-driven registry service for discovering and publishing MCP servers. `mcp`
- **[langchain-mcp-adapters](https://github.com/langchain-ai/langchain-mcp-adapters)** — adapters connecting LangChain and LangGraph agents to MCP servers and tools. `mcp` `langchain`
- **[MCPB](https://github.com/modelcontextprotocol/mcpb)** — bundle format for one-click local MCP server installation in desktop apps. `mcp` `packaging`

## Protocols & Standards
<!-- add: MCP spec, A2A, tool schemas, ... -->
- **[Model Context Protocol](https://github.com/modelcontextprotocol/modelcontextprotocol)** — specification and documentation for MCP, the open standard connecting agents to tools. `mcp`
- **[MCP Apps](https://github.com/modelcontextprotocol/ext-apps)** — spec and SDK for interactive UIs embedded in chatbots, served by MCP servers. `mcp` `ui`
- **[AG-UI](https://github.com/ag-ui-protocol/ag-ui)** — event-based protocol connecting agents to user-facing applications; complements MCP and A2A. `ui`

## Benchmarks & Leaderboards
<!-- tool-calling / function-calling benchmarks, ... -->
- **[Berkeley Function-Calling Leaderboard](https://gorilla.cs.berkeley.edu/leaderboard.html)** — de-facto leaderboard scoring LLMs on function-calling accuracy, from single calls to multi-turn agentic tasks. `tool-calling`
- **[τ²-bench](https://github.com/sierra-research/tau2-bench)** — Sierra's benchmark for tool-agent-user interaction, extending τ-bench with dual-control conversations. `tool-calling` `multi-turn`
- **[ToolBench](https://github.com/OpenBMB/ToolBench)** — tool-learning platform and benchmark over 16,000+ real-world APIs, from the ToolLLM paper. `tool-calling`
- **[MCP-Universe](https://github.com/SalesforceAIResearch/MCP-Universe)** — Salesforce benchmark and RL framework grounding agents in real-world MCP servers. `mcp` `tool-calling`

## Papers & Research
<!-- key papers -->
- **[Model Context Protocol: Landscape, Security Threats, and Future Research Directions](https://arxiv.org/abs/2503.23278)** — systematic study of the MCP ecosystem, server lifecycle, and security threat taxonomy. `mcp` `security`
- **[Gorilla](https://arxiv.org/abs/2305.15334)** — retrieval-aware fine-tuned LLaMA for accurate API calls; origin of the BFCL leaderboard. `tool-calling`
- **[Toolformer](https://arxiv.org/abs/2302.04761)** — self-supervised method teaching language models when and how to call external APIs. `tool-calling`

## Learning
<!-- tutorials, explainers -->
- **[Hugging Face MCP Course](https://huggingface.co/learn/mcp-course)** — free certification course on MCP theory and practice, built with Anthropic. `mcp`
- **[Anthropic Academy: Introduction to MCP](https://anthropic.skilljar.com/introduction-to-model-context-protocol)** — Anthropic's free course on building MCP servers and clients with the Python SDK. `mcp`
- **[MCP: Build Rich-Context AI Apps with Anthropic](https://www.deeplearning.ai/short-courses/mcp-build-rich-context-ai-apps-with-anthropic/)** — DeepLearning.AI short course on building and deploying MCP servers, taught by Anthropic. `mcp`
- **[OpenAI Function Calling Guide](https://developers.openai.com/api/docs/guides/function-calling)** — OpenAI's guide to function calling: schemas, strict mode, streaming, and parallel calls. `tool-calling`

---
[← Agents hub](../README.md)
