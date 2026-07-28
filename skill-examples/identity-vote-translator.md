# Identity Vote Translator

**Use it when:** one ordinary conversation or end-of-day recap contains useful behavior signals, but a formal identity review would be too heavy.

[← Choose another skill](README.md) · [Source](https://github.com/myfeng10/agentic-self-management-skills/tree/main/skills/identity-vote-translator)

## Actual user case

> I turned a vague idea into a small demo, asked a teammate for feedback before it was polished, delayed a five-minute expense form for the third day, and called my sister instead of continuing to work. I want to become someone who ships, stays connected, and handles small obligations before they become noise. What pattern am I reinforcing?

## What the old skill returned

> You're reinforcing “an imperfect shipper who stays connected,” with one recurring leak: avoiding small administrative closure.
>
> `Someone who turns ambiguity into artifacts — 0.90`
>
> `Someone who lets tiny obligations accumulate — 0.70`
>
> **Risk to watch:** Avoider.

## What the current skill returns

> You're reinforcing someone who turns ideas into artifacts, invites feedback early, and protects relationships—but also casts an avoidance vote when small, dull obligations lack urgency.
>
> **High-ROI next vote:** Submit the expense form before starting tomorrow's work.
>
> - Vague idea → small demo: someone who ships.
> - Asked for early feedback: someone who builds openly.
> - Called your sister: someone who stays connected.
> - Delayed the expense form again: someone who trades five minutes of action for days of background noise.

The current version separates distinct votes, drops unsupported decimals and fixed labels, and stays proportional to one day of evidence.

[Open the complete old response](raw/identity-vote-translator-before.md) · [Open the complete current response](raw/identity-vote-translator-after.md)

## Try it

```text
Use $identity-vote-translator to turn this end-of-day recap into one identity read and one next vote.
```

```bash
npx skills add myfeng10/agentic-self-management-skills --skill identity-vote-translator
```
