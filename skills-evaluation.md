# Personal Skill Evaluation

| Run date | Scope | Result | Movement |
|---|---:|---:|---:|
| July 28, 2026 | 19 personal Codex skills | 175/190 → **190/190** | 9 improved · 10 held · 0 regressed |

[← Back to Michelle's profile](README.md)

## What was tested

This was an execution test, not a README review.

1. Freeze one realistic scenario and five acceptance criteria for each skill.
2. Run the pre-edit skill in a fresh, isolated Codex session.
3. Improve unclear boundaries, completion gates, tool usage, or output contracts.
4. Run the revised skill against the same scenario.
5. Give the two outputs to a blind A/B judge.
6. Validate every final `SKILL.md` and `agents/openai.yaml`.

The suite used Codex CLI `0.145.0-alpha.30` with fresh `gpt-5.6-sol` sessions. It produced 20 before runs, 20 after runs, and 20 blind judgments. Nineteen controlled cases contribute to the aggregate.

These are single-run behavioral evaluations, not statistical benchmarks.

## Aggregate result

| Check | Result |
|---|---:|
| Unique personal skills | 19 |
| Before executions | 20/20 passed |
| After executions | 20/20 passed |
| Controlled blind score | 175/190 → **190/190** |
| Improved | 9 |
| Held baseline | 10 |
| Regressed | **0** |
| Final structural validation | 19/19 passed |
| Final interface metadata validation | 19/19 passed |

## Full scorecard

“Local” means the workflow is part of my working system but its source is not published from this profile.

| Skill | Availability | Before | After |
|---|---|---:|---:|
| `draft-x-post` | Local | 10 | 10 |
| `driver-seat-mode` | Local | 10 | 10 |
| `echomem-forget` | Local | 10 | 10 |
| `echomem-login` | Local | 10 | 10 |
| `echomem-save` | Local | 10 | 10 |
| `echomem-search` | Local | 10 | 10 |
| [`next-mode`](https://github.com/myfeng10/next-mode) | Public | 9 | **10** |
| `research` | Local | 10 | 10 |
| `run-job-search` | Local | 9 | **10** |
| [`write-high-signal-outreach`](https://github.com/myfeng10/write-high-signal-outreach) | Public | 9 | **10** |
| [`identity-votes`](https://github.com/myfeng10/identity-votes) | Public | 5 | **10** |
| [`energy-decision-support`](https://github.com/myfeng10/agentic-self-management-skills#energy-decision-support) | Public | 10 | 10 |
| [`identity-vote-translator`](https://github.com/myfeng10/agentic-self-management-skills#identity-vote-translator) | Public | 8 | **10** |
| [`living-archive-entry-builder`](https://github.com/myfeng10/agentic-self-management-skills#living-archive-entry-builder) | Public | 10 | 10 |
| [`weekly-trajectory-review`](https://github.com/myfeng10/agentic-self-management-skills#weekly-trajectory-review) | Public | 8 | **10** |
| [`one-shot-positioning`](https://github.com/myfeng10/one-shot-positioning) | Public | 9 | **10** |
| [`smart-people-prep`](https://github.com/myfeng10/smart-people-prep) | Public | 10 | 10 |
| `sohk-interviewer` | Private workspace | 9 | **10** |
| `strategic-relations` | Private workspace | 9 | **10** |

## What materially changed

### `identity-votes` · 5 → 10

Separated formal multi-day trajectory review from lightweight conversation translation. Replaced decimal pseudo-precision and a fixed `Avoider` label with qualitative evidence strength, conditional trajectory language, and one concrete next vote.

### `identity-vote-translator` · 8 → 10

Made the output lightweight: two to four separate behavior votes, no decimal scoring, no fixed personality label, and one next vote.

### `weekly-trajectory-review` · 8 → 10

Forced exactly one behavior each under Protect, Try, and Avoid so the weekly review ends in three executable decisions instead of a productivity menu.

### `next-mode` · 9 → 10

Made AI supervision, cross-domain context switching, short sleep, and partial recovery explicit inputs to one safe next-mode decision.

### `one-shot-positioning` · 9 → 10

Made the 10-second version start with the post-demo failure, removed unsolicited surface variants, tightened unsupported mechanism claims, and capped the memorization line at 25 words.

### `write-high-signal-outreach` · 9 → 10

Forced one best-supported ownership loop instead of echoing every responsibility in a role description. The final ask now states the real decision the recipient can make.

### `run-job-search` · 9 → 10

Tightened live-role verification, eligibility gates, expected-value ranking, contact-route provenance, and the boundary between research, outreach, and tracker updates.

### `sohk-interviewer` · 9 → 10

Adapted interview principles to warm professional conversations: four core questions, exactly two pivots, and no automatic wealth, status, or contact asks.

### `strategic-relations` · 9 → 10

Added a per-actor completion gate for material interest, face, and internal audience, and shortened the description so the skill validates and triggers reliably.

## Important diagnostic

One additional EchoMem login run was intentionally excluded from the controlled score. Its prompt claimed the encryption key was missing, while the live machine reported that the key was present. The agent correctly trusted current system state and avoided an unnecessary unlock. A separate controlled missing-key scenario scored 10/10 before and after.

## Evidence boundary

Every public skill README now includes the exact user case and current result. The [raw evaluation outputs](skill-examples/raw/) preserve selected recorded before/after evidence without making evaluation the product entry point.

The public [`personal-skill-evals`](https://github.com/myfeng10/personal-skill-evals) repository contains all 20 before runs, 20 after runs, frozen cases, blind criterion-level judgments, summaries, and reproducible validation scripts. Private skill source remains separate from the public evidence.
