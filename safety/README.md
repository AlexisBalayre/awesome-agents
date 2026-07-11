# Safety — Guardrails, Sandboxing, Policy

Keeping agents contained and well-behaved: guardrails, sandboxes, permission & policy systems.

## Tools & Libraries
<!-- add: guardrail libraries, sandbox runtimes, permission systems, ... -->
- **[NeMo Guardrails](https://github.com/NVIDIA-NeMo/Guardrails)** — NVIDIA toolkit for adding programmable guardrails to LLM conversational systems. `guardrails`
- **[Guardrails AI](https://github.com/guardrails-ai/guardrails)** — Python framework validating LLM inputs and outputs with reusable guard validators. `guardrails` `validation`
- **[PurpleLlama](https://github.com/meta-llama/PurpleLlama)** — Meta's LLM security suite: Llama Guard, LlamaFirewall, and CyberSecEval. `guardrails` `red-teaming`
- **[E2B](https://github.com/e2b-dev/E2B)** — open-source sandboxed cloud environments for running untrusted AI-generated code. `sandboxing` `code-agents`
- **[garak](https://github.com/NVIDIA/garak)** — NVIDIA's LLM vulnerability scanner probing jailbreaks, leakage, and prompt injection. `red-teaming` `prompt-injection`
- **[gVisor](https://github.com/google/gvisor)** — user-space application kernel widely used to sandbox agent code execution. `sandboxing`

## Protocols & Standards
<!-- policy languages, permission schemas, ... -->
- **[OWASP Top 10 for LLM Applications](https://genai.owasp.org/llm-top-10/)** — de-facto risk taxonomy for LLM apps, covering prompt injection and excessive agency. `threat-model`
- **[MITRE ATLAS](https://atlas.mitre.org/)** — ATT&CK-style knowledge base of adversarial tactics and techniques against AI systems. `threat-model` `red-teaming`

## Benchmarks & Leaderboards
<!-- safety/red-teaming benchmarks for agents, ... -->
- **[AgentDojo](https://github.com/ethz-spylab/agentdojo)** — dynamic environment measuring prompt-injection attacks and defenses on tool-calling agents. `prompt-injection`
- **[AgentHarm](https://huggingface.co/datasets/ai-safety-institute/AgentHarm)** — malicious agent task suite from UK AISI measuring harmful compliance and refusal. `red-teaming`

## Papers & Research
<!-- key papers -->
- **[Defeating Prompt Injections by Design (CaMeL)](https://arxiv.org/abs/2503.18813)** — DeepMind system-level defense isolating untrusted data from control flow via capabilities. `prompt-injection`
- **[The Instruction Hierarchy](https://arxiv.org/abs/2404.13208)** — OpenAI's training approach teaching LLMs to prioritize privileged instructions over injected ones. `prompt-injection` `alignment`
- **[Universal and Transferable Adversarial Attacks on Aligned Language Models](https://arxiv.org/abs/2307.15043)** — the GCG attack: adversarial suffixes that jailbreak aligned models and transfer. `jailbreaks`
- **[Not what you've signed up for](https://arxiv.org/abs/2302.12173)** — the paper that introduced indirect prompt injection against LLM-integrated applications. `prompt-injection`
- **[Constitutional AI: Harmlessness from AI Feedback](https://arxiv.org/abs/2212.08073)** — Anthropic's method training harmless models via AI feedback against a written constitution. `alignment`

## Learning
<!-- tutorials, explainers -->
- **[Prompt injection series](https://simonwillison.net/series/prompt-injection/)** — Simon Willison's essay series from the term's coiner, including the lethal trifecta. `prompt-injection`
- **[Gandalf](https://gandalf.lakera.ai/)** — Lakera's interactive game teaching prompt-injection attacks by leveling up against defenses. `prompt-injection`
- **[Red Teaming LLM Applications](https://www.deeplearning.ai/short-courses/red-teaming-llm-applications/)** — DeepLearning.AI short course on probing and attacking LLM apps, with Giskard. `red-teaming`

---
[← Agents hub](../README.md)
