**[← AI Impact Research](../../)** · **[AI Capabilities Research](../)**

---

# Safety and Alignment

## Research Question

**How robust and safe are current AI models?**

## November 2026 update

*Updated November 1, 2026. Evidence through October 2026. Each item carries an evidence label, explained on the home page.*

- **Expert compilation.** The International AI Safety Report 2026 says pre-deployment test results do not reliably predict real-world performance (an 'evaluation gap') and that dangerous capabilities could go undetected before deployment. ([International AI Safety Report, Feb 3, 2026](https://internationalaisafetyreport.org/publication/2026-report-extended-summary-policymakers))
- **Expert compilation.** The International AI Safety Report 2026 says developers have made safeguards harder to bypass but attackers still succeed at a moderately high rate, and reported prompt injection success rates (within 10 attempts, models released May 2024 to August 2025) have fallen over time but remain relatively high. ([International AI Safety Report, Feb 3, 2026](https://internationalaisafetyreport.org/publication/2026-report-extended-summary-policymakers))
- **Third-party measurement.** UK AI Security Institute stress tests of safeguards on two leading systems released six months apart found a universal jailbreak for biological misuse requests in both, but the first took 10 minutes of expert red-teamer time and the second took over 7 hours plus a novel universal jailbreak (about 40x more effort). ([UK AI Security Institute, Dec 18, 2025](https://aisi.gov.uk/frontier-ai-trends-report))
- **Vendor-reported.** In Anthropic's report of the Gray Swan indirect prompt injection benchmark, Claude Opus 5 was attacked successfully within 15 attempts 2.0% of the time, and the most robust non-Claude model (Muse Spark) 16.5%; GPT 5.6 Sol was 20.0%. ([Anthropic, Oct 2, 2026](https://www.anthropic.com/transparency/model-report))
- **Third-party measurement.** Vectara's HHEM summarization leaderboard (updated 2026-10-22) lists hallucination rates of 9.3% for GPT-5.5, 9.9% for Claude Opus 5.5, 10.4% for Gemini 3.1 Pro and 12.4% for GPT-5.6 Sol, while the lowest listed model is 1.8%. This measures unsupported claims in summaries, not factual recall. ([Vectara, Oct 22, 2026](https://github.com/vectara/hallucination-leaderboard))
- **Third-party measurement.** METR's independent review of Anthropic's August 2026 Risk Report agrees the risk of catastrophic harm from misalignment is low for the covered models, but attributes this primarily to limited model capabilities rather than safeguards and alignment training. ([METR, Oct 20, 2026](https://metr.org/blog/2026-10-20-misalignment-risk-report-august-2026-review))
- **Third-party measurement.** The Future of Life Institute's Summer 2026 AI Safety Index (independent panel of seven, evidence to 2026-06-03) found that Anthropic, OpenAI, Google DeepMind and Meta have weakened or voided pledges to pause unilaterally if redlines are approached; overall grades were Anthropic C+ (2.66), OpenAI C (2.28), Google DeepMind C (2.01). ([Future of Life Institute, Jul 2026](https://futureoflife.org/ai-safety-index-summer-2026/))
- **Official source.** The European Commission's AI Act page states that rules for high-risk systems in sensitive areas including education will apply from 2 December 2027 (Annex I product-embedded systems from 2 August 2028), after an AI Omnibus agreed politically on 7 May 2026 and in force 27 July 2026. ([European Commission, Oct 19, 2026](https://digital-strategy.ec.europa.eu/en/policies/regulatory-framework-ai))

Vendor-reported numbers come from the company named and were not independently checked unless stated. All 16 new findings, with methods, are in **[the November 2026 evidence](./data.md#november-2026-evidence)**.

5 statements from the December 2025 version of this topic were corrected. See the [corrections log](../../corrections.md#cap-06).

## Explore This Research

- **[Detailed Evidence →](./data.md)**: every new finding, with method notes
- **[All Sources →](./sources.md)**: sources added in November 2026

---

[How this was checked](../../method.md) · [Corrections log](../../corrections.md) · [Report an error](https://github.com/vishalsachdev/ai-impact/issues/new?title=Error%20report&body=Page%3A%0AClaim%3A%0ASource%3A%0AWhat%20is%20wrong%3A) · [December 2025 archive](../../archive/2025-12/ai-capabilities-research/06-safety-and-alignment/)

**[← Previous: Agentic Capabilities](../05-agentic-capabilities/)** | **[Next: Educational Implications →](../07-educational-implications/)**
