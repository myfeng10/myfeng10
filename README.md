<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/banner-dark.svg">
  <img alt="Michelle Yilin Feng — I turn messy human context into memory, judgment, and reusable agent behavior" src="assets/banner-light.svg" width="100%">
</picture>

<p>
  <a href="https://www.myfeng10.com/"><img src="https://img.shields.io/badge/web-myfeng10.com-0969da?style=flat-square&logo=safari&logoColor=white" alt="Website"></a>
  <a href="https://www.linkedin.com/in/michelle-yilin-feng/"><img src="https://img.shields.io/badge/LinkedIn-michelle--yilin--feng-0a66c2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="mailto:myfeng10d@gmail.com"><img src="https://img.shields.io/badge/email-myfeng10d%40gmail.com-57606a?style=flat-square&logo=gmail&logoColor=white" alt="Email"></a>
  <a href="https://yeahecho.com"><img src="https://img.shields.io/badge/now-founding_engineer_@_Iditor-1a7f37?style=flat-square" alt="Now"></a>
</p>

<p>
  <a href="skills-evaluation.md"><img src="https://img.shields.io/badge/personal_skills-19-8250df?style=flat-square" alt="19 personal skills"></a>
  <a href="skills-evaluation.md"><img src="https://img.shields.io/badge/real_before%2Fafter_runs-20%20%2B%2020-0969da?style=flat-square" alt="20 before and 20 after runs"></a>
  <a href="skills-evaluation.md"><img src="https://img.shields.io/badge/blind_score-190%2F190-1a7f37?style=flat-square" alt="190 out of 190 blind score"></a>
  <a href="skills-evaluation.md"><img src="https://img.shields.io/badge/regressions-0-1a7f37?style=flat-square" alt="Zero regressions"></a>
</p>

I build tools for the part of AI work that breaks after the demo: fragmented context, changing state, hidden effort, unclear positioning, and the gap between thinking and action.

