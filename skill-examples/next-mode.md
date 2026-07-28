# Next Mode

**Use it when:** AI work felt physically easy but required hours of judging, debugging, switching domains, and holding context—and you cannot tell whether it is safe to keep pushing.

[← Choose another skill](README.md) · [Source](https://github.com/myfeng10/next-mode)

## Actual user case

> I slept 5.5 hours. From 9 to 11 I debugged an unfamiliar agent workflow with repeated tool failures, 11 to 12 I reviewed generated code, 1 to 3 I had two tense meetings, and 3:30 to 5 I rewrote a product plan. I ate lunch and took a 15-minute walk. It is 6:20pm and I want to start a new architecture design. Should I push?

## What the old skill returned

> **Decision:** Don't push into architecture design tonight; defer it until after sleep.
>
> - Current capacity: LOW
> - Hidden spend: HIGH
> - Safe mode: RECOVERY
>
> **Primary action:** Write one sentence naming tomorrow's architecture question, then stop work and recover.

This was already decisive, but it counted the difficult tasks without naming the additional cost of moving between debugging, review, tense meetings, and product planning.

## What the current skill returns

> **Decision:** Don't push into architecture design tonight; protect it for tomorrow.
>
> - Current capacity: LOW
> - Hidden spend: HIGH
> - Safe mode: SHUTDOWN
>
> **Primary action:** Spend 10 minutes capturing the design question, constraints, and tomorrow's first step, then stop.
>
> Code review, two tense meetings, and product-plan rewriting crossed several demanding domains; **that context switching added its own cost**.

The current version makes the invisible spend legible and ends with one exact shutdown action, not a productivity menu.

[Open the complete old response](raw/next-mode-before.md) · [Open the complete current response](raw/next-mode-after.md)

## Try it

```text
Use $next-mode to decide whether I should push, switch modes, recover, or stop from my sleep and timeline.
```

```bash
npx skills add myfeng10/next-mode
```
