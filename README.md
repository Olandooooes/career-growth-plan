# Career Growth Companion

**English** | [简体中文](README.zh-CN.md)

### Turn everyday work into evidence of your growth.

Busy all week, but unsure what belongs in your performance review or resume?
Start with one real experience. This AI skill helps you find your contribution, capture a reusable lesson, and choose a practical next step.

**Chinese name: 职场大神养成计划** · Skill ID: `career-growth-plan` · [MIT license](LICENSE)

## A small conversation, a useful outcome

> **You:** I spent the day chasing design and engineering. The requirements changed three times. I don't feel like I achieved anything.
>
> **Companion:** What was blocking them, and what did you personally do to move it forward?
>
> **You:** They disagreed about the requirements. I listed the unresolved decisions and got both sides to confirm the scope. Engineering then resumed implementation. We haven't shipped yet.
>
> **Accomplishment:** Documented unresolved requirements and coordinated scope confirmation between design and engineering, allowing implementation to resume. Final delivery impact is still unconfirmed.
>
> **Next experiment:** Try that decision list at the next handoff and observe whether disagreements surface earlier.

*Fictional illustration, not a real user result or a guaranteed model response.*

No invented “30% efficiency improvement”. No long questionnaire before the first useful draft. Read the [complete English example](examples/first-session.en.md) or [中文案例](examples/first-session.zh-CN.md).

## What it helps you do

| When you need help | What you get |
| --- | --- |
| “I can't remember what I accomplished.” | A conversation that recovers a factual accomplishment card |
| “Help me log today's work.” | A record of actions, outcomes, open questions, and lessons |
| “Help me reflect on this week.” | Project-level patterns and a useful next step from available records |
| “My review or promotion discussion is coming up.” | A draft grounded in your contribution and actual criteria |
| “I'm preparing for a job change.” | Resume material and interview stories based on real experience |
| “What should I work on next?” | A small growth experiment with an observable outcome |

Coordination, maintenance, troubleshooting, and failed attempts count too. Playful titles are optional and stay out of formal materials.

## Install and start

This is an instruction-based Agent Skill, **not a standalone app**. It requires an AI host that can load skills. The package needs no API key, server, or additional runtime; the host's own access and usage costs still apply. File tools are needed to save an archive.

### In Codex

Ask the built-in installer:

```text
Use $skill-installer to install the skill at the root of
https://github.com/Olandooooes/career-growth-plan
```

Then ask:

```text
Use $career-growth-plan. My performance review is in two months.
Help me turn one recent work experience into an accomplishment card.
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

## Project files

- [SKILL.md](SKILL.md): shared behavior and language policy.
- [Goals and outputs](references/goals-and-outputs.md): reviews, promotion, interviews, and growth actions.
- [Local records](references/local-records.md): archive locations, evidence, and incremental updates.
- [UI metadata](agents/openai.yaml): display name and suggested starting prompt.
- [English example](examples/first-session.en.md) / [中文案例](examples/first-session.zh-CN.md): fictional conversations illustrating the intended experience.

## Status and contributions

This is an early version. Examples illustrate intended behavior; they are not benchmark results, user testimonials, or proof of career outcomes. No promotion, hiring, or salary outcome is promised.

Issues and pull requests in **English or Chinese** are welcome. The most useful feedback includes a redacted prompt, what happened, and what you expected. Do not submit real private career archives. When changing behavior or installation steps, update both READMEs; keep one authoritative `SKILL.md` rather than separate language forks.

## Inspiration and license

The idea grew from lightweight work reflection and the [brag document](https://jvns.ca/blog/brag-documents/) practice. [HowToLiveBetter](https://github.com/eternity4719/HowToLiveBetter) inspired packaging a useful method as a skill. This is an independent project, not an endorsement by those authors.

Released under the [MIT license](LICENSE).
