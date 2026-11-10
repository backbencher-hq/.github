# Backbencher

> Evidence is the answer.

**bb** is local-first code intelligence for 50 languages. It indexes a repository into a
per-project SQLite database and answers questions from the CLI, from MCP-capable agents, or from
the editor — and every answer carries the record behind it instead of a guess.

```bash
npm install -g backbencher-brain
cd your-project
bb index .
bb onboard      # writes the tool guidance into AGENTS.md
```

## Repositories

- **[backbencher-brain](https://github.com/backbencher-hq/backbencher-brain)** — the engine, CLI,
  MCP server and editor integrations. MIT.
- **[backbencher-site](https://github.com/backbencher-hq/backbencher-site)** — the
  [backbencher.cc](https://backbencher.cc) website.
- **[backbencher-skills](https://github.com/backbencher-hq/backbencher-skills)** — agent skills
  for bb: when to use which tool, how to read its evidence, how to edit safely.

Security reports: see `SECURITY.md` in the brain repository. Everything here is MIT licensed.
