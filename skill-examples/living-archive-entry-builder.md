# Living Archive Entry Builder

**Use it when:** a project, realization, or period mattered and you want future you to recover what happened, what changed, and why it was worth remembering.

[← Choose another skill](README.md) · [Source](https://github.com/myfeng10/agentic-self-management-skills/tree/main/skills/living-archive-entry-builder)

## Actual user case

> In July 2026 I built a tiny context-health overlay after repeatedly losing the thread in long AI coding sessions. At first I blamed model quality; the real problem was that neither the agent nor I could see the stale context accumulating. It changed how I think about AI UX: systems should expose when their own state becomes unreliable. Future me should remember that the useful product came from noticing my own confusion instead of hiding it.

## What the old skill did

> Drafted the living-archive entry in `context-health-overlay.md`.

The entry itself was good, but the skill wrote a file even though the user asked only for a draft. The content was hidden behind a side effect.

[Open the file the old skill created](raw/living-archive-entry-builder-before-artifact.md)

## What the current skill returns

> **Title:** When Context Became Visible
>
> **Time period:** July 2026
>
> **Thread:** Making hidden system state legible
>
> **Pull:** I kept losing the thread during long AI coding sessions. I initially blamed model quality, but the deeper problem was shared blindness…
>
> **Future-self note:** When I repeatedly lose the thread, do not assume I need a better model or more discipline. Look for the invisible condition shaping the interaction. Confusion can be an instrument.

The current version returns the complete draft inline. It writes or edits a file only when the user explicitly asks.

[Open the complete old response](raw/living-archive-entry-builder-before.md) · [Open the complete current response](raw/living-archive-entry-builder-after.md)

## Try it

```text
Use $living-archive-entry-builder to turn this project story into a draft future-self archive entry. Return it inline.
```

```bash
npx skills add myfeng10/agentic-self-management-skills --skill living-archive-entry-builder
```
