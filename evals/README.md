# Evals — Benchmarks & Evaluation

How agents are measured: benchmarks, eval harnesses, leaderboards.

## Tools & Libraries
<!-- add: eval harnesses, trace/observability tooling for evals, ... -->
- **[openevals](https://github.com/langchain-ai/openevals)** — prebuilt LLM-as-judge and string evaluators for testing LLM applications, in Python and TypeScript. `llm-as-judge`
- **[agentevals](https://github.com/langchain-ai/agentevals)** — evaluators for agent trajectories: trajectory match and LLM-as-judge over intermediate steps. `llm-as-judge` `trajectory`

## Protocols & Standards
<!-- eval task formats, reporting conventions, ... -->

## Benchmarks & Leaderboards
<!-- add: agent benchmarks, leaderboards, ... -->
- **[SWE-bench](https://github.com/SWE-bench/SWE-bench)** — 2,294 real GitHub issues; the de-facto benchmark for autonomous coding agents. `coding`
- **[GAIA](https://huggingface.co/spaces/gaia-benchmark/leaderboard)** — 466 real-world assistant questions requiring tool use, browsing, and multimodal reasoning. `tool-use` `multimodal`
- **[AgentBench](https://github.com/THUDM/AgentBench)** — evaluates LLMs as agents across eight interactive environments, from OS to web. `multi-environment`
- **[WebArena](https://github.com/web-arena-x/webarena)** — self-hostable realistic web environment with 812 tasks for autonomous browser agents. `web-agents`
- **[OSWorld](https://github.com/xlang-ai/OSWorld)** — real-computer environment benchmarking multimodal agents on 369 open-ended desktop tasks. `computer-use` `multimodal`
- **[τ-bench](https://github.com/sierra-research/tau-bench)** — simulates user–agent conversations where tool-using agents must follow domain policy rules. `tool-calling` `simulated-users`

## Papers & Research
<!-- key papers -->
- **[Establishing Best Practices for Building Rigorous Agentic Benchmarks](https://arxiv.org/abs/2507.02825)** — audits flaws in agent benchmarks and proposes the Agentic Benchmark Checklist. `methodology`
- **[Survey on Evaluation of LLM-based Agents](https://arxiv.org/abs/2503.16416)** — comprehensive survey covering agent capabilities, application benchmarks, evaluation frameworks, and open gaps. `survey`
- **[AI Agents That Matter](https://arxiv.org/abs/2407.01502)** — argues agent benchmarks overfit accuracy and ignore cost; urges cost-controlled, reproducible evaluation. `cost-aware` `methodology`
- **[Judging LLM-as-a-Judge with MT-Bench and Chatbot Arena](https://arxiv.org/abs/2306.05685)** — foundational LLM-judge study measuring agreement with human preferences and characterizing judge biases. `llm-as-judge`

## Learning
<!-- tutorials, explainers -->
- **[LLM Evaluation Guidebook](https://github.com/huggingface/evaluation-guidebook)** — practical and theoretical evaluation guidance from the Open LLM Leaderboard team. `benchmarking` `llm-as-judge`
- **[Your AI Product Needs Evals](https://hamel.dev/blog/posts/evals/)** — widely cited practitioner guide to building eval systems for LLM products. `llm-as-judge`
- **[Evaluating AI Agents](https://www.deeplearning.ai/short-courses/evaluating-ai-agents/)** — DeepLearning.AI short course on tracing, evaluating, and monitoring agents, with Arize. `observability`

---
[← Agents hub](../README.md)
