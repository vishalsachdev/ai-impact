**[← AI Impact Research](../../)** · **[AI Capabilities Research](../)**

---

# Academic Task Benchmarks

## November 2026 update

*Updated November 1, 2026. The November 2026 section is current. Everything after it is the December 2025 compilation, kept as dated history. Superlatives and words like "latest", "leading" or "now" in that older text describe December 2025.*

- OpenAI reports GPT-6 Astra at 96.0% on GPQA Diamond, and Epoch AI's independent run of GPT-6 Astra gives 0.96 (+/-0.01). ([Epoch AI, undated page, read Nov 1, 2026](https://epoch.ai/data/benchmarks.csv); [OpenAI, GPT-6 Astra page, undated](https://openai.com/index/gpt-6-astra/))
- OpenAI reports GPT-5.2 Thinking scoring 100.0% on AIME 2025 without tools (Dec 11, 2025), so the competition-math benchmark is saturated for vendor-reported results. ([OpenAI, Dec 11, 2025](https://openai.com/index/introducing-gpt-5-2/))
- Anthropic's Fable 5.1 page reports Humanity's Last Exam at 60.9% without tools and 65.0% with tools for Claude Fable 5.1, against 57.8% and 63.8% for Fable 5 and 56.6% and 63.6% for Opus 5. ([Anthropic, Sep 2026](https://www.anthropic.com/claude-fable-and-mythos-5-1))
- The Humanity's Last Exam owner site lists a Nature publication (Jan 28, 2026, Nature 649, 1139-1146) and the release of HLE-Diamond on Sept 22, 2026 as a migration path 'once frontier AI begins to hit the noise ceiling on the original HLE dataset'; its own leaderboard table still shows Gemini 3 Pro at 38.3 as top. ([CAIS and Scale AI, Sep 22, 2026](https://lastexam.ai))
- OpenAI's GPT-6 Astra page says Astra scored 99.9% on ARC-AGI-3 and 98% on FrontierMath Tier 4, while its GPT-5.6 page (Jul 9, 2026) lists ARC-AGI-3 at 7.78% for GPT-5.6 Sol and 0.43% for GPT-5.5. ([OpenAI, undated page, read Nov 1, 2026](https://openai.com/index/gpt-6-astra/))
- Stanford's 2026 AI Index reports frontier models gained 30 percentage points in a single year on Humanity's Last Exam, and that a review found invalid question rates from 2% on MMLU Math to 42% on GSM8K. ([Stanford HAI, undated page, read Nov 1, 2026](https://hai.stanford.edu/ai-index/2026-ai-index-report/technical-performance))

Vendor-reported numbers come from the company named and were not independently checked unless stated. All 9 new findings, with methods, are in **[the November 2026 evidence](./data.md#november-2026-evidence)**.

2 corrections to the December 2025 text on this page are marked in place below, labelled "Corrected November 1, 2026".

---

## Research Question

**How do AI models perform on academic and intellectual tasks relevant to universities?**

## Hypothesis

AI models are achieving expert-level performance on many academic tasks, requiring universities to reconsider assessment methods, learning objectives, and the nature of expertise development.

---

## Key Findings

### 1. Graduate-Level Science (GPQA Diamond)

**Benchmark**: PhD-level questions in physics, biology, and chemistry ([Google](https://blog.google/products/gemini/gemini-3/))
- **Gemini 3 Deep Think**: 93.8%
- **Human PhD students**: ~65-70% (in their domain) *Corrected November 1, 2026: The GPQA paper gives 65% for experts (74% after discounting clear mistakes) and 34% for skilled non-experts, on the full question set rather than Diamond ([GPQA paper](https://arxiv.org/pdf/2311.12022)).*
- **Significance**: AI exceeds average PhD student in multi-domain science *Corrected November 1, 2026: the baselines behind this comparison are corrected above.*

### 2. Mathematics (AIME 2025)

**Benchmark**: [American Invitational Mathematics Examination](https://www.maa.org/math-competitions/aime) ([Google](https://blog.google/products/gemini/gemini-3/))
- **Gemini 3**: 95% raw, 100% with code execution
- **Human qualification threshold**: ~50%
- **Significance**: Near-perfect on competition-level math

### 3. Frontier Knowledge (Humanity's Last Exam)

**Benchmark**: Questions at the edge of human knowledge ([Google](https://blog.google/technology/google-deepmind/gemini-model-thinking-updates-march-2025/))
- **Gemini 2.5 Pro**: 18.8% (without tools)
- **Expert humans**: ~40-50% *Corrected November 1, 2026: The expert baseline here could not be found in the Humanity's Last Exam paper. Do not cite it.*
- **Significance**: AI approaching half of frontier knowledge performance *Corrected November 1, 2026: the expert baseline is corrected above, and newer scores are in the update.*

### 4. Undergraduate Coursework

**Estimated AI Performance by Subject**:
- STEM problem sets: 80-95%
- Essay writing: 70-85%
- Research synthesis: 75-90%
- Foreign language: 70-85%
- Creative work: 50-70%

---

## Implications for Universities

### Assessment Redesign
- Take-home exams fundamentally compromised
- Proctored exams gain importance
- Process-based assessment essential
- Oral examinations more reliable

### Learning Objectives
- Knowledge recall less valuable
- Critical thinking and synthesis emphasized
- AI collaboration as new skill
- Meta-cognitive skills essential

### Course Design
- AI-augmented assignments normalized
- Explicit AI policy required for every course
- Focus on what AI cannot (yet) do

---

## Related Research Questions

- [RQ01: Real-World Task Performance](../01-real-world-task-performance/) - Professional context
- [RQ04: Coding and Research](../04-coding-and-research/) - Technical capabilities
- [RQ07: Educational Implications](../07-educational-implications/) - Recommendations

---

## Explore This Research

- **[Detailed Data & Analysis →](./data.md)** — Full benchmark results and performance data
- **[All Sources →](./sources.md)** — Primary and secondary sources with links

---

**[← Previous: Capability Trajectory](../02-capability-trajectory/)** | **[Next: Coding & Research →](../04-coding-and-research/)**
