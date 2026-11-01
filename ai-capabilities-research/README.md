**[← AI Impact Research](../)**

---

# AI Capabilities Research: Frontier Labs Benchmarks & Trajectories (2025-2026)

## November 2026 update

**Updated November 1, 2026.** The numbers in this section are current as of their dates. The rest of this page is the December 2025 compilation, kept as dated history. The models named in the old cross-lab table have all been replaced.

### Selected benchmark results

Most scores are vendor-reported, and the same model can score differently in different vendors' tables. Do not read this table as a ranking.

| Benchmark | Result | Who reported it | Date |
|-----------|--------|-----------------|------|
| GDPval wins or ties | GPT-5.5 84.9%, Claude Opus 4.7 80.3% | [OpenAI](https://openai.com/index/introducing-gpt-5-5/) | Apr 23, 2026 |
| GDPval-AA v2.1 (Elo) | Claude Opus 5.5 1846, GPT-5.6 Sol 1588, GPT-6 Astra 1542 | [Anthropic](https://www.anthropic.com/claude-opus-5-5) | Sep 22, 2026 |
| Remote Labor Index | Claude Opus 5.5 21.25%, GPT 6 Astra 20.83% | [Scale AI](https://www.scale.com/leaderboard/rli) | Undated, read Nov 1, 2026 |
| OSWorld 2.0, binary completion | Claude Opus 4.8 20.6% | [XLANG Lab](https://osworld-v2.xlang.ai/) | Undated, read Nov 1, 2026 |
| FrontierMath Tier 1-3 (v2) | GPT-6 Astra 93.7%, Claude Opus 5.5 91.2% | [Epoch AI, independent run](https://epoch.ai/data/benchmarks.csv) | Undated, read Nov 1, 2026 |
| GPQA Diamond | GPT-6 Astra 96% (+/-1) | [Epoch AI, independent run](https://epoch.ai/data/benchmarks.csv) | Undated, read Nov 1, 2026 |
| Humanity's Last Exam, no tools | Claude Fable 5.1 60.9% | [Anthropic](https://www.anthropic.com/claude-fable-and-mythos-5-1) | Sep 2026 |

### What changed by research question

- **Real-world tasks:** OpenAI's GDPval numbers rose through April 2026 ([OpenAI, Apr 23, 2026](https://openai.com/index/introducing-gpt-5-5/)), then its launch pages moved to another scale ([OpenAI, Jul 9, 2026](https://openai.com/index/gpt-5-6/)). Most client-style freelance projects still fail ([Scale AI, undated page, read Nov 1, 2026](https://www.scale.com/leaderboard/rli)).
- **Trajectory:** METR puts the doubling time of its time horizon since 2023 at 131 days ([METR, Jan 29, 2026](https://metr.org/blog/2026-01-29-time-horizon-1-1/)), but says its page is no longer updated ([METR, Sep 8, 2026](https://metr.org/time-horizons/)). A Federal Reserve governor said evidence of labor-market change remains limited ([Federal Reserve, Sep 28, 2026](https://www.federalreserve.gov/newsevents/speech/cook20260928a.htm)).
- **Academic benchmarks:** several are saturated ([OpenAI, Dec 11, 2025](https://openai.com/index/introducing-gpt-5-2/)), and Stanford's AI Index reports invalid question rates of up to 42% on one benchmark ([Stanford HAI, undated page, read Nov 1, 2026](https://hai.stanford.edu/ai-index/2026-ai-index-report/technical-performance)).
- **Coding:** SWE-bench Verified is no longer reported by OpenAI ([OpenAI, Feb 23, 2026](https://openai.com/index/why-we-no-longer-evaluate-swe-bench-verified/)). METR's follow-up estimates an 18% time reduction for 10 returning developers (interval -38% to +9%, which includes zero), and METR calls the data an unreliable signal ([METR, Feb 24, 2026](https://metr.org/blog/2026-02-24-uplift-update/)).
- **Agents:** success falls with task length ([XLANG Lab, undated page, read Nov 1, 2026](https://osworld-v2.xlang.ai/)). METR investigated an incident in which agents meant to be isolated found a way to communicate ([METR, Aug 26, 2026](https://metr.org/blog/2026-08-26-openai-hugging-face-incident-investigation/)).
- **Safety:** pre-deployment tests do not reliably predict real-world performance ([International AI Safety Report, Feb 3, 2026](https://internationalaisafetyreport.org/publication/2026-report-extended-summary-policymakers)). UK testing found jailbreaks took about 40x more expert effort on a later system, but still succeeded ([UK AI Security Institute, Dec 18, 2025](https://aisi.gov.uk/frontier-ai-trends-report)).
- **Education:** randomized evidence on generative AI in coursework conflicts ([IZA Institute of Labor Economics, Oct 2026](https://docs.iza.org/dp18989.pdf); [arXiv, Jul 9, 2026](https://arxiv.org/pdf/2607.08849)). EU high-risk rules that cover education will apply from 2 December 2027 ([European Commission, Oct 19, 2026](https://digital-strategy.ec.europa.eu/en/policies/regulatory-framework-ai)).

**How this update was made.** Every added number was read on its primary source page, or on a copy named in the method note, on November 1, 2026. Sources that could not be opened were left out. The research was done with Claude, an Anthropic model, and Anthropic's models and reports are subjects here, so vendor-reported numbers are labelled throughout.

---

## Overview

This repository contains comprehensive research on **what AI systems can do** — their performance on real-world tasks, improvement trajectories, and implications for higher education. The research covers frontier models from Anthropic, OpenAI, Google DeepMind, and Microsoft.

**Audience**: University stakeholders (administrators, faculty, curriculum designers, policy makers) adapting to rapidly changing AI capabilities.

> **Related Track**: Looking for how people actually use AI (adoption, demographics, trends)?
> See **[AI Usage Research →](../ai-usage-research/)**

**Time Period**: 2024-2025 benchmark data, with evidence published through October 2026 in the November 2026 sections

---

## Why This Matters for Universities (December 2025 figures)

AI capabilities are advancing faster than institutional adaptation cycles. These figures date from December 2025, and some are corrected on the research question pages:

- **PhD-level reasoning**: Gemini 3 scores 93.8% on graduate-level science questions (GPQA Diamond) ([Google](https://blog.google/products/gemini/gemini-3/))
- **Software engineering**: Claude Opus 4.5 exceeds best human performance on real-world coding tasks ([Anthropic](https://www.anthropic.com/news/claude-opus-4-5)) *Corrected November 1, 2026: the human comparison was a separate Anthropic exam, not SWE-bench.*
- **Professional tasks**: AI completes authentic work deliverables 100x faster and 100x cheaper than experts ([OpenAI](https://openai.com/index/gdpval/)) *Corrected November 1, 2026: a naive ratio. With human review the paper gives 1.12x faster and 1.18x cheaper for GPT-5 ([GDPval paper](https://cdn.openai.com/pdf/d5eb7428-c4e9-4a33-bd86-86dd4bcf12ce/GDPval.pdf)).*
- **Improvement rate**: Model capabilities doubled in 14 months (GPT-4o → GPT-5) ([OpenAI](https://openai.com/index/gdpval/)) *Corrected November 1, 2026: the paper's win rates are 12.5% for GPT-4o and 39.0% for GPT-5 ([GDPval paper](https://cdn.openai.com/pdf/d5eb7428-c4e9-4a33-bd86-86dd4bcf12ce/GDPval.pdf)).*

These developments have immediate implications for curriculum design, assessment integrity, research workflows, and workforce preparation.

---

## Research Questions

### [01. Real-World Task Performance](./01-real-world-task-performance/)

**Key Question**: How well do AI models perform on authentic professional tasks across occupations?

**Key Findings (December 2025)**:
- GDPval benchmark: 1,320 tasks across 44 occupations in 9 GDP-dominant sectors ([OpenAI](https://openai.com/index/gdpval/))
- Claude Opus 4.1 leads on deliverable quality (formatting, layout) ([OpenAI](https://openai.com/index/gdpval/))
- GPT-5 leads on accuracy (domain-specific knowledge) ([OpenAI](https://openai.com/index/gdpval/))
- AI achieves expert parity on ~50% of professional tasks ([Fortune](https://fortune.com/2025/09/30/ai-models-are-already-as-good-as-experts-at-half-of-tasks-a-new-openai-benchmark-gdpval-suggests/)) *Corrected November 1, 2026: the paper gives 47.6% for Claude Opus 4.1 and 39.0% for GPT-5 ([GDPval paper](https://cdn.openai.com/pdf/d5eb7428-c4e9-4a33-bd86-86dd4bcf12ce/GDPval.pdf)).*
- 100x speed and cost advantage over human experts ([OpenAI](https://openai.com/index/gdpval/)) *Corrected November 1, 2026: a naive ratio. With human review the paper gives 1.12x faster and 1.18x cheaper for GPT-5 ([GDPval paper](https://cdn.openai.com/pdf/d5eb7428-c4e9-4a33-bd86-86dd4bcf12ce/GDPval.pdf)).*

**Significance**: AI is approaching professional competence across diverse occupations

---

### [02. Capability Trajectory & Economic Impact](./02-capability-trajectory/)

**Key Question**: How fast are AI capabilities improving, and what are the projected economic impacts?

**Key Findings (December 2025)**:
- GPT-4o → GPT-5: >2x improvement on GDPval (14 months) ([OpenAI](https://openai.com/index/gdpval/))
- Gemini 2.5 → Gemini 3: 50% improvement on developer tasks (7 months) ([Google](https://blog.google/products/gemini/gemini-3/))
- Claude 4.1 → 4.5: 74.5% → 80.9% SWE-bench (3 months) ([Anthropic](https://www.anthropic.com/news/claude-opus-4-5))
- McKinsey: $4.4 trillion annual economic impact potential ([McKinsey](https://www.mckinsey.com/capabilities/mckinsey-digital/our-insights/the-economic-potential-of-generative-ai-the-next-productivity-frontier)) *Corrected November 1, 2026: this is the top of a $2.6 to $4.4 trillion range from June 2023 ([McKinsey](https://www.mckinsey.com/capabilities/mckinsey-digital/our-insights/the-economic-potential-of-generative-ai-the-next-productivity-frontier)).*
- PWC: $15.7 trillion global contribution by 2030 *Corrected November 1, 2026: this figure could not be traced to an open PwC page in November 2026. Do not cite it.*

**Significance**: Capability improvement is accelerating, not plateauing

---

### [03. Academic Task Benchmarks](./03-academic-task-benchmarks/)

**Key Question**: How do models perform on academic/intellectual tasks relevant to universities?

**Key Findings (December 2025)**:
- **GPQA Diamond** (PhD-level science): Gemini 3 at 93.8% ([Google](https://blog.google/products/gemini/gemini-3/))
- **AIME 2025** (math competition): Gemini 3 at 95% raw, 100% with code execution ([Google](https://blog.google/products/gemini/gemini-3/))
- **Humanity's Last Exam**: 18.8% on frontier knowledge/reasoning (without tools) ([Google](https://blog.google/technology/google-deepmind/gemini-model-thinking-updates-march-2025/))
- Writing, analysis, and research synthesis approaching expert quality

**Significance**: Graduate-level academic work is increasingly within AI capability range

---

### [04. Coding and Research Capabilities](./04-coding-and-research/)

**Key Question**: What can AI do in software development and research contexts?

**Key Findings (December 2025)**:
- **SWE-bench Verified**: Claude Opus 4.5 at 80.9% (first to exceed best human) ([Anthropic](https://www.anthropic.com/news/claude-opus-4-5)) *Corrected November 1, 2026: the human comparison was a separate Anthropic exam.*
- Claude exceeds best human on Anthropic's internal engineering test ([Anthropic](https://www.anthropic.com/news/claude-opus-4-5))
- AI research tasks: GPU kernels, RL algorithms, ML model training ([Anthropic](https://www.anthropic.com/research/how-ai-is-transforming-work-at-anthropic))
- **Counterpoint**: METR study found experienced devs 19% slower with AI assistance ([METR](https://metr.org/)) *Corrected November 1, 2026: METR's February 2026 follow-up reports different estimates and calls its data an unreliable signal. See the update above.*

**Significance**: Coding education and CS curriculum require fundamental rethinking

---

### [05. Agentic Capabilities](./05-agentic-capabilities/)

**Key Question**: What autonomous, multi-step work can AI perform?

**Key Findings (December 2025)**:
- **OSWorld** (computer use): Claude at 61.4% on real desktop/web tasks ([Anthropic](https://www.anthropic.com/news/claude-opus-4-5))
- Multi-file code changes with context awareness
- Autonomous refinement: peak performance in 4 iterations ([Anthropic](https://www.anthropic.com/research/how-ai-is-transforming-work-at-anthropic))
- Research workflow automation emerging

**Significance**: AI transitioning from tool to autonomous agent

---

### [06. Safety and Alignment](./06-safety-and-alignment/)

**Key Question**: How robust and safe are current AI models?

**Key Findings (December 2025)**:
- Claude Opus 4.5 leads in prompt injection resistance ([Anthropic](https://www.anthropic.com/transparency/model-report))
- Jailbreak success rates vary significantly across models
- Hallucination rates improving but still significant
- Safety-capability tradeoffs in model design

**Significance**: Relevant for AI ethics curricula and responsible deployment policies

---

### [07. Educational Implications](./07-educational-implications/)

**Key Question**: What should universities do in response to these capabilities?

**Recommendations**:
- **Curriculum**: Emphasize skills that complement AI (judgment, creativity, ethics, interpersonal)
- **Assessment**: Move toward process-based and oral evaluation; rethink take-home work
- **Research**: Integrate AI into workflows while maintaining rigor and attribution
- **Student skills**: Focus on AI collaboration, critical evaluation, domain expertise
- **Policy**: Develop nuanced academic integrity frameworks

**Significance**: Proactive adaptation required; reactive policies will lag capabilities

---

## Key Statistics Summary (December 2025, kept as history)

### Cross-Lab Benchmark Comparison (November 2025, kept as history)

*Corrected November 1, 2026: this table mixes model versions and is superseded. The 61.4% OSWorld score was reported for Claude Sonnet 4.5 ([Anthropic, Sep 29, 2025](https://www.anthropic.com/news/claude-sonnet-4-5)). OpenAI no longer reports SWE-bench Verified ([OpenAI, Feb 23, 2026](https://openai.com/index/why-we-no-longer-evaluate-swe-bench-verified/)). See the table in the November 2026 update above.*

| Benchmark | Claude Opus 4.5 | GPT-5 | Gemini 3 | Measure |
|-----------|-----------------|-------|----------|---------|
| SWE-bench Verified | **80.9%** | 77.9% | 76.2% | Real-world coding |
| GPQA Diamond | TBD | TBD | **93.8%** | PhD-level science |
| AIME 2025 | TBD | TBD | **95-100%** | Math competition |
| OSWorld | **61.4%** | TBD | TBD | Computer use |
| GDPval Expert Parity | **Leading** | Strong | TBD | Professional tasks |

### Capability Improvement Rates

| Transition | Timeframe | Improvement | Benchmark |
|------------|-----------|-------------|-----------|
| GPT-4o → GPT-5 | 14 months | >2x | GDPval |
| Gemini 2.5 → 3 | 7 months | 50% | Developer tasks |
| Claude 4.1 → 4.5 | 3 months | 74.5% → 80.9% | SWE-bench |

### Economic Projections

*Corrected November 1, 2026: the PwC and market size rows could not be traced to an open primary source. Do not cite them.*

| Source | Projection | Timeframe |
|--------|------------|-----------|
| [McKinsey, Jun 14, 2023](https://www.mckinsey.com/capabilities/mckinsey-digital/our-insights/the-economic-potential-of-generative-ai-the-next-productivity-frontier) | $2.6 to $4.4 trillion/year (corrected) | Potential annual impact, 63 use cases |
| PWC | $15.7 trillion | Global contribution by 2030 |
| Market size | $243.72B → $826.73B | 2025 → 2030 |

---

## Research Structure

Each research question folder contains:

```
XX-research-question-name/
├── README.md      # Question overview, hypothesis, key findings
├── data.md        # Detailed data, analysis, implications
└── sources.md     # Comprehensive source list with links
```

---

## Major Data Sources

### Primary Research (2025)

1. **OpenAI GDPval** (September 2025)
   - 1,320 tasks across 44 occupations
   - Open-sourced 220-task gold set
   - Public evaluation service at evals.openai.com

2. **Anthropic Model Reports & Transparency Hub**
   - SWE-bench and OSWorld results
   - Safety evaluations and model cards
   - Internal engineering test comparisons

3. **Google DeepMind Gemini Reports**
   - Gemini 2.5 and 3 technical reports
   - GPQA, AIME, Humanity's Last Exam results

4. **Microsoft Research**
   - ADeLe framework for AI evaluation
   - Work Trend Index productivity studies
   - Azure AI evaluation methodology

### Third-Party Research

5. **METR** - AI coding impact studies
6. **Stanford/BetterUp** - Workplace productivity research
7. **McKinsey/PWC/IMF** - Economic impact projections

---

## Using This Research

### For University Administrators
- RQ02 (Trajectory) for strategic planning timelines
- RQ07 (Educational Implications) for policy development
- Cross-reference with [Usage Research](../ai-usage-research/) for adoption patterns

### For Faculty
- RQ03 (Academic Benchmarks) for discipline-specific implications
- RQ04 (Coding/Research) for CS and research methodology courses
- RQ07 (Educational Implications) for assessment redesign

### For Curriculum Designers
- All RQs inform skill prioritization
- RQ01 (Real-World Tasks) for workforce preparation alignment
- RQ05 (Agentic) for understanding near-future capabilities

### For Policy Makers
- RQ06 (Safety) for responsible use frameworks
- RQ07 (Educational Implications) for academic integrity policies
- RQ02 (Trajectory) for anticipatory governance

---

## Cross-References with Usage Research (December 2025)

| Capabilities RQ | Related Usage RQ | Connection |
|-----------------|------------------|------------|
| RQ05 (Agentic) | Usage RQ01 (Automation) | Automation patterns reflect agentic capabilities |
| RQ04 (Coding) | Usage RQ02 (Platform Specialization) | Claude's coding dominance in usage matches benchmarks |
| RQ02 (Trajectory) | Usage RQ06 (Use Case Evolution) | Capability growth drives use case expansion |

---

## Data Gaps & Research Needs (December 2025)

### Missing Data
1. **Longitudinal tracking**: Need multi-year capability trajectories
2. **Domain-specific benchmarks**: Limited data outside tech/STEM
3. **Educational outcome studies**: Impact of AI on learning outcomes
4. **Comparative safety data**: Standardized cross-lab safety benchmarks

### Future Research Questions
1. How do capability improvements translate to educational impact?
2. What is the optimal human-AI collaboration model for learning?
3. How should assessment evolve as capabilities advance?
4. What skills remain durably valuable?

---

## About This Research

**Compiled**: December 2025
**Last Updated**: 2026-11-01
**Research Purpose**: Inform university stakeholder decisions on AI adaptation
**Methodology**: Synthesis of published benchmarks, technical reports, and economic analyses

---

## Citation Recommendation

```
AI Capabilities Research: Frontier Labs Benchmarks & Trajectories (2025-2026)
Research Questions: Real-World Tasks, Capability Trajectory, Academic Benchmarks,
Coding/Research, Agentic Capabilities, Safety/Alignment, Educational Implications
Data Sources: OpenAI GDPval, Anthropic Model Reports, Google DeepMind Gemini Reports,
Microsoft Research, METR, McKinsey, PWC, IMF
Compiled: December 2025. Updated: November 2026
```

For specific findings, cite the original source (URLs provided in sources.md files).
