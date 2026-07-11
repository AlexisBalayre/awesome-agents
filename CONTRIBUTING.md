# Contributing / Curation rules

This is a curated list, not an exhaustive one. Quality over quantity.

## Entry format

One bullet per entry, in this shape:

```
- **[Name](https://link)** — one-line description of what it is and why it's notable. `tag` `tag`
```

Example:

```
- **[smolagents](https://github.com/huggingface/smolagents)** — barebones library for agents that think in code. `code-agents`
```

Tags are short, lowercase, backticked keywords — e.g. `multi-agent`, `mcp`, `tool-calling`, `sandboxing`, `benchmark`, `long-term-memory`, `local`.

## Rules

1. **Open source preferred.** Mark closed/commercial entries clearly if included.
2. **Still maintained.** No dead links; prefer projects with recent activity.
3. **One line.** If it needs more, link to a dedicated note.
4. **Right section.** Put it under the matching heading in the matching domain.
5. **No duplicates.** Search before adding.
6. **Order** within a section: roughly by relevance/popularity, newest-notable first.

## Domain structure

One directory per domain (`frameworks/`, `protocols/`, `memory/`, `evals/`, `safety/`).
Every domain `README.md` uses the **same fixed sections**, in this order:

- **Tools & Libraries**
- **Protocols & Standards**
- **Benchmarks & Leaderboards**
- **Papers & Research**
- **Learning**

Keep all five headings even when a section is empty (leave a `<!-- -->` placeholder) —
consistency is what lets the curation tooling file entries mechanically.

## Adding a domain

Copy an existing domain `README.md` as a template and keep the same section headings.
