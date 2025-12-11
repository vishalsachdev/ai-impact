# AI Capabilities Research: Frontier Labs Benchmarks & Trajectories (2025)

## Overview

This repository contains comprehensive research on **what AI systems can do** — their performance on real-world tasks, improvement trajectories, and implications for higher education. The research covers frontier models from Anthropic, OpenAI, Google DeepMind, and Microsoft.

**Audience**: University stakeholders (administrators, faculty, curriculum designers, policy makers) adapting to rapidly changing AI capabilities.

**Companion Research**: See [AI Usage Research](../ai-usage-research/) for how people actually use these systems.

**Time Period**: 2024-2025 benchmark data with trajectory analysis

---

## Why This Matters for Universities

AI capabilities are advancing faster than institutional adaptation cycles:

- **PhD-level reasoning**: Gemini 3 scores 93.8% on graduate-level science questions (GPQA Diamond)
- **Software engineering**: Claude Opus 4.5 exceeds best human performance on real-world coding tasks
- **Professional tasks**: AI completes authentic work deliverables 100x faster and 100x cheaper than experts
- **Improvement rate**: Model capabilities doubled in 14 months (GPT-4o → GPT-5)

These developments have immediate implications for curriculum design, assessment integrity, research workflows, and workforce preparation.

---

## Research Questions

### [01. Real-World Task Performance](./01-real-world-task-performance/)

**Key Question**: How well do AI models perform on authentic professional tasks across occupations?

**Key Findings**:
- GDPval benchmark: 1,320 tasks across 44 occupations in 9 GDP-dominant sectors
- Claude Opus 4.1 leads on deliverable quality (formatting, layout)
- GPT-5 leads on accuracy (domain-specific knowledge)
- AI achieves expert parity on ~50% of professional tasks
- 100x speed and cost advantage over human experts

**Significance**: AI is approaching professional competence across diverse occupations

---

### [02. Capability Trajectory & Economic Impact](./02-capability-trajectory/)

**Key Question**: How fast are AI capabilities improving, and what are the projected economic impacts?

**Key Findings**:
- GPT-4o → GPT-5: >2x improvement on GDPval (14 months)
- Gemini 2.5 → Gemini 3: 50% improvement on developer tasks (7 months)
- Claude 4.1 → 4.5: 74.5% → 80.9% SWE-bench (3 months)
- McKinsey: $4.4 trillion annual economic impact potential
- PWC: $15.7 trillion global contribution by 2030

**Significance**: Capability improvement is accelerating, not plateauing

---

### [03. Academic Task Benchmarks](./03-academic-task-benchmarks/)

**Key Question**: How do models perform on academic/intellectual tasks relevant to universities?

**Key Findings**:
- **GPQA Diamond** (PhD-level science): Gemini 3 at 93.8%
- **AIME 2025** (math competition): Gemini 3 at 95% raw, 100% with code execution
- **Humanity's Last Exam**: 18.8% on frontier knowledge/reasoning (without tools)
- Writing, analysis, and research synthesis approaching expert quality

**Significance**: Graduate-level academic work is increasingly within AI capability range

---

### [04. Coding and Research Capabilities](./04-coding-and-research/)

**Key Question**: What can AI do in software development and research contexts?

**Key Findings**:
- **SWE-bench Verified**: Claude Opus 4.5 at 80.9% (first to exceed best human)
- Claude exceeds best human on Anthropic's internal engineering test
- AI research tasks: GPU kernels, RL algorithms, ML model training
- **Counterpoint**: METR study found experienced devs 19% slower with AI assistance

**Significance**: Coding education and CS curriculum require fundamental rethinking

---

### [05. Agentic Capabilities](./05-agentic-capabilities/)

**Key Question**: What autonomous, multi-step work can AI perform?

**Key Findings**:
- **OSWorld** (computer use): Claude at 61.4% on real desktop/web tasks
- Multi-file code changes with context awareness
- Autonomous refinement: peak performance in 4 iterations
- Research workflow automation emerging

**Significance**: AI transitioning from tool to autonomous agent

---

### [06. Safety and Alignment](./06-safety-and-alignment/)

**Key Question**: How robust and safe are current AI models?

**Key Findings**:
- Claude Opus 4.5 leads in prompt injection resistance
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

## Key Statistics Summary

### Cross-Lab Benchmark Comparison (November 2025)

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

| Source | Projection | Timeframe |
|--------|------------|-----------|
| McKinsey | $4.4 trillion/year | Potential annual impact |
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

## Cross-References with Usage Research

| Capabilities RQ | Related Usage RQ | Connection |
|-----------------|------------------|------------|
| RQ05 (Agentic) | Usage RQ01 (Automation) | Automation patterns reflect agentic capabilities |
| RQ04 (Coding) | Usage RQ02 (Platform Specialization) | Claude's coding dominance in usage matches benchmarks |
| RQ02 (Trajectory) | Usage RQ06 (Use Case Evolution) | Capability growth drives use case expansion |

---

## Data Gaps & Research Needs

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
**Last Updated**: 2025-12-10
**Research Purpose**: Inform university stakeholder decisions on AI adaptation
**Methodology**: Synthesis of published benchmarks, technical reports, and economic analyses

---

## Citation Recommendation

```
AI Capabilities Research: Frontier Labs Benchmarks & Trajectories (2025)
Research Questions: Real-World Tasks, Capability Trajectory, Academic Benchmarks,
Coding/Research, Agentic Capabilities, Safety/Alignment, Educational Implications
Data Sources: OpenAI GDPval, Anthropic Model Reports, Google DeepMind Gemini Reports,
Microsoft Research, METR, McKinsey, PWC, IMF
Compiled: December 2025
```

For specific findings, cite the original source (URLs provided in sources.md files).
