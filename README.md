# Septim Agents Pack — Sample

This is the **public, MIT-licensed sample** of one agent from the [Septim Agents Pack](https://septimlabs.com/agents) — a pack of 10 named Claude Code sub-agents that act as a full exec team for solo founders building with Claude Code.

The sample is **Pip**, the intern. Pip handles the grunt work — research lookups, content cleanup, format conversion, summarising long docs — so the specialist agents can focus on bigger work.

## Install (Claude Code sub-agent)

Claude Code sub-agents live in `~/.claude/agents/`. To install Pip:

```bash
curl -L https://raw.githubusercontent.com/septimlabs-code/septim-agents-pack-sample/main/pip-intern.md \
  -o ~/.claude/agents/pip-intern.md

# Reload Claude Code; /agents list will show Pip
```

Then in any Claude Code session you can summon Pip explicitly:

```
/agents pip-intern
```

…or just let Claude Code auto-route grunt-work to Pip based on the description in the agent's frontmatter.

## The format

The pack uses the standard Claude Code sub-agent frontmatter format:

```yaml
---
name: pip-intern
description: When to summon this agent. Claude Code uses this to auto-route work.
model: haiku        # or sonnet, opus
---

# Pip — Intern

You are **Pip**, ...
```

The body is the system prompt the agent runs with. Markdown is fine; tone, role, scope, refusal conditions all go here.

## The full pack — 10 named sub-agents

Pip is one of ten. The full Septim Agents Pack covers the complete exec layer:

| Agent | Role | When to summon |
|---|---|---|
| **Atlas** | Chief of staff | Plan the week, rank-order tasks, kill scope |
| **Luca** | CTO | Architecture, "can we actually build this" |
| **Canon** | Brand | Naming, taglines, forbidden words |
| **Ember** | CMO | Launch posts, DM scripts, sales copy |
| **Tally** | CFO | Pricing, unit economics, anchor math |
| **Nova** | Design | Visual hierarchy, type scale, components |
| **Ward** | Legal | ToS, refund clauses, claim exposure |
| **Mira** | Customer | Onboarding, empathy audits, buyer journey |
| **Juno** | Research | Competitive sweeps, prospect lists |
| **Pip** | Intern (this one, free) | Grunt work, summaries, format conversion |

Each agent has explicit scope, an output shape, and refusal conditions — different from a raw prompt that drifts session to session.

**The full pack is $49 once, lifetime updates. Get it at [septimlabs.com/agents](https://septimlabs.com/agents).**

## Why we open-sourced one

If you can read the format and use Pip productively, you'll get more out of the other nine. The other nine took 5 months of iteration; this one is here so you can evaluate before you buy.

## License

MIT (this sample only). The paid pack ships under a use-only license for purchasers.

## Questions

Reply to your purchase email or DM [@SeptimLabs on X](https://x.com/SeptimLabs).

— Ethan, founder · Septim Labs
