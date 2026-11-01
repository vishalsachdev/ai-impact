**View this research at [vishalsachdev.github.io/ai-impact](https://vishalsachdev.github.io/ai-impact/)**

# AI Impact Research

Comprehensive research on AI from frontier labs: usage patterns, capabilities, trajectories, and implications for higher education.

## November 2026 update

**Updated November 1, 2026.** This site now includes evidence published through October 2026. Findings from the December 2025 compilation stay below as dated history, with known errors marked in place.

### How people use AI

- **Reach:** OpenAI says more than 1.2 billion people use ChatGPT each week ([OpenAI, Oct 7, 2026](https://openai.com/index/gpt-6-for-everyone/)). Alphabet says the Gemini app is at one billion users ([Google, Oct 28, 2026](https://blog.google/company-news/inside-google/message-ceo/alphabet-earnings-q3-2026/)). Pew found 49% of U.S. adults use chatbots, up from 33% in 2024, though the question wording changed ([Pew Research Center, Jun 17, 2026](https://www.pewresearch.org/internet/2026/06/17/americans-and-ai-2026-chatbots-smart-devices-and-views-on-impact/)).
- **Automation:** The August 2025 automation spike did not hold. Anthropic's November 2025 sample shows augmentation back ahead, 52% to 45% ([Anthropic, Jan 15, 2026](https://www.anthropic.com/research/anthropic-economic-index-january-2026-report)). Google's own study found end-to-end automation under 10% of non-routine cognitive work conversations ([Google, Jul 22, 2026](https://arxiv.org/abs/2608.00038)).
- **Global gap:** Microsoft's telemetry puts use at 28.8% of working-age people in the Global North and 16.2% in the Global South, a gap of 12.6 points, up from 10.6 in H2 2025 ([Microsoft AI Economy Institute, Sep 21, 2026](https://www.microsoft.com/en-us/research/wp-content/uploads/2026/09/Microsoft-AI-Diffusion-Report-2026-Q2.pdf)).
- **Gender:** Pew finds the gap in ever-use has closed (50% of men, 47% of women), but men use chatbots daily more often, 27% to 20% ([Pew Research Center, Jun 17, 2026](https://www.pewresearch.org/internet/2026/06/17/the-gender-gap-in-ai/)).

### What AI can do

- **Benchmarks change fast.** OpenAI stopped reporting SWE-bench Verified after finding flaws in 59.4% of 138 audited problems that o3 did not consistently solve ([OpenAI, Feb 23, 2026](https://openai.com/index/why-we-no-longer-evaluate-swe-bench-verified/)). Epoch AI fixed errors in 42% of FrontierMath problems, so older scores are not comparable ([Epoch AI, Jun 12, 2026](https://epoch.ai/benchmarks/frontiermath)).
- **Long tasks remain hard.** The best agent listed on the OSWorld 2.0 page, Claude Opus 4.8, completes 20.6% of long-horizon computer tasks ([XLANG Lab, undated page, read Nov 1, 2026](https://osworld-v2.xlang.ai/)). The top Remote Labor Index score is 21.25% of freelance projects ([Scale AI, undated page, read Nov 1, 2026](https://www.scale.com/leaderboard/rli)).
- **Vendors disagree about the same model.** Google lists GPT-6 Astra at 34.2% on Agent's Last Exam, while OpenAI lists 59.3% on a benchmark of the same name ([Google DeepMind, Oct 13, 2026](https://deepmind.google/models/model-cards/gemini-4-argon/); [OpenAI, GPT-6 Astra page, undated](https://openai.com/index/gpt-6-astra/)).
- **Learning evidence conflicts.** A randomized trial of a course-integrated AI tutor with 2,379 students found no significant grade effect in the full sample, and a 0.37 standard deviation drop among sections of the same course ([IZA Institute of Labor Economics, Oct 2026](https://docs.iza.org/dp18989.pdf)). A proctored experiment with 211 students found higher test scores with open generative AI access ([arXiv, Jul 9, 2026](https://arxiv.org/pdf/2607.08849)). Both are unreviewed papers.
- **Labor and productivity.** A Federal Reserve governor said there is limited evidence so far that AI is changing the structure of the labor market ([Federal Reserve, Sep 28, 2026](https://www.federalreserve.gov/newsevents/speech/cook20260928a.htm)).

**How this update was made.** Every added number was read on its primary source page, or on a copy named in the method note, on November 1, 2026. Sources that could not be opened were left out. The research was done with Claude, an Anthropic model, and Anthropic's models and reports are subjects here, so vendor-reported numbers are labelled throughout.

---

## Two Research Tracks

This repository contains two complementary research compilations:

| Track | Focus | Audience |
|-------|-------|----------|
| **[AI Usage Research](ai-usage-research/)** | How people use AI | General |
| **[AI Capabilities Research](ai-capabilities-research/)** | What AI can do | University stakeholders |

---

## AI Usage Research

**How people use AI platforms from Anthropic, OpenAI, Google, and Microsoft.**

**[View Full Research →](ai-usage-research/)**

### Quick Links

- [01. Automation vs Augmentation](ai-usage-research/01-automation-vs-augmentation/)
- [02. Platform Specialization](ai-usage-research/02-platform-specialization/)
- [03. Demographics & Adoption](ai-usage-research/03-demographics-adoption/)
- [04. Global Inequality](ai-usage-research/04-global-inequality/)
- [05. Enterprise vs Consumer](ai-usage-research/05-enterprise-vs-consumer/)
- [06. Use Case Evolution](ai-usage-research/06-use-case-evolution/)

### Key Findings (December 2025, kept as history)

- **Gender Parity Achieved**: ChatGPT 52.4% female users (fastest of any major tech; corrected in the track pages: about 52%, inferred from names) ([OpenAI](https://openai.com/index/how-people-are-using-chatgpt/))
- **Automation Rising**: Claude directive usage 27% → 39% (2024-2025; fell to 32% by November 2025) ([Anthropic](https://www.anthropic.com/research/anthropic-economic-index-september-2025-report))
- **Global Paradox**: Emerging economies growing 4x faster but usage 23x lower ([OpenAI](https://openai.com/index/how-people-are-using-chatgpt/), [Anthropic](https://www.anthropic.com/research/anthropic-economic-index-september-2025-report)) *Corrected November 1, 2026: the 23x compares Claude.ai usage per working-age person, not AI use in general.*
- **Teen Adoption**: 64% of U.S. teens use AI chatbots, 28% daily ([Pew Research](https://www.pewresearch.com/internet/2025/12/09/teens-social-media-and-ai-chatbots-2025/)) *Corrected November 1, 2026: Pew's text says about three in ten daily.*
- **Enterprise Standard**: 90%+ Fortune 500 using Microsoft Copilot ([Microsoft](https://www.microsoft.com/en-us/microsoft-365/blog/2025/11/18/microsoft-ignite-2025-copilot-and-agents-built-to-power-the-frontier-firm/)) *Corrected November 1, 2026: vendor-reported, counting organisations with any use, not the share of employees.*

---

## AI Capabilities Research

**What AI can do: benchmarks, trajectories, and educational implications.**

**[View Full Research →](ai-capabilities-research/)**

### Quick Links

- [01. Real-World Task Performance](ai-capabilities-research/01-real-world-task-performance/)
- [02. Capability Trajectory & Economic Impact](ai-capabilities-research/02-capability-trajectory/)
- [03. Academic Task Benchmarks](ai-capabilities-research/03-academic-task-benchmarks/)
- [04. Coding and Research](ai-capabilities-research/04-coding-and-research/)
- [05. Agentic Capabilities](ai-capabilities-research/05-agentic-capabilities/)
- [06. Safety and Alignment](ai-capabilities-research/06-safety-and-alignment/)
- [07. Educational Implications](ai-capabilities-research/07-educational-implications/)

### Key Findings (December 2025, kept as history)

- **Expert Parity**: ~50% of professional tasks at expert level (corrected in the track pages: 47.6% for Claude Opus 4.1, 39.0% for GPT-5) ([OpenAI GDPval](https://openai.com/index/gdpval/))
- **Coding Leader, November 2025**: Claude Opus 4.5 at 80.9% SWE-bench (the human comparison was a separate Anthropic exam) ([Anthropic](https://www.anthropic.com/news/claude-opus-4-5))
- **PhD-Level Science**: Gemini 3 at 93.8% on GPQA Diamond ([Google](https://blog.google/products/gemini/gemini-3/))
- **100x Advantage**: AI completes tasks 100x faster and cheaper than experts (a naive ratio; corrected in the track pages to 1.12x faster and 1.18x cheaper with human review) ([OpenAI](https://openai.com/index/gdpval/))
- **Rapid Improvement**: Capabilities doubled in 14 months (GPT-4o → GPT-5; corrected in the track pages: win rates of 12.5% and 39.0%) ([OpenAI](https://openai.com/index/gdpval/))

---

## Data Sources

**150+ sources** from the December 2025 compilation, plus **134 primary sources** added in November 2026, across both research tracks:

- **Primary Research**: [OpenAI GDPval](https://openai.com/index/gdpval/), [Anthropic Economic Index](https://www.anthropic.com/research/anthropic-economic-index-september-2025-report), [Microsoft Copilot Analysis](https://microsoft.ai/news/its-about-time-the-copilot-usage-report-2025/)
- **Benchmarks**: SWE-bench, GPQA, AIME, OSWorld
- **Economic**: [McKinsey](https://www.mckinsey.com/capabilities/mckinsey-digital/our-insights/the-economic-potential-of-generative-ai-the-next-productivity-frontier), PWC, [IMF](https://www.imf.org/en/publications/wp/issues/2025/04/04/ai-adoption-and-inequality-565729) projections
- **Demographics**: [Pew Research](https://www.pewresearch.com/internet/2025/12/09/teens-social-media-and-ai-chatbots-2025/), UN, OECD
- **Industry**: News analysis, platform comparisons

---

## For University Stakeholders

This research is designed to inform higher education decision-making:

| Role | Start Here |
|------|------------|
| Administrators | [Capability Trajectory](ai-capabilities-research/02-capability-trajectory/), [Educational Implications](ai-capabilities-research/07-educational-implications/) |
| Faculty | [Academic Benchmarks](ai-capabilities-research/03-academic-task-benchmarks/), [Coding & Research](ai-capabilities-research/04-coding-and-research/) |
| Curriculum Designers | [Educational Implications](ai-capabilities-research/07-educational-implications/), [Real-World Tasks](ai-capabilities-research/01-real-world-task-performance/) |
| Policy Makers | [Safety & Alignment](ai-capabilities-research/06-safety-and-alignment/), [Usage Patterns](ai-usage-research/) |

---

**Last Updated**: 2026-11-01
