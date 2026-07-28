# Energy Decision Support

**Use it when:** you need one capacity-based decision from ordinary signals such as sleep, meetings, food, movement, timing, and accumulated work.

[← Choose another skill](README.md) · [Source](https://github.com/myfeng10/agentic-self-management-skills/tree/main/skills/energy-decision-support)

## Actual user case

> I slept 6 hours. I wrote from 8 to 10, ran errands until noon, had a high-stakes interview from 1 to 2, and handled admin from 2:30 to 4. I ate, drank water, and took a 20-minute walk. It is 4:30 and I am considering a two-hour strategy session. What should I do next?

## What the old skill returned

> **Decision:** Defer the two-hour strategy session and stop cognitively demanding work for today.
>
> **Primary action:** End the workday now and protect the evening for recovery.
>
> **Fallback:** If you must continue, spend no more than 30 minutes organizing existing notes.

## What the current skill returns

> **Decision:** Defer the two-hour strategy session and end demanding work for today.
>
> **Primary action:** Take the next hour fully off—no planning, admin, or consequential decisions.
>
> **Fallback:** If you must continue, spend 20 minutes capturing strategy questions and facts only, then schedule the actual session after a full night's sleep.
>
> Errands and admin added sustained effort and several context switches.

Both versions made the right decision. The current version gives a more behaviorally precise recovery block and names context switching as part of the capacity cost.

[Open the complete old response](raw/energy-decision-support-before.md) · [Open the complete current response](raw/energy-decision-support-after.md)

## Try it

```text
Use $energy-decision-support to choose one safe next action from my sleep, timeline, recovery, and current decision.
```

```bash
npx skills add myfeng10/agentic-self-management-skills --skill energy-decision-support
```
