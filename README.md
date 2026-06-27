# Building a Self-Maintaining Second Brain

A plain-Markdown [Obsidian](https://obsidian.md) vault that an AI coding agent ([Claude Code](https://docs.anthropic.com/en/docs/claude-code)) files, links, and dedupes for you — steered by one written contract, `CLAUDE.md`. Retrieval is **navigation-first** (the agent `grep`s to the few notes it needs), not a RAG pipeline. No vector-DB server, no SaaS.

## Two ways to read

| | |
|---|---|
| 📖 **[Full write-up →](building-a-second-brain.md)** | The complete recipe — architecture, the `CLAUDE.md` core, search stack, capture, privacy & security, automation, FAQ. |
| ⚡ **[Condensed version →](building-a-second-brain.lite.md)** | The same recipe in ~half the length, for people who want to build it fast. |

## What it is

- **Token-cheap · merge-don't-clobber · improve-don't-bloat** — the three rules the whole system optimizes for.
- A two-layer page model (compiled truth above the rule, append-only timeline below) so the agent extends notes instead of overwriting them.
- Honest about what's built, what's still manual, and what it cost. It's a recipe that works for the author, not a guaranteed turnkey product.

## Steal it

Copy the `CLAUDE.md` core from the write-up into the root of a fresh vault, point an agent at the folder, and start dumping notes. Add search, capture, privacy, and automation later, one at a time. Use any of this however you like.

*If it saved you a weekend, a ⭐ is appreciated.*
