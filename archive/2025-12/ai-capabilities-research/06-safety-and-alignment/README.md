**[← AI Impact Research](../../)** · **[AI Capabilities Research](../)**

---

# Safety and Alignment

> **Archived text from December 2025.** This page is not kept up to date, and it holds figures the [corrections log](../../../../corrections.md) marks as wrong or unsourced. Do not cite it as current. See the [current page](../../../../ai-capabilities-research/06-safety-and-alignment/README.md).


## Research Question

**How robust and safe are current AI models?**

## Hypothesis

AI safety characteristics vary significantly across models, with important implications for responsible deployment in educational contexts and AI ethics curricula.

---

## Key Findings

### 1. Prompt Injection Resistance

**Claude Opus 4.5**: Industry-leading resistance to prompt injection attacks ([Anthropic](https://www.anthropic.com/transparency/model-report))
- Harder to manipulate than any other frontier model *Corrected November 1, 2026: This is vendor-reported, from a benchmark Anthropic reports, and models were not tested under the same safeguards. See the dated numbers on the current page.*
- Improved from previous generations
- Critical for deployed applications

### 2. Jailbreak Resistance

Models vary in susceptibility to:
- Direct instruction violations
- Roleplay-based circumvention
- Multi-turn manipulation
- Encoded malicious content

### 3. Hallucination Rates

| Model | Hallucination Rate | Trend |
|-------|-------------------|-------|
| Frontier models (2025) | 5-15% | Improving |
| Previous generation | 15-25% | - |
| Early LLMs | 25-40% | - |

### 4. Safety-Capability Tradeoffs

- More capable models can be more dangerous *Corrected November 1, 2026: No source measures this tradeoff. Treat it as the authors' judgment from December 2025.*
- Safety training may reduce some capabilities
- Balance is active research area
- No model is both maximally capable and maximally safe

---

## Implications for Universities

### AI Ethics Curriculum
- Real data on safety characteristics
- Prompt injection as security topic
- Responsible AI deployment
- Red teaming and evaluation methods

### Deployment Decisions
- Model selection based on safety profile
- Use case matching to risk tolerance
- Monitoring and audit requirements
- Incident response planning

### Research Ethics
- AI safety research opportunities
- Dual-use concerns
- Responsible disclosure practices
- Collaboration with labs

---

## Related Research Questions

- [RQ05: Agentic Capabilities](../05-agentic-capabilities/) - Agent safety concerns
- [RQ07: Educational Implications](../07-educational-implications/) - Policy frameworks

---

## Explore This Research

- **[Detailed Data & Analysis →](./data.md)** — Safety metrics, hallucination rates, and model comparisons
- **[All Sources →](./sources.md)** — Primary and secondary sources with links

---

**[← Previous: Agentic Capabilities](../05-agentic-capabilities/)** | **[Next: Educational Implications →](../07-educational-implications/)**
