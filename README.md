# Career Growth Companion

**English** | [简体中文](README.zh-CN.md)

### Great at the work, stuck explaining it? Turn everyday tasks into clear KPI accomplishments.

You chase updates, check data, handle exceptions, and help colleagues all month—then your review says only “completed routine work.” This skill helps you explain the problems you handled, the responsibility you took, and the work you delivered.

**Core feature: KPI accomplishment writing.** Paste rough work notes and your assessment criteria to get a contribution-to-KPI table, copy-ready self-review drafts, and a separate evidence checklist. Built for capable people who do strong work but struggle to make their contribution visible in performance reviews.

**Chinese name: 职场大神养成计划** · `career-growth-plan` · [MIT](LICENSE)

> **Raw notes:** “Chased Sales and Support for data each week, produced four reports, asked Support to correct inconsistent refund figures, and removed two duplicate orders.”
>
> **Review wording:** “Coordinated data collection and reconciliation with Sales and Support, delivered four weekly reports this month, identified and coordinated correction of inconsistent refund figures, and removed two duplicate orders.”

*Fictional example. Delivery counts do not establish timeliness or efficiency gains; actual drafts follow the available facts.*

**[See the complete KPI example (Chinese): scattered tasks → four self-assessment entries →](examples/kpi-self-review.zh-CN.md)**

Raw notes → contribution groups → KPI mapping → full self-review → evidence checklist. The case includes a copyable trial prompt.

## Do strong work, and make it visible

Built for people who contribute a great deal but struggle to express it during assessments. Paste rough task lists, weekly updates, or work notes; no character quiz is required.

```text
Use $career-growth-plan to prepare my quarterly KPI self-assessment.
Group my scattered work into contributions, map it to my actual KPIs,
and draft wording I can submit. List missing evidence separately.
My assessment criteria: …
My work notes: …
```

Get a **contribution-to-KPI table, copy-ready accomplishment statements, and a short evidence checklist**. Without company criteria, the skill uses explicitly provisional contribution themes.

For example, “chased three departments for reports, consolidated 12 editions, coordinated corrections to five definition discrepancies, and shared a definitions note” becomes:

> Coordinated weekly report collection across three departments and consolidated 12 reports this quarter; identified and coordinated correction of five reporting-definition discrepancies, then distributed a definitions note to support consistency.

*Figures are fictional examples; actual drafts use only supplied facts.* Strong framing makes the problem, action, and contribution explicit. It preserves actual responsibility, avoids invented improvement percentages, and uses concrete deliverables when outcome metrics are unavailable. Missed targets remain visible with gaps and next steps.

## More ways to support your work

| Entry | Try saying | Experience |
| --- | --- | --- |
| KPI self-assessment | “Turn these scattered tasks into my KPI self-review.” | Raw notes → contribution groups → KPI mapping → self-review and evidence gaps |
| Discover yourself | “Start my career adventure. What's my career character?” | Light quiz → editable character card → work interpretation → your choice of direction |
| Talk about today | “I need to vent. Please don't give me a plan yet.” | Listening, celebration, problem-solving, or reflection; no compulsory logging |
| Choose a next step | “I want project ownership, but I'm always firefighting.” | A realistic experiment, followed by reflection when you return |

**Tools for explaining your work:**

- **Work translator:** “I just chase people for updates. Help me explain what I do.” Playful metaphors can be extravagant; professional statements stay factual.
- **KPI accomplishment lab:** “I do a lot of small tasks but cannot explain my contribution.” Group scattered work, map it to review criteria, and get copy-ready self-assessment wording with evidence gaps listed separately.
- **Conversation practice:** “Play my manager. I want to ask for project ownership.” Practice one turn at a time, pause for help, and finish with one improvement and a fallback.

You can also jump straight to “My review is tomorrow; help me draft it.” Character discovery and playful titles are optional experiences.

**Growth comes from recognizable changes:** handling a disagreement more independently, noticing a warning earlier, or reusing a method. No invented progress, arbitrary XP, streak penalties, or pressure to keep logging.

## Explore before installing

- [English walkthrough](examples/first-session.en.md): work notes, KPI self-review, corrections, shorter drafts, and continuity.
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
Use $career-growth-plan to turn my daily work into a KPI self-review.
Here are my assessment criteria and work notes: …
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
- [KPI accomplishment lab](references/kpi-accomplishments.md): contribution grouping, KPI mapping, formal wording, and evidence gaps.
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
