# Research Notes：AI Outbound、GTM Engineering 与 FDE

## 研究结论

### 1. Relevance 高于 personalization

机械感通常不是因为 AI 用词不够自然，而是没有 legitimate reason to reach out。

身份式 personalization：

- 对方是 founder；
- 对方在某个行业；
- 对方最近融资；
- 对方写过一篇 AI 文章。

这些只能帮助 qualification，不能自动构成联系理由。

真正的 relevance 来自：

- 对方表达了一个 EchoMem 可能解决的 pain；
- 对方正在使用临时 workaround；
- 对方在寻找方案；
- 对方刚进入一个会放大该问题的新阶段；
- 对方主动邀请反馈或讨论。

### 2. 一条消息一个 signal

AI 应该先筛选 signal，再研究 “why now”，最后才生成内容。不要把多条公开信息拼成一段证明自己做过功课的摘要。

### 3. Observation 后面必须有新问题

只引用 hook，不复述全文。Hook 的作用是说明为什么联系，下一句话应该提出我们的 observation 或问题。

### 4. Human approval 仍然重要

AI 适合 research、qualification 和 draft。错误的个性化比普通模板更糟，因为它会让收件人立刻把发送者归类成 bot。真人已经回复以后，human review 更重要，不能批量自动回复。

### 5. FDE 的 offer 更适合 EchoMem

FDE 的核心不是卖一个标准 demo，而是进入客户真实环境：

1. discovery；
2. 选择一个小 workflow；
3. 使用真实 context 试验；
4. 部署；
5. 关闭反馈循环；
6. 把反复出现的问题带回产品。

EchoMem 早期应该邀请对方共同测试一个 workflow，而不是只邀请对方“看产品”。

## 来源

### GTM engineering 与 signal-based outbound

- Shawn Tenam：Qualification → Research the “why now” → Content  
  https://www.linkedin.com/posts/shawntenam_first-it-was-gtm-engineer-now-its-gtm-alpha-activity-7322615696557858817-qIrQ

- Common Room：job listing、social engagement、job change 等 signal  
  https://www.commonroom.io/blog/3-signals-every-sales-rep-should-leverage/

- Common Room：身份式或个人爱好式 personalization 容易显得刻意和机械  
  https://www.commonroom.io/blog/winning-modern-buyers-requires-a-person-first-approach/

- Unify：one signal per message、observation-based opening、严格 prompt constraint  
  https://www.unifygtm.com/explore/ai-outreach-without-sounding-like-ai

- Unify：signal-triggered warm outbound 与 human approval  
  https://www.unifygtm.com/explore/warm-outbound-examples

- Lily Sloma：关键问题是哪些 signal 在 intent 明显以前就存在，以及什么可以自动化而不破坏人性  
  https://www.linkedin.com/posts/liliia-sloma_everyones-suddenly-a-gtm-engineer-but-activity-7467874637771681792-3Xh9

### 关于 AI outreach 机械感的公开讨论

- Personalization 不等于 intent；错误的 hyper-personalization 更糟  
  https://www.reddit.com/r/coldemail/comments/1qm7u58/why_personalization_isnt_fixing_your_reply_rates/

- 如果 signal 没有形成 legitimate reason to reach out，消息仍然像自动化  
  https://www.reddit.com/r/SaaS/comments/1t76e7i/i_think_ai_outbound_is_quietly_making_founders/

- “Saw you’re a founder” 等 AI 开场已经成为明显负面信号  
  https://www.reddit.com/r/SaaS/comments/1t4ybxj/i_received_40_cold_emails_this_week_literally_all/

- 一条错误但自信的 opening，比普通 opening 更容易暴露 bot；真人回复后必须加强人工审核  
  https://www.reddit.com/r/coldemail/comments/1t6zlw7/i_built_an_ai_system_to_personalize_cold_outreach/

### FDE

- FDE Playbook：discovery、MVP scope、real data prototype、evaluation、production、feedback loop  
  https://fde.academy/blog/forward-deployed-engineer-playbook

- FDE 的价值是缩短“模型能工作”和“客户业务实际使用”之间的距离  
  https://fde.academy/blog/why-every-ai-startup-needs-a-forward-deployed-engineer

### EchoMem Group 相关公开 pain

- lowtouch.ai：Claude Code 全公司 adoption 后，context management 成为最大投入  
  https://www.lowtouch.ai/how-we-rolled-out-claude-code-across-an-entire-company/

- Warmly：多人各自维护 `CLAUDE.md`、通过 Slack DM 复制 prompt，并自建 memory loop  
  https://www.warmly.ai/p/blog/claude-code-best-practices

- Steady：个人 agent 提高输出，但人变成 agent 与团队之间的 context conduit  
  https://runsteady.com/blog/everyone-on-the-team-is-running-agents-nobodys-running-the-same-plan/

- 多人使用 Claude Code 的实际工作流讨论  
  https://www.reddit.com/r/ClaudeCode/comments/1rhswxk/how_are_you_actually_using_claude_code_as_a_team/

- 多个 Claude Code session 共用 memory 后出现的真实失败  
  https://www.reddit.com/r/ClaudeCode/comments/1v3q7cx/ive_had_34_claude_code_sessions_sharing_one/

## 后续研究方向

- 专门搜索公开抱怨 `stakeholder check-in` 与 agent context 的人。
- 搜索 AI-native startup 的 engineering leader，而不是泛 CTO 名单。
- 搜索已经维护 session summary、shared `CLAUDE.md`、agent handoff 文档的人。
- 搜索 privacy、安全或权限阻止其采用 shared memory 的团队。
- 从近期 Reddit/Hacker News comment 中找正在寻求实际解决方案的人。

