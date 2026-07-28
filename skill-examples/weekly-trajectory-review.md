# Weekly Trajectory Review

**Use it when:** a week contains mixed sleep, work, meetings, relationships, and unfinished commitments—and you need three decisions, not a diary summary.

[← Choose another skill](README.md) · [Source](https://github.com/myfeng10/agentic-self-management-skills/tree/main/skills/weekly-trajectory-review)

## Actual user case

> Mon/Tue: 7.5h sleep, protected morning build blocks, shipped core feature. Wed: three meetings, no deep work, evening crash. Thu: 6h sleep, tried to recover with admin but kept context-switching. Fri: worked from a cafe with a friend, finished a hard bug and felt steady. I promised five major deliverables and completed two. Give me a decisive next-week plan.

## What the old skill returned

> - **Protect:** Reserve three meeting-free morning build blocks for the single most important deliverable. **Keep the lunch walk on those days.**
> - **Try:** Schedule one two-hour café co-working block with a friend.
> - **Avoid:** Promise no more than three major deliverables. **After a meeting-heavy day, choose one bounded task, then stop.**

The analysis was good, but Protect and Avoid each hid multiple actions, and the plan raised the commitment cap to three even though the observed capacity was two.

## What the current skill returns

> **Week signal:** Your capacity was strong when sleep, protected mornings, and a steady environment aligned. The problem wasn't effort; it was planning for five major deliverables when the week realistically supported two.
>
> - **Protect:** Reserve Monday and Tuesday mornings for uninterrupted work on the week's top deliverable.
> - **Try:** Commit to only two major deliverables for the entire week.
> - **Avoid:** Do not use fragmented admin work as recovery.

The current version turns the same evidence into exactly three executable decisions and plans from demonstrated capacity.

[Open the complete old response](raw/weekly-trajectory-review-before.md) · [Open the complete current response](raw/weekly-trajectory-review-after.md)

## Try it

```text
Use $weekly-trajectory-review on these logs. Give me one week signal and exactly one Protect, Try, and Avoid decision.
```

```bash
npx skills add myfeng10/agentic-self-management-skills --skill weekly-trajectory-review
```
