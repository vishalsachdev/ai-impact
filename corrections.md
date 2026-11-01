**[← AI Impact Research](./)**

---

# Corrections Log

This log lists 80 statements from the December 2025 version of this site that were found to be wrong, unsupported or misleading, all corrected on November 1, 2026. The original pages are in the [December 2025 archive](archive/2025-12/), with each correction marked in place. Some statements appear on more than one page, so the same correction can appear twice.

**Found another error?** [Report it](https://github.com/vishalsachdev/ai-impact/issues/new?title=Error%20report&body=Page%3A%0AClaim%3A%0ASource%3A%0AWhat%20is%20wrong%3A) in a public GitHub issue.

## Capabilities 01: Real-World Task Performance {#cap-01}

- **Earlier text:** "Linear improvement trajectory: performance doubled from GPT-4o to GPT-5 (14 months) (OpenAI)"
  **Correction:** The paper's win rates are 12.5% for GPT-4o and 39.0% for GPT-5 ([GDPval paper](https://cdn.openai.com/pdf/d5eb7428-c4e9-4a33-bd86-86dd4bcf12ce/GDPval.pdf)). The 14-month interval is not stated there.
- **Earlier text:** "AI completes GDPval tasks 100x faster than human experts (OpenAI)"
  **Correction:** The 100x is a naive ratio. For GPT-5 the paper gives 90x speed and 474x cost before human review, and 1.12x faster and 1.18x cheaper when a person reviews once and redoes failures ([GDPval paper](https://cdn.openai.com/pdf/d5eb7428-c4e9-4a33-bd86-86dd4bcf12ce/GDPval.pdf)).
- **Earlier text:** "Gemini 3 Varies 33-50%"
  **Correction:** The GDPval paper tested Gemini 2.5 Pro and Grok 4, not Gemini 3, and these ranges could not be found in it. Do not cite them.
- **Earlier text:** "Late 2026: 70-80% expert parity"
  **Correction:** This was a projection, not a finding. See the dated GDPval results on the current page.
- **Earlier text:** "GPT-5 ~45-50% Accuracy, domain knowledge"
  **Correction:** The paper reports 47.6% wins or ties for Claude Opus 4.1 and a 39.0% win rate for GPT-5 ([GDPval paper](https://cdn.openai.com/pdf/d5eb7428-c4e9-4a33-bd86-86dd4bcf12ce/GDPval.pdf)).

## Capabilities 02: Capability Trajectory & Economic Impact {#cap-02}

- **Earlier text:** "Market size $243.72B → $826.73B 2025 → 2030"
  **Correction:** This market size figure has no source on this site. Do not cite it.
- **Earlier text:** "McKinsey $4.4 trillion/year Annual potential"
  **Correction:** The $4.4 trillion is the top of McKinsey's range of $2.6 trillion to $4.4 trillion across 63 use cases, from June 2023 ([McKinsey, Jun 14, 2023](https://www.mckinsey.com/capabilities/mckinsey-digital/our-insights/the-economic-potential-of-generative-ai-the-next-productivity-frontier)).

## Capabilities 03: Academic Task Benchmarks {#cap-03}

- **Earlier text:** "Expert humans: ~40-50%"
  **Correction:** The expert baseline here could not be found in the Humanity's Last Exam paper. Do not cite it.
- **Earlier text:** "Human PhD students: ~65-70% (in their domain)"
  **Correction:** The GPQA paper gives 65% for experts (74% after discounting clear mistakes) and 34% for skilled non-experts, on the full question set rather than Diamond ([GPQA paper](https://arxiv.org/pdf/2311.12022)).

## Capabilities 04: Coding and Research Capabilities {#cap-04}

- **Earlier text:** "Finding: Experienced developers 19% slower with AI assistance (METR)"
  **Correction:** METR's estimate was 19% longer with a confidence interval of +2% to +39% ([METR, Jul 10, 2025](https://metr.org/blog/2025-07-10-early-2025-ai-experienced-os-dev-study/)). See METR's [February 2026 follow-up](https://metr.org/blog/2026-02-24-uplift-update/) on the current page.
- **Earlier text:** "Claude Opus 4.5 80.9% Nov 2025 First to exceed best human"
  **Correction:** The human comparison is a separate Anthropic internal take-home exam, not SWE-bench, and is vendor-reported ([Anthropic, Nov 24, 2025](https://www.anthropic.com/news/claude-opus-4-5)).
- **Earlier text:** "Task Type AI Capability Best Model"
  **Correction:** These proficiency and frequency tables have no cited source. Treat them as the authors' judgment from December 2025, not as measurements.

## Capabilities 05: Agentic Capabilities {#cap-05}

- **Earlier text:** "Peak performance achieved in 4 iterations"
  **Correction:** This is a customer testimonial on the Opus 4.5 launch page, not an Anthropic research finding ([Anthropic, Nov 24, 2025](https://www.anthropic.com/news/claude-opus-4-5)).
- **Earlier text:** "Other frontier models 30-50% 2025"
  **Correction:** The 'Other frontier models 30-50%' row has no source. Do not cite it.
- **Earlier text:** "Claude Opus 4.5 61.4% Nov 2025"
  **Correction:** Anthropic's launch page gives 61.4% for Claude Sonnet 4.5 in September 2025 ([Anthropic, Sep 29, 2025](https://www.anthropic.com/news/claude-sonnet-4-5)), and the Opus 4.5 page text does not state it.
- **Earlier text:** "Steps Success Rate Notes"
  **Correction:** This table has no source. Do not cite it. OSWorld 2.0 task-length results are on the current page.

## Capabilities 06: Safety and Alignment {#cap-06}

- **Earlier text:** "More capable models can be more dangerous"
  **Correction:** No source measures this tradeoff. Treat it as the authors' judgment from December 2025.
- **Earlier text:** "Harder to manipulate than any other frontier model"
  **Correction:** This is vendor-reported, from a benchmark Anthropic reports, and models were not tested under the same safeguards. See the dated numbers on the current page.
- **Earlier text:** "Hallucination Rates by Domain"
  **Correction:** These hallucination ranges are estimates with no source. Do not cite them.
- **Earlier text:** "Jailbreak Success Rates (Estimated)"
  **Correction:** These jailbreak rates have no source. Do not cite them.
- **Earlier text:** "Model Comparison (Anthropic Transparency Hub)"
  **Correction:** The cited Anthropic page has no such ratings for other developers' models. See the numeric, vendor-reported results on the current page.

## Capabilities 07: Educational Implications {#cap-07}

- **Earlier text:** "This section provides prescriptive recommendations for university stakeholders based on the capability data from RQ01-RQ06. It is intended for administrators, faculty, cu..."
  **Correction:** These recommendations were not tied to measured learning outcomes. The current page adds randomized evidence, including a negative result.
- **Earlier text:** "AI detection tools unreliable (high false positive/negative rates)"
  **Correction:** This line cites no study. See Epoch AI's July 2026 detector test on the current page, including its limits.
- **Earlier text:** "AI in Education Research"
  **Correction:** Most sources from number 7 on give only a generic title and no URL, so they could not be checked. Sources 4 to 6 are secondary coverage.

## Usage 01: Automation vs Augmentation Patterns {#usage-01}

- **Earlier text:** "Business vs Consumer divide: 77% of business API use is automation (Anthropic), while 73% of ChatGPT use is personal/advisory (OpenAI)"
  **Correction:** The 73% is the non-work share of sampled ChatGPT messages in June 2025. The Asking share, the closest match to advisory use, was 49% ([OpenAI paper, Sep 2025](https://cdn.openai.com/pdf/a253471f-8260-40c6-a2cc-aa93fe9f142e/economic-research-chatgpt-usage-paper.pdf)).
- **Earlier text:** "Historic shift (August 2025): First time automation (39%) exceeded augmentation (61%) in Anthropic's data (Anthropic)"
  **Correction:** The 39% is the directive share only, and 39% does not exceed 61%. Anthropic's report puts automation at about 49% against about 47% augmentation in August 2025 ([Anthropic, Sep 15, 2025](https://www.anthropic.com/research/anthropic-economic-index-september-2025-report)); augmentation led again in November 2025 at 52% against 45% ([Anthropic, Jan 15, 2026](https://www.anthropic.com/research/anthropic-economic-index-january-2026-report)).
- **Earlier text:** "ChatGPT ~27% ~73% Personal/Consumer"
  **Correction:** The 27% and 73% are OpenAI's work and non-work shares, not automation and augmentation. OpenAI's own split is Asking 49%, Doing 40%, Expressing 11% ([OpenAI paper, Sep 2025](https://cdn.openai.com/pdf/a253471f-8260-40c6-a2cc-aa93fe9f142e/economic-research-chatgpt-usage-paper.pdf)).
- **Earlier text:** "Claude API 77% 23% Business/Enterprise"
  **Correction:** The API split is 77% automation and 12% augmentation, not 23% augmentation ([Anthropic, Sep 15, 2025](https://www.anthropic.com/research/anthropic-economic-index-september-2025-report)).
- **Earlier text:** "77% of business API: Full task delegation"
  **Correction:** The 77% covers all automation patterns in August 2025, not only full delegation ([Anthropic, Sep 15, 2025](https://www.anthropic.com/research/anthropic-economic-index-september-2025-report)). The directive share alone was 64% in November 2025 ([Anthropic, Jan 15, 2026](https://www.anthropic.com/research/anthropic-economic-index-january-2026-report)).
- **Earlier text:** "73% usage for personal tasks"
  **Correction:** The 73% is the non-work share in June 2025, and Asking is a separate 49% ([OpenAI paper, Sep 2025](https://cdn.openai.com/pdf/a253471f-8260-40c6-a2cc-aa93fe9f142e/economic-research-chatgpt-usage-paper.pdf)).

## Usage 02: Platform Specialization Patterns {#usage-02}

- **Earlier text:** "Q2 2025: 82M MAU"
  **Correction:** Alphabet stated over 450 million monthly active Gemini app users for Q2 2025 ([Alphabet, Jul 23, 2025](https://blog.google/inside-google/message-ceo/alphabet-earnings-q2-2025/)), so the 82M figure and the 11.7x growth multiple on this page are wrong.
- **Earlier text:** "Note: Gemini's U.S. sessions represent 37% of all generative AI tool sessions despite lower headline share"
  **Correction:** This 37% line has no source and conflicts with the share on the line above. Do not cite it.
- **Earlier text:** "Shift: Work tasks declining (47% → 28%)"
  **Correction:** The paper gives 27% for June 2025 ([OpenAI paper](https://cdn.openai.com/pdf/a253471f-8260-40c6-a2cc-aa93fe9f142e/economic-research-chatgpt-usage-paper.pdf)).

## Usage 03: Demographics & Adoption Trends {#usage-03}

- **Earlier text:** "Emerging economies leading: India, Brazil, Mexico, South Africa have highest adoption rates (Modern Diplomacy)"
  **Correction:** This holds only for respondents in the 14-country OECD-Cisco poll. Microsoft's Q2 2026 telemetry lists South Africa at 23.9%, Mexico at 21.4%, Brazil at 20.2% and India at 18.5%, against 28.8% for the Global North ([Microsoft, Sep 21, 2026](https://www.microsoft.com/en-us/research/wp-content/uploads/2026/09/Microsoft-AI-Diffusion-Report-2026-Q2.pdf)).
- **Earlier text:** "Age concentration: 53.24% of ChatGPT users are 18-34 years old (DemandSage)"
  **Correction:** The 53.24% comes from an aggregator, not a primary source, and is a share of users rather than an adoption rate by age. Use the Pew 2026 age figures on the current page.
- **Earlier text:** "Gender parity achieved: ChatGPT now 52.4% female (vs male-dominated in 2024) (OpenAI)"
  **Correction:** The 52.4% overstates the source. OpenAI reported about 52% among users whose names could be classified, by July 2025. This is inferred from names, not measured gender. Pew's 2026 survey shows the gap in ever-use has closed, but men use chatbots daily more often (see the current page).
- **Earlier text:** "Black teens: 68% use chatbots"
  **Correction:** Pew's text says roughly seven in ten Black and Hispanic teens and about three in ten teens daily. The exact 68% and 28% could not be confirmed from Pew's page text.

## Usage 04: Global Inequality in AI Access & Adoption {#usage-04}

- **Earlier text:** "Speed vs equity: AI adoption happening in months (not decades), many countries lack infrastructure/skills/governance (UN)"
  **Correction:** This finding was cited through news coverage. The primary source is the [UNDP report, Dec 2025](https://www.undp.org/sites/g/files/zskgke326/files/2025-12/undp-rbap-the-next-great-divergence.pdf).
- **Earlier text:** "Economic impact: AI growth in advanced economies projected >2x that of low-income countries (IMF)"
  **Correction:** This is a model estimate from a different IMF paper: the growth impact in advanced economies "could be more than double" that in low-income countries ([IMF WP 2025/076, Apr 11, 2025](https://www.imf.org/en/publications/wp/issues/2025/04/11/the-global-impact-of-ai-mind-the-gap-566129)).
- **Earlier text:** "Adoption gap: Global North 23%, Global South 13% (10 pp difference) (IMF)"
  **Correction:** These numbers are from Microsoft's telemetry for H1 2025 (22.9% and 13.1%), not the IMF paper cited here ([Microsoft, May 7, 2026](https://www.microsoft.com/en-us/research/wp-content/uploads/2026/05/Microsoft-AI-Diffusion-Report-2026-Q1.pdf)).
- **Earlier text:** "Extreme disparities: Singapore uses AI 23x more than Nigeria (AUI: 4.6 vs 0.20) (Anthropic)"
  **Correction:** The 23x compares rounded Claude.ai usage per working-age person (August 2025 data). It does not measure AI use in general.
- **Earlier text:** "25% of population has no internet access"
  **Correction:** The Asia-Pacific figure comes from the [UNDP report, Dec 2025](https://www.undp.org/sites/g/files/zskgke326/files/2025-12/undp-rbap-the-next-great-divergence.pdf), not from the OECD-Cisco poll.

## Usage 05: Enterprise vs Consumer Usage Patterns {#usage-05}

- **Earlier text:** "Industry leaders: IT & telecom (38%), retail (31%), financial services (24%) (Menlo Ventures)"
  **Correction:** The linked Menlo page does not contain these sector figures. For sector rates see the [Census Bureau, May 26, 2026](https://www.census.gov/library/stories/2026/05/ai-use-businesses.html).
- **Earlier text:** "Enterprise growth: Claude enterprise share 18% → 29% in past year (SQ Magazine)"
  **Correction:** The linked Menlo page does not contain 18% or 29%, and those figures trace to an aggregator. Menlo's own December 2025 estimate is on the current page.
- **Earlier text:** "Adoption by segment: Gemini 63% enterprise (SQ Magazine), 72% of all companies use AI (Menlo Ventures), 90%+ Fortune 500 on Copilot (Microsoft)"
  **Correction:** The linked Menlo page does not contain the 72% figure. Do not cite it. The current page gives three sourced measures that use different methods.
- **Earlier text:** "Privacy Divide: Consumer = Terms of Service (data as product), Enterprise = Data Processing Addendums (privacy as product) (Medium)"
  **Correction:** The "data as product" framing rests on a blog post. The primary terms show plan-level choices: see the Anthropic and OpenAI policy items on the current page.
- **Earlier text:** "Leading Platform ChatGPT (59.7%) Copilot (90% F500)"
  **Correction:** The 'Leading Platform' row mixes a traffic share with a count of organisations that report any Copilot use. The 90% is vendor-reported and says nothing about the share of employees.
- **Earlier text:** "Mid-2025: 72% non-work prompts"
  **Correction:** The paper's table gives 73% non-work and 27% work for June 2025, with work down from 47% ([OpenAI paper, Sep 2025](https://cdn.openai.com/pdf/a253471f-8260-40c6-a2cc-aa93fe9f142e/economic-research-chatgpt-usage-paper.pdf)).
- **Earlier text:** "47% → 28% decline in work usage"
  **Correction:** The paper gives 27% for June 2025 ([OpenAI paper](https://cdn.openai.com/pdf/a253471f-8260-40c6-a2cc-aa93fe9f142e/economic-research-chatgpt-usage-paper.pdf)).

## Usage 06: Use Case Evolution Over Time {#usage-06}

- **Earlier text:** "Work → Personal shift: ChatGPT non-work usage 53% → 72% (mid-2024 → mid-2025) (OpenAI)"
  **Correction:** The paper's table gives 53% in June 2024 and 73% in June 2025 ([OpenAI paper, Sep 2025](https://cdn.openai.com/pdf/a253471f-8260-40c6-a2cc-aa93fe9f142e/economic-research-chatgpt-usage-paper.pdf)).
- **Earlier text:** "Mid-2025: 72% non-work prompts, 28% work prompts"
  **Correction:** The paper's table gives 27% work in June 2025, a 43% relative decline from 47% ([OpenAI paper, Sep 2025](https://cdn.openai.com/pdf/a253471f-8260-40c6-a2cc-aa93fe9f142e/economic-research-chatgpt-usage-paper.pdf)).
- **Earlier text:** "Change: Work usage declined from 47% → 28% (40% relative decline)"
  **Correction:** The paper gives 27% for June 2025 ([OpenAI paper](https://cdn.openai.com/pdf/a253471f-8260-40c6-a2cc-aa93fe9f142e/economic-research-chatgpt-usage-paper.pdf)).
- **Earlier text:** "Work usage declining in percentage terms (47% → 28%)"
  **Correction:** The paper gives 27% for June 2025 ([OpenAI paper](https://cdn.openai.com/pdf/a253471f-8260-40c6-a2cc-aa93fe9f142e/economic-research-chatgpt-usage-paper.pdf)).

## Landing pages {#landing}

- **Earlier text:** "Software engineering: Claude Opus 4.5 exceeds best human performance on real-world coding tasks (Anthropic)"
  **Correction:** The human comparison was a separate Anthropic exam, not SWE-bench.
- **Earlier text:** "Professional tasks: AI completes authentic work deliverables 100x faster and 100x cheaper than experts (OpenAI)"
  **Correction:** A naive ratio. With human review the paper gives 1.12x faster and 1.18x cheaper for GPT-5 ([GDPval paper](https://cdn.openai.com/pdf/d5eb7428-c4e9-4a33-bd86-86dd4bcf12ce/GDPval.pdf)).
- **Earlier text:** "Improvement rate: Model capabilities doubled in 14 months (GPT-4o → GPT-5) (OpenAI)"
  **Correction:** The paper's win rates are 12.5% for GPT-4o and 39.0% for GPT-5 ([GDPval paper](https://cdn.openai.com/pdf/d5eb7428-c4e9-4a33-bd86-86dd4bcf12ce/GDPval.pdf)).
- **Earlier text:** "AI achieves expert parity on ~50% of professional tasks (Fortune)"
  **Correction:** The paper gives 47.6% for Claude Opus 4.1 and 39.0% for GPT-5 ([GDPval paper](https://cdn.openai.com/pdf/d5eb7428-c4e9-4a33-bd86-86dd4bcf12ce/GDPval.pdf)).
- **Earlier text:** "100x speed and cost advantage over human experts (OpenAI)"
  **Correction:** A naive ratio. With human review the paper gives 1.12x faster and 1.18x cheaper for GPT-5 ([GDPval paper](https://cdn.openai.com/pdf/d5eb7428-c4e9-4a33-bd86-86dd4bcf12ce/GDPval.pdf)).
- **Earlier text:** "McKinsey: $4.4 trillion annual economic impact potential (McKinsey)"
  **Correction:** This is the top of a $2.6 to $4.4 trillion range from June 2023 ([McKinsey](https://www.mckinsey.com/capabilities/mckinsey-digital/our-insights/the-economic-potential-of-generative-ai-the-next-productivity-frontier)).
- **Earlier text:** "PWC: $15.7 trillion global contribution by 2030"
  **Correction:** This figure could not be traced to an open PwC page in November 2026. Do not cite it.
- **Earlier text:** "SWE-bench Verified: Claude Opus 4.5 at 80.9% (first to exceed best human) (Anthropic)"
  **Correction:** The human comparison was a separate Anthropic exam.
- **Earlier text:** "Counterpoint: METR study found experienced devs 19% slower with AI assistance (METR)"
  **Correction:** METR's February 2026 follow-up reports different estimates and calls its data an unreliable signal. See the current page.
- **Earlier text:** "73% of ChatGPT use is personal/advisory (augmentation-focused) (OpenAI)"
  **Correction:** The 73% is the non-work share in June 2025. Asking was 49% ([OpenAI paper](https://cdn.openai.com/pdf/a253471f-8260-40c6-a2cc-aa93fe9f142e/economic-research-chatgpt-usage-paper.pdf)).
- **Earlier text:** "ChatGPT: Consumer dominance (59.7% market share), personal advisor role, 700M+ WAU (SQ Magazine, Index.dev)"
  **Correction:** The share figures in this list came from aggregators and could not be traced to a primary source. Do not cite them.
- **Earlier text:** "Gender parity achieved: ChatGPT now 52.4% female (vs male-dominated in Jan 2024) (OpenAI)"
  **Correction:** About 52% among users with classifiable names, inferred from names, by July 2025.
- **Earlier text:** "Age concentration: 53.24% of ChatGPT users are 18-34 years old (DemandSage)"
  **Correction:** From an aggregator, not a primary source. Do not cite it.
- **Earlier text:** "Emerging economies leading growth: India, Brazil, Mexico, South Africa have highest adoption rates (Modern Diplomacy)"
  **Correction:** This holds only for the 14-country OECD-Cisco poll. See the current page.
- **Earlier text:** "Extreme disparities: Singapore 4.6x AUI vs Nigeria 0.20x (23x gap) (Anthropic)"
  **Correction:** This compares Claude.ai usage per working-age person, not AI use in general.
- **Earlier text:** "Adoption: Gemini 63% enterprise (SQ Magazine), 72% of companies use AI (Menlo Ventures), 90%+ Fortune 500 on Copilot (Microsoft)"
  **Correction:** The Gemini share came from an aggregator, the linked Menlo page does not contain the 72%, and the 90% counts organisations with any use. Do not cite them as adoption rates.
- **Earlier text:** "Industry leaders: IT & telecom (38%), retail (31%), financial services (24%) (Menlo Ventures)"
  **Correction:** The linked Menlo page does not contain these figures. See the [Census Bureau](https://www.census.gov/library/stories/2026/05/ai-use-businesses.html) for sector rates.
- **Earlier text:** "Consumer shift: ChatGPT 73% personal tasks, becoming advisor vs work tool (OpenAI)"
  **Correction:** The 73% is the non-work share in June 2025.
- **Earlier text:** "Work → Personal: ChatGPT non-work 53% → 72% (mid-2024 → mid-2025) (OpenAI)"
  **Correction:** The paper gives 73% for June 2025.
- **Earlier text:** "Automation rising: Claude automation 27% → 39% (late 2024 → Aug 2025) (Anthropic)"
  **Correction:** The directive share fell to 32% by November 2025. See the current page.
- **Earlier text:** "Global Paradox: Emerging economies growing 4x faster but usage 23x lower (OpenAI, Anthropic)"
  **Correction:** The 23x compares Claude.ai usage per working-age person, not AI use in general.
- **Earlier text:** "Teen Adoption: 64% of U.S. teens use AI chatbots, 28% daily (Pew Research)"
  **Correction:** Pew's text says about three in ten daily.
- **Earlier text:** "Enterprise Standard: 90%+ Fortune 500 using Microsoft Copilot (Microsoft)"
  **Correction:** Vendor-reported, counting organisations with any use, not the share of employees.
- **Earlier text:** "1. Longitudinal patterns: Need data beyond 2025 to confirm trend continuation"
  **Correction:** 2026 reports from Anthropic, OpenAI and Google now extend beyond 2025.
- **Earlier text:** "Significance: AI exceeds average PhD student in multi-domain science"
  **Correction:** The baselines behind this comparison are corrected on this log.
- **Earlier text:** "Significance: AI approaching half of frontier knowledge performance"
  **Correction:** The expert baseline is corrected on this log, and newer scores are in the update.
- **Earlier text:** "2027: Majority of professional tasks at expert level"
  **Correction:** This was a projection, not a finding.
- **Earlier text:** the usage track statistics table (Gemini 82M, market shares, Claude 300M, Gemini 63% enterprise)
  **Correction:** Alphabet stated over 450 million monthly Gemini users for Q2 2025 ([Alphabet, Jul 23, 2025](https://blog.google/inside-google/message-ceo/alphabet-earnings-q2-2025/)). The other figures came from aggregators and could not be traced to a primary source. Do not cite them.
- **Earlier text:** the capabilities cross-lab benchmark table and economic projections
  **Correction:** The table mixed model versions. The 61.4% OSWorld score was reported for Claude Sonnet 4.5 ([Anthropic, Sep 29, 2025](https://www.anthropic.com/news/claude-sonnet-4-5)). The PwC and market size rows could not be traced to an open primary source.


**Last Updated**: 2026-11-01
