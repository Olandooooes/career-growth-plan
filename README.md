# Career Growth Companion

**English** | [简体中文](README.zh-CN.md) · [Try it](examples/start-here.en.md) · [See a case](examples/everyday-work-to-materials.zh-CN.md) · [Read actual tests](tests/kpi-session-report.zh-CN.md)

## Good at your work, unsure how to explain its value?

**Turn scattered daily work into truthful accomplishments, then into the material you need.**

![Cartoon: scattered work notes become clear contributions and useful work documents](assets/illustrations/work-to-accomplishments.png)

Chasing updates, checking data, answering questions, handling exceptions—then calling it all “small tasks”? This skill helps explain your responsibilities, the problems you handled, and what you delivered. Built for people who do strong work but struggle to summarize it.

**Daily notes → truthful contributions → material for your chosen use.** No KPI form, impressive metrics, or complete profile required.

This is a work-writing companion loaded into an AI host. It produces text drafts and evidence prompts.

## What can it help with?

| Your need | What you get |
| --- | --- |
| “I do lots of small tasks. What counts?” | Contributions grouped by theme, preserving personal responsibility, team results, and open items |
| “I need a weekly update or work summary.” | A clear summary of delivery and pending work instead of a daily task diary |
| “How do I write my KPI self-review?” | Wording mapped to actual criteria, with material evidence gaps; concise prose when requested, detailed tables when useful |
| “I need a performance-review narrative.” | Six parts: responsibilities, actions, results, personal growth, work improvements, and confirmed plans; optional proportions |
| “I'm preparing for promotion, a resume, or an interview.” | Relevant real experiences with clear personal contributions and evidence |
| “I want to rehearse a conversation with my manager.” | One-turn-at-a-time practice, with the option to pause for help |

Reflection, venting, career direction, and optional character discovery remain available. A character quiz is not required before organizing work.

## How to use it: share a few tasks, then choose a purpose

![Cartoon: share work notes, check the facts with a companion, and choose a document](assets/illustrations/three-step-start.png)

**1. Start.** After installing and loading the skill, say:

```text
Use $career-growth-plan. Help me organize my recent work.
```

**2. Share rough notes.** Get useful accomplishment wording before a long intake:

```text
I chased three teams for materials and combined a weekly report.
I found five inconsistent figures and contacted the owners to correct them.
I wrote and shared a systems FAQ, but don't know whether anyone used it.
```

**3. Adapt it.** Check the facts, then ask for one of these:

- “Make it a short weekly update for my manager.”
- “Write one paragraph for these KPI criteria. Don't claim attainment without evidence.”
- “Use the six-part review structure. Confirm next steps with me before including them.”

Reuse the same notes across formats without repeating your background. If your purpose is already clear, include it in the first request.

**Not installed yet?** [Copy a standalone tryout prompt](examples/start-here.en.md) or read the [first-use walkthrough](examples/first-session.en.md). Installation follows below.

## What changes in the output?

| Rough notes | Truthful accomplishment wording |
| --- | --- |
| “Chased three teams, combined a report, got five inconsistent numbers fixed.” | “Coordinated materials from three teams and consolidated a weekly report, identified five data discrepancies, and contacted the owners to correct them.” |
| “Answered systems questions and shared an FAQ. Don't know who read it.” | “Responded to colleagues' systems questions and compiled and shared an FAQ for team reference.” |

*Fictional examples. Clearer wording does not establish on-time delivery, improved efficiency, or FAQ adoption.*

You leave with **a draft you can check, edit, and use**, clearer personal contributions, and the important gaps behind unsupported claims.

- Participation stays distinct from leadership; team outcomes stay distinct from personal work.
- Personal growth needs before/after evidence. An FAQ deliverable does not establish better process outcomes.
- Unconfirmed plans stay outside submission text. Unknown outcomes, missed targets, and pending work remain visible.

Check facts before formal use. No promotion, pay, hiring, or performance-rating outcome is promised.

## Read a case, then inspect actual tests

| Explore | Link |
| --- | --- |
| From the opening to work notes | [First-use walkthrough](examples/first-session.en.md) |
| Reuse one story across formats | [Accomplishments → weekly update → concise KPI case (Chinese)](examples/everyday-work-to-materials.zh-CN.md) |
| Personal growth versus work improvements | [Six-part review case (Chinese)](examples/six-part-review.zh-CN.md) |
| A fuller KPI scenario | [KPI self-review case (Chinese)](examples/kpi-self-review.zh-CN.md) |
| Actual loaded-skill behavior | [Independent-session report: inputs, outputs, issues, and retests (Chinese)](tests/kpi-session-report.zh-CN.md) |

As of October 16, 2026, the report records nine independent sessions and 19 responses covering onboarding, accomplishments, weekly updates, KPIs, and six-part reviews. Tests found and prompted fixes for unconfirmed future commitments and invented tracking artifacts; corresponding later runs did not repeat them. Review tests cover plan confirmation and missing evidence. **These are bounded runs, not proof of cross-model reliability or long-term user outcomes.**

