# skills

A collection of portable AI agent skills authored by Felipe Mello. Each skill is a single `SKILL.md` file — drop it into your agent runtime's skills directory and the runtime activates it by description match.

## Available skills

### [ai-showcase](./ai-showcase) — Notion submission flow

Interviews creators and submits AI use cases to a company's Notion AI Showcase gallery via Notion MCP. Designed around one principle: **the skill is the only runtime dependency.** No npm packages, no helper CLIs, no on-disk state — every step uses MCPs already in the agent's session.

Install (Cursor, macOS/Linux):

```bash
mkdir -p ~/.cursor/skills/ai-showcase && \
  curl -fsSL https://raw.githubusercontent.com/felipemellovoodoo/skills/main/ai-showcase/SKILL.md \
  -o ~/.cursor/skills/ai-showcase/SKILL.md
```

For Claude Code or Anthropic Agents, replace `~/.cursor/skills/` with `~/.claude/skills/` or `~/.agents/skills/`. Each skill's full install + usage instructions live on the gallery's Notion landing page, not in this repo.

## License

MIT — see [`LICENSE`](./LICENSE).
