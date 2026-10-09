# elieve

**Open-source AI agent framework** — a modular ReAct loop with function calling,
sandboxed tools, and a harness built for long autonomous runs.

- **Context compaction** — 4-layer pipeline (micro, threshold, LLM, cache-preserving)
- **Memory** — cross-session notes with automatic tidying
- **Permission gate** — optional 2-stage classifier (lightning + reasoning)
- **Orchestrator** — parallel subagents with failure isolation
- **Hooks, task tracking, token accounting, MCP client, checkpoints, plan mode**

Works with any OpenAI-compatible provider. `pip install elieve` (soon) · Android APK (Termux-based) in progress.

→ **[kenyangbali/elieve](https://github.com/kenyangbali/elieve)**
