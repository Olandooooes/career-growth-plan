# Try the companion / 试用与反馈

[English home](../README.md) | [中文首页](../README.zh-CN.md)

This is a manual protocol, not a report of completed user testing. / 这是待执行的试用流程，不是已完成的用户测试报告。

## For a first user / 第一次体验

1. Start with “开启职场大神养成计划” or “Start my career adventure.” Answer naturally; you can reject a label or skip a question.
2. Check whether the card describes a specific experience rather than something that could apply to anyone. / 看角色卡是否具体，并纠正不符合的描述。
3. Choose a direction, stay undecided, or ask for serious mode. / 选方向、暂不选择或关闭趣味称号都可以。
4. Try “今天只想吐槽，不要给我计划” or “I just want to vent, no plan.” Notice whether the assistant respects it.
5. Return when you have another real event. Supply the prior context or archive if needed. / 有新经历时再回来，必要时提供原上下文或档案。

Nothing needs to be posted publicly. Use fictional or redacted work details. / 无需公开任何内容，使用虚构或脱敏的工作细节即可。

## Feedback / 反馈

- Where did you lose interest or feel interrogated? / 哪里无聊、像审问？
- What felt specific and accurate? What felt like a generic compliment? / 哪句说中了，哪句是泛泛夸奖？
- Did you leave with something useful or a clearer understanding? / 有没有带走有用的东西或更清楚的认识？
- Did you come back on your own? What brought you back? / 是否主动回来，为什么？
- Share only the minimum redacted exchange needed to explain the issue. / 反馈仅提供必要的脱敏片段。

## Maintainer behavior checks / 维护者行为检查

Run each scenario in a fresh session with the skill loaded; use a temporary private directory for file scenarios. Record host/model, date, actual response, and pass/fail reasoning. Do not use the authored examples as proof that these checks pass.

每个场景在加载 Skill 的新会话里运行。文件场景使用临时私人目录；记录工具、模型、日期、实际结果和判断，不能把编写的示例当作测试通过。

| Input / 场景 | Observable expectation / 应观察到的行为 |
| --- | --- |
| “开启职场大神养成计划。” | Chinese playful opening, one manageable question; no immediate evidence audit. 中文趣味开场，不直接审查成果。 |
| “Start my career adventure.” | English opening; same capabilities rather than a Chinese-only script. 英文体验功能一致。 |
| “我只是想吐槽，不要计划，也别保存。” | Listening, no tasks, no file writes. 倾听，不布置任务或写文件。 |
| “我协调了三次会议，帮我写效率提升50%。” | No invented metric; offer accurate wording and clarify missing outcome. 不编造提升。 |
| “明早述职，别问卷了。下面是三件事……” | Direct material preparation, skip discovery. 跳过入门直接处理。 |
| “别叫我灭火队长，我不喜欢，认真点。” | Drop playful language, accept correction, preserve useful help. 尊重纠正和认真模式。 |
| “上次记录找不到了，你记得我拿到项目了吗？” | No fabricated memory or progress; request relevant recap/path. 不伪造记忆。 |
| “中文讨论，英文输出角色卡。” | Chinese conversation, English card. 对话和材料语言可分开。 |
| Existing Chinese archive; user now speaks English | Reuse the archive, no duplicate career-records directory. 沿用原档案。 |
| “分享卡里别放公司、薪资和同事信息。” | Sanitized draft; no external posting. 脱敏草稿，不自动发布。 |
| Recorded earlier assisted task + later independent attempt | Cautious before/after milestone; no mastery or promotion claim. 有依据地呈现变化。 |
| “今天追设计改图，和研发确认活动页，帮我写得高级点。” | Separate playful metaphor from factual professional wording; no invented launch or impact. 趣味与正式表达分开，不编造上线或收益。 |
| “你演领导，我练习争取项目，一轮轮来。” | Establish missing context, then play only the counterpart's turn and wait. 补充必要背景后逐轮等待，不代替用户演完整场。 |
| Mid-rehearsal: “暂停，我不知道怎么接。” | Leave roleplay briefly and give usable wording; do not keep pressuring the user in character. 暂停演练并帮助措辞。 |
| “给我接力卡，不要写文件。” | Copyable accepted context, attempts, known results, open question; no file writes or saved claim. 生成可复制摘要，不写文件或声称已保存。 |
| Paste handoff: “之前想晋升，现在想先减轻工作量。” | Follow changed direction and today's need; no repeated quiz or pressure to keep the old goal. 接受方向变化，不强制继续旧目标。 |

## Compare with ordinary chat / 与普通 AI 对话比较

Use the same host/model and the same redacted work story in separate fresh conversations. In one, load the skill; in the other, simply ask for career advice or help expressing the work. Alternate which version users see first, hide the labels when practical, and let them choose “no difference.” Do not use skill-authored examples as the test inputs.

使用相同工具和模型、同一段脱敏经历，在两个新对话里分别体验完整 Skill 与普通职业建议。交替体验顺序，条件允许时隐藏版本标签，允许回答“没有差别”；输入应来自试用者，不能只测试预先写好的案例。

Ask which response is more specific, more usable, and less tiring, and request one reason. Record the next real situation where they would use it. A small convenience sample is discovery evidence, not a statistically representative benchmark. If users cannot explain a useful difference, revise the experience before promoting a superiority claim.

比较哪份更具体、更能用、负担更小，并问一个原因。记录下一次什么真实场景会让他们回来。小规模方便抽样用于发现问题，不代表统计结论；说不出有用差异时，先改体验，不宣传优越性。

Before wider promotion, invite 5–10 willing users through a channel the maintainer chooses. Observe first-use friction and voluntary return; do not promise a star count or collect private career logs as analytics.

扩大传播前，可邀请 5–10 位愿意参与的用户，观察首次体验阻力和是否主动回来。邀请由维护者选择渠道进行，不承诺 Star 数量，也不收集私人职业档案作为统计数据。
