**[← AI Impact Research](../../)** · **[AI Capabilities Research](../)**

---

# Safety and Alignment

## November 2026 update

*Updated November 1, 2026. The November 2026 section is current. Everything after it is the December 2025 compilation, kept as dated history. Superlatives and words like "latest", "leading" or "now" in that older text describe December 2025.*

- The International AI Safety Report 2026 says pre-deployment test results do not reliably predict real-world performance (an 'evaluation gap') and that dangerous capabilities could go undetected before deployment. ([International AI Safety Report, Feb 3, 2026](https://internationalaisafetyreport.org/publication/2026-report-extended-summary-policymakers))
- The International AI Safety Report 2026 says developers have made safeguards harder to bypass but attackers still succeed at a moderately high rate, and reported prompt injection success rates (within 10 attempts, models released May 2024 to August 2025) have fallen over time but remain relatively high. ([International AI Safety Report, Feb 3, 2026](https://internationalaisafetyreport.org/publication/2026-report-extended-summary-policymakers))
- UK AI Security Institute stress tests of safeguards on two leading systems released six months apart found a universal jailbreak for biological misuse requests in both, but the first took 10 minutes of expert red-teamer time and the second took over 7 hours plus a novel universal jailbreak (about 40x more effort). ([UK AI Security Institute, Dec 18, 2025](https://aisi.gov.uk/frontier-ai-trends-report))
- In Anthropic's report of the Gray Swan indirect prompt injection benchmark, Claude Opus 5 was attacked successfully within 15 attempts 2.0% of the time, and the most robust non-Claude model (Muse Spark) 16.5%; GPT 5.6 Sol was 20.0%. ([Anthropic, Oct 2, 2026](https://www.anthropic.com/transparency/model-report))
- Vectara's HHEM summarization leaderboard (updated 2026-10-22) lists hallucination rates of 9.3% for GPT-5.5, 9.9% for Claude Opus 5.5, 10.4% for Gemini 3.1 Pro and 12.4% for GPT-5.6 Sol, while the lowest listed model is 1.8%. This measures unsupported claims in summaries, not factual recall. ([Vectara, Oct 22, 2026](https://github.com/vectara/hallucination-leaderboard))
- METR's independent review of Anthropic's August 2026 Risk Report agrees the risk of catastrophic harm from misalignment is low for the covered models, but attributes this primarily to limited model capabilities rather than safeguards and alignment training. ([METR, Oct 20, 2026](https://metr.org/blog/2026-10-20-misalignment-risk-report-august-2026-review))
- The Future of Life Institute's Summer 2026 AI Safety Index (independent panel of seven, evidence to 2026-06-03) found that Anthropic, OpenAI, Google DeepMind and Meta have weakened or voided pledges to pause unilaterally if redlines are approached; overall grades were Anthropic C+ (2.66), OpenAI C (2.28), Google DeepMind C (2.01). ([Future of Life Institute, Jul 2026](https://futureoflife.org/ai-safety-index-summer-2026/))
- The European Commission's AI Act page states that rules for high-risk systems in sensitive areas including education will apply from 2 December 2027 (Annex I product-embedded systems from 2 August 2028), after an AI Omnibus agreed politically on 7 May 2026 and in force 27 July 2026. ([European Commission, Oct 19, 2026](https://digital-strategy.ec.europa.eu/en/policies/regulatory-framework-ai))

Vendor-reported numbers come from the company named and were not independently checked unless stated. All 16 new findings, with methods, are in **[the November 2026 evidence](./data.md#november-2026-evidence)**.

2 corrections to the December 2025 text on this page are marked in place below, labelled "Corrected November 1, 2026".

---

## Research Question

**How robust and safe are current AI models?**

## Hypothesis

AI safety characteristics vary significantly across models, with important implications for responsible deployment in educational contexts and AI ethics curricula.

---

## Key Findings

### 1. Prompt Injection Resistance

**Claude Opus 4.5**: Industry-leading resistance to prompt injection attacks ([Anthropic](https://www.anthropic.com/transparency/model-report))
- Harder to manipulate than any other frontier model *Corrected November 1, 2026: This is vendor-reported, from a benchmark Anthropic reports, and models were not tested under the same safeguards. See the dated numbers in the update above.*
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
