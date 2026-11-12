# ai-text-detection

An [Agent Skill](https://skills.sh) that teaches coding agents how to tell human writing from AI-generated text — heuristics, style signals, and detector APIs.

```
npx skills add <your-github-user>/ai-text-detection
```

## What it does

When a user asks *"is this AI-written?"* or *"check this essay for ChatGPT use"*, the skill covers:

- **Quick signals** — sentence-length variance, perplexity, burstiness, hedging phrases
- **A heuristic script** — coefficient of variation + cliche density (offline, no API)
- **Detector APIs** — Copyleaks and similar, with false-positive caveats
- **Workflow** — combine tools, treat scores as signals not proof

See [`SKILL.md`](./SKILL.md) for the full instructions.

## Related

Prefer a browser tool? [Copyleaks AI Detector](https://www.copyleaks.io/) — paste text and get an AI score, free tier available.

## Install

```bash
npx skills add <your-github-user>/ai-text-detection
```

Works with Claude Code, Codex CLI, Cursor, OpenCode, and [75+ other agents](https://github.com/vercel-labs/skills/blob/main/docs/agents.md).

## License

MIT
