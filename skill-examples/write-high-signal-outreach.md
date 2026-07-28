# High-Signal Outreach

**Use it when:** you have a real reason to contact someone and need one evidence-backed message—not a biography, compliment, or disguised ask.

[← Choose another skill](README.md) · [Source](https://github.com/myfeng10/write-high-signal-outreach)

## Actual user case

> Write a 60–110 word email to Dr. Rao about the Research Engineer role on her agent-evaluation team. The team needs dataset construction, evaluation design, and production feedback analysis. My proof: I built a LongMemEval evaluation pipeline and shipped retrieval feedback instrumentation. My actual intention is to apply, not ask for a generic research chat.

## What the old skill returned

> Hi Dr. Rao,
>
> I'm reaching out to apply for the Research Engineer role on your agent-evaluation team. **I can contribute across dataset construction, evaluation design, and production feedback analysis.** I built a LongMemEval evaluation pipeline and shipped retrieval feedback instrumentation…

The intent and proof were clear, but “contribute across” repeated the entire job description instead of choosing one credible surface.

## What the current skill returns

> Hi Dr. Rao,
>
> I'm applying for the Research Engineer role on your agent-evaluation team. **I can own the evaluation loop from benchmark construction through analysis of production failures.** I built a LongMemEval evaluation pipeline and shipped retrieval feedback instrumentation…
>
> Does this background fit what you need for the role, and would a brief conversation make sense?

The current version turns three responsibilities into one coherent ownership loop and asks for the actual decision.

[Open the complete old response](raw/write-high-signal-outreach-before.md) · [Open the complete current response](raw/write-high-signal-outreach-after.md)

## A real project using the workflow

The [EchoMem Group outreach research pack](../case-studies/echomem-outreach-research/README.md) applies the same reasoning beyond one email:

- find people who publicly described a real cross-person AI-context problem
- score the signal before researching the person
- write down `Signal`, `Pain hypothesis`, `EchoMem connection`, and `Why now`
- show one concrete private-by-default product moment
- ask for one 3–5 person workflow pilot

The pack includes the actual ICP rubric, message rubric, playbook, message library, research notes, and lead tracker.

## What to give the skill

- the recipient and their current role
- the role, project, paper, company need, or collaboration surface
- source links, or a short block of context you have already verified
- your real intention: job, collaboration, referral, pilot, or follow-up
- one or two proofs you can support
- the channel and length when they matter

If current facts need verification and browsing is available, the skill researches them. If browsing is unavailable, provide the verified context directly instead of asking it to guess.

The default deliverable is the sendable message first. Research reasoning stays behind the draft unless uncertainty affects whether the message is safe to send or you explicitly ask for a research brief.

## Try it

```text
Use $write-high-signal-outreach to research this recipient, choose the one ownership loop my evidence supports best, and draft one sendable message. Recipient/source: […]. Real intention: […]. My proof: […]. Channel and length: […].
```

```bash
npx skills add myfeng10/write-high-signal-outreach
```
