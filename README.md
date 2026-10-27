# Robert Nyborg

I build agent tooling in Seattle. I run Claude Code all day at Peek Technologies (multifamily real-estate data) and publish the harness pieces that held up under measurement: hooks, skills, evals, and multi-session tools.

Each repo started from a failure I counted.

| Repo | What it does | The number behind it |
|---|---|---|
| [claude-guardrails](https://github.com/robertmnyborg/claude-guardrails) | Hooks that enforce rules a CLAUDE.md file can't | Chained `sleep` calls fell from 138 a week to 1 after a 10-line hook |
| [harness-doctrine](https://github.com/robertmnyborg/harness-doctrine) | Four questions that decide where a model belongs in a harness | A 70-line normalizer hit 99.89% recall in 2 s; a local 30B model hit 94.95% in 2.6 h |
| [skill-eval](https://github.com/robertmnyborg/skill-eval) | Runs a skill with and without, judges both arms, reports the delta | A public skill scored 77% loaded vs 97% without it |
| [analyst-rigor-skills](https://github.com/robertmnyborg/analyst-rigor-skills) | Skills that stop an agent from fabricating causal claims, root causes, quotes, and personas | Each rule follows a wrong answer an agent shipped |
| [cmux-agent-kit](https://github.com/robertmnyborg/cmux-agent-kit) | Pair, spin off, and split Claude Code sessions in cmux | One 8-day session cost 48% of two weeks of spend |
| [agent-overworld](https://github.com/robertmnyborg/agent-overworld) | Live map of every agent session, with status and last-reply recap | |
| [plan-notes](https://github.com/robertmnyborg/plan-notes) | Inline `@@` review notes on a plan, answered in one pass, with a decision ledger | |

Stack: Claude Code (hooks, skills, subagents, MCP servers), Python, Shell, TypeScript, Postgres.
