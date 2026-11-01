**← [Back to Overview](./README.md)** | **[Sources →](./sources.md)**

---

# Academic Task Benchmarks: Detailed Data

## November 2026 evidence

*Updated November 1, 2026. The November 2026 section is current. Everything after it is the December 2025 compilation, kept as dated history. Superlatives and words like "latest", "leading" or "now" in that older text describe December 2025.*

- Anthropic's Opus 5.5 table reports Humanity's Last Exam with tools at 67.7% for Opus 5.5, 65.6% for Fable 5.1, 63.6% for Opus 5 and 57.2% for GPT-6 Astra (Sep 22, 2026). Anthropic's Fable 5.1 page gives 65.0% for the same model. With-tools scores are not comparable to no-tools scores. ([Anthropic, Sep 22, 2026](https://www.anthropic.com/claude-opus-5-5)) *Method: Vendor-reported, with tools, max effort.*
- The Humanity's Last Exam owner site lists a Nature publication (Jan 28, 2026, Nature 649, 1139-1146) and the release of HLE-Diamond on Sept 22, 2026 as a migration path 'once frontier AI begins to hit the noise ceiling on the original HLE dataset'; its own leaderboard table still shows Gemini 3 Pro at 38.3 as top. ([CAIS and Scale AI, Sep 22, 2026](https://lastexam.ai)) *Method: Benchmark owner site. The leaderboard table on the page carries its own dataset date of April 3, 2025.*
- Anthropic's Fable 5.1 page reports Humanity's Last Exam at 60.9% without tools and 65.0% with tools for Claude Fable 5.1, against 57.8% and 63.8% for Fable 5 and 56.6% and 63.6% for Opus 5. ([Anthropic, Sep 2026](https://www.anthropic.com/claude-fable-and-mythos-5-1)) *Method: Vendor-reported.*
- OpenAI reports GPT-5.2 Thinking at 34.5% on Humanity's Last Exam without tools and 45.5% with search and Python (Dec 11, 2025), up from 25.7% and 42.7% for GPT-5.1 Thinking. ([OpenAI, Dec 11, 2025](https://openai.com/index/introducing-gpt-5-2/)) *Method: OpenAI-reported (vendor) result.*
- OpenAI reports GPT-5.2 Thinking scoring 100.0% on AIME 2025 without tools (Dec 11, 2025), so the competition-math benchmark is saturated for vendor-reported results. ([OpenAI, Dec 11, 2025](https://openai.com/index/introducing-gpt-5-2/)) *Method: OpenAI-reported (vendor) result.*
- Stanford's 2026 AI Index reports frontier models gained 30 percentage points in a single year on Humanity's Last Exam, and that a review found invalid question rates from 2% on MMLU Math to 42% on GSM8K. ([Stanford HAI, undated page, read Nov 1, 2026](https://hai.stanford.edu/ai-index/2026-ai-index-report/technical-performance)) *Method: Compilation.*
- OpenAI reports GPT-6 Astra at 96.0% on GPQA Diamond, and Epoch AI's independent run of GPT-6 Astra gives 0.96 (+/-0.01). ([Epoch AI, undated page, read Nov 1, 2026](https://epoch.ai/data/benchmarks.csv); [OpenAI, GPT-6 Astra page, undated](https://openai.com/index/gpt-6-astra/)) *Method: Independent run by Epoch at max effort, 96% with a standard error of about 1 point.*
- OpenAI's GPT-6 Astra page says Astra scored 99.9% on ARC-AGI-3 and 98% on FrontierMath Tier 4, while its GPT-5.6 page (Jul 9, 2026) lists ARC-AGI-3 at 7.78% for GPT-5.6 Sol and 0.43% for GPT-5.5. ([OpenAI, undated page, read Nov 1, 2026](https://openai.com/index/gpt-6-astra/)) *Method: OpenAI-reported (vendor) result.*
- Stanford's 2026 AI Index reports that Gemini Deep Think scored 35 points (gold) at the 2025 International Mathematical Olympiad, up from the 28-point silver in 2024, while the top model reads analog clocks correctly 50.6% of the time against 90.1% for humans. ([Stanford HAI, undated page, read Nov 1, 2026](https://hai.stanford.edu/ai-index/2026-ai-index-report/technical-performance)) *Method: The IMO result is Google DeepMind's 2025 entry (DeepMind's own post dated 2025-07-21 says 'earning 35 out of a possible 42 points').*

---

## [GPQA](https://storage.googleapis.com/deepmind-media/gemini/gemini_v2_5_report.pdf) (Graduate-Level Science)

### Benchmark Overview

**GPQA Diamond** tests PhD-level reasoning in:
- Physics
- Chemistry
- Biology
- Cross-domain science

**Question Characteristics**:
- Require deep domain expertise
- Multi-step reasoning
- Cannot be easily searched
- Verified by domain experts

### Performance Data

| Model | GPQA Diamond | Date |
|-------|--------------|------|
| GPT-4 | ~55% | 2023 |
| Claude 3 Opus | ~60% | Early 2024 |
| Gemini 2.5 Pro | ~80% | March 2025 |
| Gemini 3 Deep Think | **93.8%** | November 2025 |

### Human Baselines

| Group | Estimated Score |
|-------|-----------------|
| PhD students (own domain) | 65-70% |
| PhD students (cross-domain) | 40-50% |
| Undergraduate (advanced) | 30-40% |
| General population | 20-25% |

### Implications

- AI exceeds average PhD student in cross-domain science
- Approaching expert-level in single domains
- Science education assessment fundamentally affected

---

## [AIME](https://www.maa.org/math-competitions/aime) (Mathematics Competition)

### Benchmark Overview

**American Invitational Mathematics Examination**:
- 15 questions, 3 hours
- Integer answers (0-999)
- Invitational (top ~5% of AMC qualifiers)
- Tests: algebra, geometry, number theory, combinatorics

### Performance Data

| Model | AIME 2025 Raw | With Code | Date |
|-------|---------------|-----------|------|
| GPT-4 | ~30% | ~40% | 2023 |
| Claude 3.5 | ~50% | ~60% | 2024 |
| Gemini 2.5 Pro | ~70% | ~80% | March 2025 |
| Gemini 3 | **95%** | **100%** | November 2025 |

### Human Baselines

| Group | Typical Score |
|-------|---------------|
| AIME qualifier (avg) | 6-7/15 (40-47%) |
| USAMO qualifier | 10+/15 (67%+) |
| IMO-level student | 12+/15 (80%+) |

### Implications

- AI exceeds most human math competitors
- Near-perfect with computational tools
- Math education emphasis shifts from computation to intuition

---

## Humanity's Last Exam

### Benchmark Overview

**Design Principle**: Questions at frontier of human knowledge
- Crowdsourced from domain experts
- Not searchable online
- Require novel reasoning
- Intended to be very difficult for AI

### Performance Data

| Model | Score (No Tools) | Date |
|-------|------------------|------|
| GPT-4 | ~8% | 2024 |
| Claude 3.5 Sonnet | ~12% | 2024 |
| Gemini 2.5 Pro | **18.8%** | March 2025 |

### Human Baselines

| Group | Estimated Score |
|-------|-----------------|
| Domain experts | 70-90% (in domain) |
| PhD researchers | 40-50% (cross-domain) |
| Advanced undergrad | 15-25% |

### Implications

- AI approaching half of expert cross-domain performance
- Frontier knowledge still largely human domain
- Gap closing faster than expected

---

## Writing and Analysis Benchmarks

### Essay Quality (Various Benchmarks)

| Task Type | AI Performance | Human Parity |
|-----------|----------------|--------------|
| Argumentative essay | 75-85% | Approaching |
| Research synthesis | 80-90% | Achieved |
| Creative writing | 60-75% | Below |
| Technical writing | 85-95% | Exceeded |

### Analysis Tasks

| Task Type | AI Performance |
|-----------|----------------|
| Literature review | High (with sources) |
| Data interpretation | Very high |
| Critical analysis | Moderate-high |
| Original argumentation | Moderate |

---

## Subject-Specific Academic Performance

### STEM Fields

| Subject | AI Capability Level |
|---------|---------------------|
| Mathematics (computational) | Expert |
| Mathematics (proof-based) | Advanced |
| Physics (problem-solving) | Expert |
| Chemistry | Advanced-Expert |
| Biology (factual) | Expert |
| Computer Science | Expert |
| Engineering (analysis) | Advanced |

### Humanities

| Subject | AI Capability Level |
|---------|---------------------|
| History (factual) | Expert |
| History (interpretation) | Advanced |
| Philosophy (analysis) | Advanced |
| Literature (analysis) | Moderate-Advanced |
| Languages (translation) | Expert |
| Languages (nuance) | Advanced |

### Social Sciences

| Subject | AI Capability Level |
|---------|---------------------|
| Economics (quantitative) | Expert |
| Psychology (research) | Advanced |
| Sociology | Advanced |
| Political Science | Advanced |

### Professional Fields

| Subject | AI Capability Level |
|---------|---------------------|
| Law (research) | Expert |
| Law (judgment) | Moderate |
| Medicine (diagnosis support) | Advanced |
| Business (analysis) | Expert |
| Education (content) | Expert |

---

## Assessment Vulnerability Analysis

### High Vulnerability (AI can likely complete)

1. **Take-home exams** - all subjects
2. **Research papers** - with proper prompting
3. **Problem sets** - especially STEM
4. **Short-answer questions** - most types
5. **Code assignments** - most levels

### Moderate Vulnerability

1. **In-class essays** - depends on proctoring
2. **Lab reports** - without actual lab work
3. **Project proposals** - conceptual portions
4. **Presentations** - slide content (not delivery)

### Lower Vulnerability (Currently)

1. **Oral examinations** - real-time interaction
2. **Lab practicals** - physical presence required
3. **Live demonstrations** - real-time execution
4. **Portfolio defense** - process-based
5. **Collaborative projects** - interpersonal dynamics

---

## Trajectory Implications

### Current State (2025)
- Graduate-level performance on standardized tests
- Expert-level writing and analysis
- Competition-level mathematics

### Near-Term (2026-2027)
- Frontier knowledge gap closing
- Original research assistance
- Multi-modal academic tasks

### Medium-Term (2028-2030)
- Research contribution at PhD level
- Novel discovery assistance
- Human advantage: judgment, ethics, relationships

---

## Key Takeaways for Universities

1. **Academic integrity crisis is real**: AI can complete most traditional assignments
2. **Assessment must evolve**: Process-based, oral, and proctored methods essential
3. **Learning objectives shift**: From knowledge to judgment and application
4. **AI literacy required**: Students need to work with AI effectively
5. **Subject-specific strategies needed**: Vulnerability varies by discipline
