# Career Growth Companion

**English** | [简体中文](README.zh-CN.md)

### Discover what your everyday work is turning you into.

Explore a few playful questions, discover your career character, understand what work gives and costs you, and choose your next direction. Come back to vent, celebrate, solve a problem, reflect, or prepare for a review or job change.

**Chinese name: 职场大神养成计划** · `career-growth-plan` · [MIT](LICENSE)

> **Career character: Cross-team ambiguity wrangler**
>
> **Official role:** Operations. **Everyday work:** Connecting different teams' understanding.
>
> **Emerging strength:** You turned a requirements disagreement into specific decisions people could confirm.
>
> **Current tension:** Ad hoc coordination takes up time, while you want ownership of a complete piece of work.
>
> **Possible next step:** Discuss a small, bounded project and what existing work it would replace.

*Fictional character card: a playful lens, not a psychological assessment or job title. Its observations need checking against your experience.*

## Where would you like to start?

| Entry | Try saying | Experience |
| --- | --- | --- |
| Discover yourself | “Start my career adventure. What's my career character?” | Light quiz → editable character card → work interpretation → your choice of direction |
| Talk about today | “I need to vent. Please don't give me a plan yet.” | Listening, celebration, problem-solving, or reflection; no compulsory logging |
| Choose a next step | “I want project ownership, but I'm always firefighting.” | A realistic experiment, followed by reflection when you return |

You can also jump straight to “My review is tomorrow; help me draft it.” Serious mode skips playful titles.

**Growth comes from recognizable changes:** handling a disagreement more independently, noticing a warning earlier, or reusing a method. No invented progress, arbitrary XP, streak penalties, or pressure to keep logging.

## Explore before installing

- [English walkthrough](examples/first-session.en.md): discovery, character card, direction, and returning to chat.
- [完整中文体验](examples/first-session.zh-CN.md): the same capabilities in Chinese.
- [Workplace field guides](guides/README.md): three readable guides; no installation needed.
- [Bilingual tryout](examples/tryout.md): experience and feedback checklist.

The guides cover busywork and growth, constant firefighting, and overlooked contributions. They are contextual practical advice, not scientific laws.

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
Use $career-growth-plan. Start with a few fun questions
and help me discover my career character.
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
- [Companion experience](references/companion-experience.md): discovery, characters, daily modes, and growth.
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
