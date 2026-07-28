# One-Shot Positioning

**Use it when:** the work is real, but your explanation starts with tools, components, or unsupported outcome claims.

[← Choose another skill](README.md) · [Source](https://github.com/myfeng10/one-shot-positioning)

## Actual user case

> Help me explain this project to an AI infrastructure hiring manager. I made a local MCP tool, a context-health HUD, and a warm-start handoff because long coding sessions kept repeating file reads and losing decisions. I built and tested the full loop locally, but I do not have verified productivity or retention metrics.

## What the old skill returned

> **10-second version:** I built a local context-continuity system for AI coding sessions that detects context degradation and packages the essential state for a clean handoff.

It was accurate, but opened with the solution and added unrequested Resume, GitHub, and Outreach variants.

## What the current skill returns

> **10-second version:** Long-running coding agents degrade as context fills, rereading files and losing prior decisions, so I built a local system that detects those failure signals and creates clean-session handoffs.
>
> **Memorize this:** Long coding sessions degrade as context fills, so I built a local system that detects failure signals and creates clean-session handoffs.

The current version lets the hiring manager understand the post-demo failure before hearing the component list. It keeps the claim honest: the mechanism works locally; productivity gains are not yet proven.

[Open the complete old response](raw/one-shot-positioning-before.md) · [Open the complete current response](raw/one-shot-positioning-after.md)

## Try it

```text
Use $one-shot-positioning on this messy project description. Give me the 10-second version, proof, hard-part answer, and one line to memorize.
```

```bash
npx skills add myfeng10/one-shot-positioning
```
