# AGENTS.md

Global rules for AI agents, inspired by https://github.com/openai/agents.md.

## Usage

- [`AGENTS.md`](AGENTS.md) contains my personal preferences and rules
- [`AGENTS.min.md`](AGENTS.min.md) is a minimal template for everyone to repeat this practice

Include `~/agents.md/AGENTS.md` to your agent (e.g. Cursor) default context to use this global rule.

To create your own:
1. Fork this repo
2. Copy `AGENTS.min.md` to `AGENTS.md` (overwrite existing)
3. Use `remember <preference>` to ask your agent to modify `AGENTS.md` with your preferences

Examples:
- `remember: never commit without my explicit approval`
- `remember: always use TypeScript for new projects`
- `remember globally: MUST use conventional commit format`
- `remember globally: MUST include error handling in all API calls`
