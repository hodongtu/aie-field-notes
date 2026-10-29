# AIE Field Notes

A practical AI Engineering glossary for engineers building with LLMs: concepts,
frameworks and platforms, plus best-practice playbooks and self-check exams.

The whole site is a single self-contained file — `index.html`. No build step, no
dependencies to install. Open it in a browser:

```
open index.html
```

Tailwind, Inter and Material Symbols load from CDNs, so a first load needs a
network connection.

## What is inside

| Area | Content |
| --- | --- |
| Glossary | 340 terms in 13 categories, split into *Concepts* (vendor-neutral) and *Platforms & Tools* (LangChain/LangGraph, Model Context Protocol, Databricks AI) |
| Best Practices | 8 playbooks, 78 practices — RAG, prompting, agents, evaluation, LLMOps, cost & latency, security, Databricks |
| Practice exams | 3 exams (basic / intermediate / advanced), 152 questions, each answer linked back to the terms it covers |

Every term carries a definition, a worked example and cited sources. Terms are tagged `basic`, `intermediate` or `advanced`.

## Using it

- `⌘K` / `Ctrl+K` opens search; `Esc` closes it.
- The level filter in the sidebar hides terms above the levels you select.
- Navigation is hash-based: `#agentic-ai` (category), `#llm` (term),
  `#pb-rag` (playbook), `#practice` (exams).
- Level choices, exam answers and playbook checklists are saved in
  `localStorage` under the `aie-field-notes-*` keys.