Authored fictional cases and actual execution records are labeled separately. Cartoons explain the workflow; they are not product screenshots or test evidence.

Also explore the [workplace field guides](guides/README.md) and [manual tryout checks](examples/tryout.md).

## Install and start

This is an instruction-based Agent Skill, **not a standalone app**. It requires an AI host that can load skills. The baseline experience uses text/Markdown cards, not guaranteed clickable controls or animations. The package needs no API key, server, or additional runtime; the host's own access and usage costs still apply. File tools are needed to save an archive.

### In Codex

Ask the built-in installer:

```text
Use $skill-installer to install the skill at the root of
https://github.com/Olandooooes/career-growth-plan
```

Then ask:

```text
Use $career-growth-plan to organize my everyday work into truthful accomplishments.
Here are a few things I did: …
```

For manual installation on macOS/Linux with Git, clone into the user skills directory documented by Codex:

```sh
mkdir -p "$HOME/.agents/skills"
git clone https://github.com/Olandooooes/career-growth-plan.git \
  "$HOME/.agents/skills/career-growth-plan"
```

Use **one installation method**. If a copy already exists, update that copy rather than installing a duplicate. Older or customized hosts may use a different skills directory. See the [official skill documentation](https://learn.chatgpt.com/docs/build-skills) for current discovery locations; restart the host if the skill does not appear.

### Other skill-capable hosts

Follow your host's installation instructions and keep `SKILL.md`, `references/`, and `agents/` together. Native integration has not been tested across all hosts. For a one-off trial, ask your assistant to read a local checkout's `SKILL.md` and relevant references; this does not install the skill or grant permanent memory.

## Speak your language

One shared English instruction set serves both English and Chinese conversations. The assistant should follow your language or explicit preference:

```text
开启职场大神养成计划。帮我整理最近的工作，为转正述职做准备。
```

```text
Let's discuss this in English, but write my final self-review in Chinese.
```

Workplace terminology should fit your context. A conversation in Chinese does not establish your country or employer's promotion rules. Language behavior depends on the host model and should be checked in actual use.

## Records belong to you

When you request saving and file tools are available, the assistant maintains a local Markdown archive in a suitable private workspace, separate from this public repository. It reports the path after writing. Existing `职业成长档案/` records are preserved; switching languages does not create a new archive.

Without file tools, you get copyable text and an explicit “not saved” status. There is no built-in background collection, automatic reminder, or account sync. This skill adds no telemetry or backend, but content you discuss is still processed under your AI host's data settings. Review and redact employer information before sharing it.

For continuity without persistent memory, ask for a handoff card: background you accept, your direction, actions attempted, and an open question. Paste it into your next chat. The assistant should not claim that a copyable card has been saved.

## Project files

- [SKILL.md](SKILL.md): shared behavior and language policy.
- [Companion experience](references/companion-experience.md): optional character discovery, daily modes, and growth.
- [Work lab](references/work-lab.md): work translation and turn-by-turn rehearsal.
- [Work accomplishments](references/work-accomplishments.md): recover truthful contributions and adapt to the chosen use.
- [KPI self-assessment scenario](references/kpi-accomplishments.md): contribution grouping, KPI mapping, formal wording, and evidence gaps.
- [Goals and outputs](references/goals-and-outputs.md): reviews, promotion, interviews, and growth actions.
- [Local records](references/local-records.md): archive locations, evidence, and incremental updates.
- [UI metadata](agents/openai.yaml): display name and suggested starting prompt.
- [English example](examples/first-session.en.md) / [中文案例](examples/first-session.zh-CN.md): fictional conversations illustrating the intended experience.

## Status and contributions

If a trial helped you explain your work or practice a conversation, consider **starring the repository** to find it again. You can also share a trial link with someone facing a similar situation. All content is available without starring.

This is an early version. Examples illustrate intended behavior; they are not benchmark results, user testimonials, or proof of career outcomes. No promotion, hiring, or salary outcome is promised.

**[Tell us what felt useful—or where you wanted to leave](https://github.com/Olandooooes/career-growth-plan/issues/new?template=experience.yml).** Share only redacted content you are comfortable making public; employer names, salary, and private archives are unnecessary.

Issues and pull requests in **English or Chinese** are welcome. The most useful feedback includes a redacted prompt, what happened, and what you expected. Do not submit real private career archives. When changing behavior or installation steps, update both READMEs; keep one authoritative `SKILL.md` rather than separate language forks.

## Inspiration and license

The idea grew from lightweight work reflection and the [brag document](https://jvns.ca/blog/brag-documents/) practice. [HowToLiveBetter](https://github.com/eternity4719/HowToLiveBetter) inspired packaging a useful method as a skill. This is an independent project, not an endorsement by those authors.

Released under the [MIT license](LICENSE).
