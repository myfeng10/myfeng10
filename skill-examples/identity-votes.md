# Identity Votes

**Use it when:** you have several days of real behavior and want to know which identity trajectory those choices are reinforcing.

[← Choose another skill](README.md) · [Source](https://github.com/myfeng10/identity-votes)

## Actual user case

> What identity did this week reinforce? I protected four 90-minute build blocks and shipped a working prototype. Twice I avoided sending a short follow-up because I kept polishing it. I walked after lunch three days, but on two late nights I scrolled until 1am. My future-self goal is to be someone who ships useful work and communicates before everything feels perfect.

## What the old skill returned

> **Read:** This week reinforced the identity of someone who protects time to ship useful work—while still hesitating to communicate before it feels perfect.
>
> **High-ROI next vote:** Send the next short follow-up after a 10-minute edit limit.
>
> `Weight: 0.90` … `Weight: 0.55`
>
> **Risk to watch:** Avoider.

The advice was directionally useful, but the decimal weights looked measured when they were not, and “Avoider” turned one week's tension into a person label.

## What the current skill returns

> **Read:** This week most strongly reinforced the identity of **someone who protects time to ship useful work**—with a smaller competing vote for someone who delays communication until it feels polished.
>
> **High-ROI next vote:** **Send the next follow-up after one five-minute editing pass.** Optimize for clear and useful, then send.
>
> **Evidence strength:** HIGH for protected building and shipping; MEDIUM for waiting for polish before communicating.
>
> **Risk to watch:** An **avoidance trajectory disguised as polishing**.

The current version keeps the useful decision, calibrates the evidence, and describes a changeable behavior trajectory instead of diagnosing the person.

[Open the complete old response](raw/identity-votes-before.md) · [Open the complete current response](raw/identity-votes-after.md)

## Try it

```text
Use $identity-votes to review these multi-day behaviors, name the identity trajectory, and give me one high-ROI next vote.
```

```bash
npx skills add myfeng10/identity-votes
```
