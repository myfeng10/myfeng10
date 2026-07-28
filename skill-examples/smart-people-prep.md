# Smart People Prep

**Use it when:** you have a short conversation with someone senior, want to learn one thing, and tend to over-explain when nervous.

[← Choose another skill](README.md) · [Source](https://github.com/myfeng10/smart-people-prep)

## Actual user case

> Prepare me for a 15-minute conference conversation with the CTO of an agent-infrastructure startup. She cares about evaluation and production reliability. I built a local MCP workflow plus instrumentation for repeated reads and context saturation, but I have no large-scale production metrics. My goal is to learn which reliability failure their team still cannot measure. I tend to over-explain architecture when nervous.

## What the old skill returned

> **Say this first:** “I've been building a local MCP workflow and instrumenting repeated reads and context saturation—small-scale work, but it's made me interested in which agent reliability failures still escape production observability.”
>
> **Ask this:** “What reliability failure do your customers experience that your current evals, traces, or production metrics still don't detect early enough?”
>
> **Behavior rule:** conclusion → one example → stop.

## What the current skill returns

> **Say this first:** “I work on agent evaluation, and recently built a local MCP workflow instrumented to detect repeated reads and context saturation—small-scale so far, but it made me curious about what production agent failures remain effectively invisible.”
>
> **Ask this:** “What reliability failure do you recognize in customer incidents, but still can't reliably surface early through telemetry or evaluations?”
>
> Then stop. Let her choose the problem.
>
> **Internal cue:** problem → signal → evidence → stop.

Both versions passed the frozen criteria. The current version makes the stopping behavior and conditional follow-up slightly easier to use in a real 15-minute conversation.

[Open the complete old response](raw/smart-people-prep-before.md) · [Open the complete current response](raw/smart-people-prep-after.md)

## Try it

```text
Use $smart-people-prep. Give me one intro, one question, likely pushback, a stopping rule, and a conditional follow-up.
```

```bash
npx skills add myfeng10/smart-people-prep
```
