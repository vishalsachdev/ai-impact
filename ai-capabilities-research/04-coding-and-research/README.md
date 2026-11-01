**[← AI Impact Research](../../)** · **[AI Capabilities Research](../)**

---

# Coding and Research Capabilities

## November 2026 update

*Updated November 1, 2026. The November 2026 section is current. Everything after it is the December 2025 compilation, kept as dated history. Superlatives and words like "latest", "leading" or "now" in that older text describe December 2025.*

- OpenAI audited 138 SWE-bench Verified problems that o3 did not consistently solve and found that 59.4% had material test-design or problem-description flaws, and said it has stopped reporting SWE-bench Verified scores. ([OpenAI, Feb 23, 2026](https://openai.com/index/why-we-no-longer-evaluate-swe-bench-verified/))
- OpenAI's GPT-5.6 launch table (9 Jul 2026) lists SWE-Bench Pro at 64.6% for GPT-5.6 Sol, 80.3% for Claude Mythos 5, 80% for Claude Fable 5 and 69.2% for Claude Opus 4.8 (vendor-reported, harnesses may differ). ([OpenAI, Jul 9, 2026](https://openai.com/index/gpt-5-6/))
- Anthropic's Claude Opus 5.5 page (22 Sep 2026) reports Terminal-Bench 4.0 and FrontierCode v1.1 results in place of SWE-bench Verified, and says Opus 5.5 at default effort scores 54.6% on FrontierCode versus 53.3% for GPT-6 Astra's top score. ([Anthropic, Sep 22, 2026](https://www.anthropic.com/news/claude-opus-5-5))
- METR's Feb 2026 follow-up (57 developers, 800+ tasks, run from Aug 2025) estimates a time change of -18% (interval -38% to +9%, so it includes zero) for 10 returning developers and -4% (interval -15% to +9%) for 47 new developers, against +19% in the early-2025 study. METR calls the data an unreliable signal because of selection effects. ([METR, Feb 24, 2026](https://metr.org/blog/2026-02-24-uplift-update/))
- METR's May 2026 survey of 349 technical workers (Feb to Apr 2026) found a median self-reported 1.4 to 2x change in the value of work from AI tools and a 3x median self-reported speed change, with METR warning that survey self-reports may overstate. ([METR, May 11, 2026](https://metr.org/blog/2026-05-11-ai-usage-survey/))
- Anthropic's Institute reports that as of May 2026 more than 80% of the code merged into Anthropic's codebase was authored by Claude (vendor-reported), and that the typical engineer merged 8 times as much code per day in Q2 2026 as in 2024. ([Anthropic, Jun 4, 2026](https://www.anthropic.com/institute/recursive-self-improvement))
- At Google Cloud Next (22 Apr 2026) Sundar Pichai said 75% of all new code at Google is AI-generated and approved by engineers, up from 50% the previous fall (vendor-reported). ([Google, Apr 22, 2026](https://blog.google/innovation-and-ai/infrastructure-and-cloud/google-cloud/cloud-next-2026-sundar-pichai/))
- Sakana AI's The AI Scientist was published in Nature on 25 Mar 2026: one of three AI-generated manuscripts submitted to an ICLR workshop (acceptance rate 70%) averaged 6.33 from reviewers (6, 7, 6), the other two did not meet the bar, and the paper was withdrawn under a pre-set protocol. ([Nature, Mar 25, 2026](https://www.nature.com/articles/s41586-026-10265-5))

Vendor-reported numbers come from the company named and were not independently checked unless stated. All 23 new findings, with methods, are in **[the November 2026 evidence](./data.md#november-2026-evidence)**.

2 corrections to the December 2025 text on this page are marked in place below, labelled "Corrected November 1, 2026".

---

## Research Question

**What can AI do in software development and research contexts?**

## Hypothesis

AI coding capabilities have reached a threshold where they exceed human expert performance on standard software engineering tasks, fundamentally changing CS education and research methodology.

---

## Key Findings

### 1. SWE-bench Verified (Software Engineering)

**Benchmark**: Real-world GitHub issues requiring multi-file fixes ([Anthropic](https://www.anthropic.com/news/claude-opus-4-5))

| Model | Score | Date | Significance |
|-------|-------|------|--------------|
| Claude Opus 4.5 | **80.9%** | Nov 2025 | First to exceed best human |
| GPT-5.1-Codex-Max | 77.9% | Nov 2025 | Strong competitor |
| Claude Sonnet 4.5 | 77.2% | Nov 2025 | Cost-effective option |
| Gemini 3 Pro | 76.2% | Nov 2025 | Google's entry |

*Corrected November 1, 2026: The human comparison is a separate Anthropic internal take-home exam, not SWE-bench, and is vendor-reported ([Anthropic, Nov 24, 2025](https://www.anthropic.com/news/claude-opus-4-5)).*

### 2. Human Expert Comparison

- Claude Opus 4.5 **exceeds best human candidate** on Anthropic's internal engineering test ([Anthropic](https://www.anthropic.com/news/claude-opus-4-5))
- With parallel test-time compute, matches best-ever human performance
- First documented case of AI exceeding top human software engineer on realistic tasks

### 3. AI Research Tasks

AI models can now perform:
- GPU kernel development
- Reinforcement learning algorithm implementation
- ML model training and tuning
- Research paper implementation
- Experiment design assistance

### 4. Counterpoint: METR Study

**Finding**: Experienced developers 19% slower with AI assistance ([METR](https://metr.org/)) *Corrected November 1, 2026: METR's estimate was 19% longer with a confidence interval of +2% to +39% ([METR, Jul 10, 2025](https://metr.org/blog/2025-07-10-early-2025-ai-experienced-os-dev-study/)). See METR's [February 2026 follow-up](https://metr.org/blog/2026-02-24-uplift-update/) in the update above.*
- 16 veteran open-source programmers
- 246 real-world tasks
- AI assistance reduced speed, not increased it

**Interpretation**: Learning curve and context-switching may offset gains initially

---

## Implications for Universities

### CS Curriculum
- Introductory programming courses need redesign
- Emphasis shifts from syntax to architecture and judgment
- AI collaboration as explicit skill
- Code review and AI output evaluation essential

### Research Methodology
- AI-assisted literature review standard
- Experiment automation increasing
- Reproducibility aided by AI
- Attribution and integrity challenges

### Assessment
- Code-writing exams largely obsolete
- Design and architecture emphasis
- Oral defense of code decisions
- Process documentation required

---

## Related Research Questions

- [RQ01: Real-World Task Performance](../01-real-world-task-performance/) - Professional context
- [RQ05: Agentic Capabilities](../05-agentic-capabilities/) - Autonomous work
- [RQ07: Educational Implications](../07-educational-implications/) - Recommendations

---

## Explore This Research

- **[Detailed Data & Analysis →](./data.md)** — SWE-bench results, research capabilities, and studies
- **[All Sources →](./sources.md)** — Primary and secondary sources with links

---

**[← Previous: Academic Benchmarks](../03-academic-task-benchmarks/)** | **[Next: Agentic Capabilities →](../05-agentic-capabilities/)**
