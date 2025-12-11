**[← AI Impact Research](../../)** · **[AI Capabilities Research](../)**

---

# Safety and Alignment

## Research Question

**How robust and safe are current AI models?**

## Hypothesis

AI safety characteristics vary significantly across models, with important implications for responsible deployment in educational contexts and AI ethics curricula.

---

## Key Findings

### 1. Prompt Injection Resistance

**Claude Opus 4.5**: Industry-leading resistance to prompt injection attacks ([Anthropic](https://www.anthropic.com/transparency/model-report))
- Harder to manipulate than any other frontier model
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

- More capable models can be more dangerous
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
