**[← AI Impact Research](../../)** · **[AI Capabilities Research](../)**

---

# Real-World Task Performance

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

### 3. Speed and Cost Advantage

- AI completes GDPval tasks **100x faster** than human experts ([OpenAI](https://openai.com/index/gdpval/))
- AI completes GDPval tasks **100x cheaper** than human experts ([OpenAI](https://openai.com/index/gdpval/))
- Linear improvement trajectory: performance doubled from GPT-4o to GPT-5 (14 months) ([OpenAI](https://openai.com/index/gdpval/))

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