**Now:** Founding engineer at [Iditor](https://yeahecho.com) (EchoMemory) — cross-platform AI memory across iOS, web, Chrome extension, and MCP/agent workflows. BU Computer Science '25.

My current focus is simple:

> Turn messy human context into memory, judgment, and reusable agent behavior.

---

## 🧭 Current Thesis

AI can generate more output than people can judge.

So the bottleneck moves to:

- what context should be preserved
- what changed since last time
- what evidence supports the answer
- what mode is safe next
- what identity a repeated behavior is reinforcing
- what one sentence makes the work understandable

I am interested in AI systems that do not only answer the current prompt, but help people carry context forward.

---

## 🛠️ Public Agent Skills

Small installable skills that turn recurring friction into reusable agent behavior. Each one has a bounded job and was run against a frozen scenario before and after revision.

| Skill | One job | Before → after |
|---|---|---:|
| 🪞 [identity-votes](https://github.com/myfeng10/identity-votes) | Compare several days of behavior, name the identity trajectory without diagnosing the person, and choose one next vote. | 5 → **10** |
| 🔋 [next-mode](https://github.com/myfeng10/next-mode) | Read hidden effort from AI-assisted work and choose one safe mode: push, switch, recover, or stop. | 9 → **10** |
| 🎯 [one-shot-positioning](https://github.com/myfeng10/one-shot-positioning) | Lead with the post-demo failure, prove the hard part, and return one honest sentence to remember. | 9 → **10** |
| 🤝 [smart-people-prep](https://github.com/myfeng10/smart-people-prep) | Prepare one intro, bounded proof, one useful question, pushback practice, and a conditional follow-up. | 10 → **10** |
| ✉️ [write-high-signal-outreach](https://github.com/myfeng10/write-high-signal-outreach) | Build one evidence-backed outreach argument around one ownership loop and one answerable ask. | 9 → **10** |

**Install one:** `npx skills add myfeng10/<repo>`

→ [Read the full 19-skill evaluation](skills-evaluation.md)

---

## 🧪 How I Build Skills

I treat a skill as an executable behavior contract, not a prompt snippet.

```mermaid
flowchart LR
    A["Recurring friction"] --> B["One bounded job"]
    B --> C["Frozen scenario + rubric"]
    C --> D["Before run"]
    D --> E["Revise the skill"]
    E --> F["Blind A/B judge"]
    F --> G["Installable behavior"]
```

The current system spans four layers:

| Layer | Skills |
|---|---|
| Memory continuity | `echomem-search` · `echomem-save` · `echomem-login` · `echomem-forget` |
| Self-management and control | `driver-seat-mode` · `next-mode` · `energy-decision-support` · `identity-votes` · `identity-vote-translator` · `weekly-trajectory-review` · `living-archive-entry-builder` |
| Evidence and decisions | `research` · `run-job-search` · `sohk-interviewer` · `strategic-relations` |
| Communication | `draft-x-post` · `write-high-signal-outreach` · `one-shot-positioning` · `smart-people-prep` |

---

## ⚙️ Personal Operating Systems

Some repos are public projects; some are private workspaces. I still treat them as part of my GitHub map because they capture how I work, what I am building toward, and what future agents should not miss.

| Project | What it makes durable |
|---|---|
| [memory-eval-results](https://github.com/myfeng10/memory-eval-results) | Benchmark runs, failure traces, and iteration evidence for memory retrieval and answer quality. |
| [model-knowledge](https://github.com/myfeng10/model-knowledge) | Prompt-change evidence promoted into reusable model insights, failure modes, and validated rules. |
| [thinking-video-pipeline](https://github.com/myfeng10/thinking-video-pipeline) | Raw thinking videos turned into transcripts, edit plans, rough cuts, marker edits, and burned-in captions. |
| ResumeWorkspace (private workspace) | Career evidence, job tracking, role-specific materials, and agent instructions kept in one operating system. |

The thread: turn messy personal context into systems that preserve judgment, reduce repeated effort, and make the next action easier.

---

## 🧠 Memory And Context Work

I work on cross-platform AI memory: capturing real AI conversations and turning them into retrievable context with evidence.

```mermaid
flowchart LR
    A["💬 messy conversations<br/>(ChatGPT · Claude · coding agents)"] --> B["capture"]
    B --> C[("memory<br/>+ evidence")]
    C --> D{"retrieve at<br/>the right time"}
    D --> E["🤖 coding agents / MCP"]
    D --> F["💭 next chat session"]
    D --> G["🎬 content pipeline"]
```

The interesting part is not storing more text. It is making AI able to answer:

> What do we know, why do we know it, when was it true, and what should be reused now?

Current product questions I care about:

- How should AI preserve live context without over-compressing away taste?
- When does a conversation become memory instead of just transcript?
- How can human discussion become implementation context for another agent?
- How should assistants behave when they can actually save, route, and reuse context?
- How do privacy and trust change the design of memory products?

---

## 📄 Research

Co-author on two papers from undergrad research at BU:

- [Explore Reinforced](https://arxiv.org/abs/2412.02016) — equilibrium approximation with reinforcement learning; accepted at GameSec 2025.
- [DebiasPI](https://arxiv.org/abs/2501.18642) — inference-time debiasing of text-to-image generative models by prompt iteration; presented at an ECCV 2024 workshop.

What research left me with: the habit of breaking a fuzzy problem down until it can be measured — which is most of what evaluation work on memory systems actually is.

---

<details>
<summary><b>🌱 Older Roots</b> — undergrad projects (algorithms, planning, data, full-stack)</summary>
<br>

- [CompetitiveProgramming](https://github.com/myfeng10/CompetitiveProgramming) - programming problem solutions and algorithm practice.
- [PlannerX-www](https://github.com/myfeng10/PlannerX-www) - course-planning frontend for student academic planning.
- [HighestTempPrediction](https://github.com/myfeng10/HighestTempPrediction) - weather-data aggregation and prediction.
- SportPal - community sports event web app work.

They are older, but they still matter. The throughline was already there: take something hard to track, and make it legible enough for someone else to use.

</details>

---

## 🚀 Direction

I am building toward AI memory, context engineering, agent workflows, and human-centered tools for self-management and communication.

The long-term bet:

> The best AI products will not just produce more output. They will help people preserve context, make better judgments, and act with clearer timing.
