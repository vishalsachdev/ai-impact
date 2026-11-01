**[← AI Impact Research](../../)** · **[AI Capabilities Research](../)**

---

# Real-World Task Performance

## November 2026 update

*Updated November 1, 2026. The November 2026 section is current. Everything after it is the December 2025 compilation, kept as dated history. Superlatives and words like "latest", "leading" or "now" in that older text describe December 2025.*

- OpenAI's GPT-5.5 launch table reports GDPval wins-or-ties of 84.9% for GPT-5.5, 83.0% for GPT-5.4, 82.3% for GPT-5.5 Pro, 82.0% for GPT-5.4 Pro, 80.3% for Claude Opus 4.7 and 67.3% for Gemini 3.1 Pro (Apr 23, 2026); the OpenAI launch pages checked after this one report other benchmarks. ([OpenAI, Apr 23, 2026](https://openai.com/index/introducing-gpt-5-5/))
- From GPT-5.6 (Jul 9, 2026) OpenAI's launch table reports GDPval-AA v2, an Artificial Analysis Elo scale, instead of the GDPval win-or-tie rate: GPT-5.6 Sol 1,747.8, Claude Fable 5 1,759.6, GPT-5.5 1,493.7, Gemini 3.1 Pro Preview 962.3. ([OpenAI, Jul 9, 2026](https://openai.com/index/gpt-5-6/))
- Anthropic reports Claude Opus 5.5 at 1846 Elo on GDPval-AA v2.1 at max effort, against 1735 for Fable 5.1 and 1708 for Opus 5; the same table lists GPT-6 Astra at 1542 and GPT-5.6 Sol at 1588 (Sep 22, 2026). ([Anthropic, Sep 22, 2026](https://www.anthropic.com/claude-opus-5-5))
- Scale AI's Remote Labor Index (240 real freelance projects, 230 held private) lists Claude Opus 5.5 first at a 21.25% automation rate, with GPT 6 Astra at 20.83%, Fable 5.1 at 17.92% and Gemini Argon 4 at 17.08%. ([Scale AI, undated page, read Nov 1, 2026](https://www.scale.com/leaderboard/rli))
- At launch the Remote Labor Index top agent (Manus) completed only 2.5% of the projects to a client-acceptable standard, which Scale describes as near zero; later rows (Opus 5.5 21.25%) show the rate rising but still below one in four. ([Scale AI, undated page, read Nov 1, 2026](https://www.scale.com/leaderboard/rli))
- Anthropic's own Opus 5.5 launch page says benchmark margins at current capability levels are a less reliable guide to real-world differences, and that the gap between Opus 5.5 and Fable 5.1 is narrower in its own use than the scores suggest. ([Anthropic, Sep 22, 2026](https://www.anthropic.com/claude-opus-5-5))

Vendor-reported numbers come from the company named and were not independently checked unless stated. All 11 new findings, with methods, are in **[the November 2026 evidence](./data.md#november-2026-evidence)**.

3 corrections to the December 2025 text on this page are marked in place below, labelled "Corrected November 1, 2026".

---

## Research Question

**How well do AI models perform on authentic professional tasks across occupations?**

## Hypothesis

AI models are approaching or exceeding expert-level performance on a significant portion of economically valuable professional tasks, with implications for workforce preparation and curriculum design.

---

## Key Findings

### 1. GDPval Benchmark Overview

OpenAI's [GDPval](https://openai.com/index/gdpval/) (September 2025) provides the most comprehensive evaluation of AI on real-world professional tasks:

- **Scale**: 1,320 tasks across 44 occupations in 9 GDP-dominant U.S. sectors ([OpenAI](https://openai.com/index/gdpval/))
- **Methodology**: Industry professionals with ~14 years average experience create tasks
- **Evaluation**: Blinded pairwise comparisons by occupational experts
- **Deliverables**: Authentic outputs (presentations, spreadsheets, briefs, CAD files, audio/video)

### 2. Cross-Lab Model Performance

On the 220-task GDPval gold set:

| Model | Strength | Expert Parity Rate |
|-------|----------|-------------------|
| Claude Opus 4.1 | Aesthetics (formatting, layout) | Leading |
| GPT-5 | Accuracy (domain knowledge) | Strong |
| GPT-5 Thinking | Balanced | Moderate |
| Gemini 3 | Varies | 33-50% |
| Grok | Varies | 20-33% |

*Corrected November 1, 2026: The GDPval paper tested Gemini 2.5 Pro and Grok 4, not Gemini 3, and these ranges could not be found in it. Do not cite them.*

### 3. Speed and Cost Advantage

- AI completes GDPval tasks **100x faster** than human experts ([OpenAI](https://openai.com/index/gdpval/)) *Corrected November 1, 2026: The 100x is a naive ratio. For GPT-5 the paper gives 90x speed and 474x cost before human review, and 1.12x faster and 1.18x cheaper when a person reviews once and redoes failures ([GDPval paper](https://cdn.openai.com/pdf/d5eb7428-c4e9-4a33-bd86-86dd4bcf12ce/GDPval.pdf)).*
- AI completes GDPval tasks **100x cheaper** than human experts ([OpenAI](https://openai.com/index/gdpval/))
- Linear improvement trajectory: performance doubled from GPT-4o to GPT-5 (14 months) ([OpenAI](https://openai.com/index/gdpval/)) *Corrected November 1, 2026: The paper's win rates are 12.5% for GPT-4o and 39.0% for GPT-5 ([GDPval paper](https://cdn.openai.com/pdf/d5eb7428-c4e9-4a33-bd86-86dd4bcf12ce/GDPval.pdf)). The 14-month interval is not stated there.*

### 4. Task Categories Where AI Excels

- Document formatting and layout
- Data analysis and spreadsheet work
- Research synthesis and summarization
- Technical writing and documentation
- Routine professional communications

### 5. Task Categories Where Humans Lead

- Novel strategic decisions
- Interpersonal and client-facing judgment
- Tasks requiring physical presence
- Highly context-dependent work
- Creative direction (vs. execution)

---

## Implications for Universities

### Curriculum Design
- Professional skills courses need AI-augmentation focus
- Emphasis on judgment, creativity, and interpersonal skills
- Technical execution skills less differentiated

### Workforce Preparation
- Students need experience with AI-augmented workflows
- Critical evaluation of AI outputs becomes core skill
- Domain expertise remains valuable for direction-setting

### Assessment
- Professional task simulations may need redesign
- Process and reasoning become more important than deliverable
- Oral defense and live demonstration gain importance

---

## Data Quality Notes

- GDPval is the most rigorous benchmark for professional tasks to date
- Open-sourced gold set enables independent verification
- Task construction by experienced professionals reduces synthetic bias
- Blinded evaluation reduces model-specific grading bias

---

## Related Research Questions

- [RQ02: Capability Trajectory](../02-capability-trajectory/) - Improvement rates over time
- [RQ04: Coding and Research](../04-coding-and-research/) - Technical task performance
- [RQ07: Educational Implications](../07-educational-implications/) - What universities should do

---

## Explore This Research

- **[Detailed Data & Analysis →](./data.md)** — Full benchmarks, model comparisons, and implications
- **[All Sources →](./sources.md)** — Primary and secondary sources with links

---

**[Next: Capability Trajectory →](../02-capability-trajectory/)**
