# AI contributor plumbing

The repository uses four complementary layers:

1. `AGENTS.md` for compact rules that apply to every task.
2. Nested `AGENTS.md` files for schema and reference-specific rules.
3. `.agents/skills/` for reusable workflows with progressive disclosure.
4. `.codex/agents/` for narrow, read-only specialist subagents.

Standalone custom-prompt files are intentionally not included because current Codex guidance deprecates them in favor of
skills. Human-readable prompt recipes remain in `prompt-recipes.md`.

Custom agents inherit the active parent model unless a user explicitly selects another configuration. This avoids
silently hard-coding a model that may become stale or inappropriate.

The primary agent remains the single writer. Specialist agents gather or review evidence and return concise findings.
