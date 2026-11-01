**← [Back to Overview](./README.md)** | **[Sources →](./sources.md)**

---

# Automation vs Augmentation: Detailed Data

## November 2026 evidence

*Updated November 1, 2026. The November 2026 section is current. Everything after it is the December 2025 compilation, kept as dated history. Superlatives and words like "latest", "leading" or "now" in that older text describe December 2025.*

- OpenAI's Enterprise Signals reports Codex generated 64% of combined Codex and ChatGPT output tokens among enterprise customers as of June 2026, and frontier firms (top 10% of usage) generate 8.3 times the output tokens per active user of typical firms, up from 2.6 times in January. ([OpenAI, Aug 12, 2026](https://openai.com/index/how-enterprises-put-ai-to-work/)) *Method: Vendor-reported enterprise telemetry, output tokens are a proxy for depth, and agentic workflows emit more tokens by design (OpenAI says so).*
- OpenAI reports that across countries people are more than twice as likely to use consumer ChatGPT to do a task or create something (doing) at work than outside work, where asking stays the largest category. ([OpenAI, Aug 6, 2026](https://openai.com/index/how-the-world-is-putting-chatgpt-to-work/)) *Method: OpenAI Signals, Free/Go/Plus/Pro individual accounts only, Q2 2026 country data, excludes Codex and enterprise, vendor-reported.*
- Google's ATLAS study of about 15 million Gemini App, AI Mode and Gemini API interactions (April 6 to 19, 2026) found end-to-end automation under 10% of non-routine cognitive work conversations and use that is overwhelmingly collaborative. ([Google, Jul 22, 2026](https://arxiv.org/abs/2608.00038)) *Method: ArXiv preprint by Google authors, 14,653,926 interactions, Apr 6-19 2026, Workspace enterprise excluded, classifier-based and the authors call the intent split not definitive.*
- In Anthropic's linked survey of about 9,700 Claude users (usage mid-May to early June 2026), people who delegate most to Claude were the most optimistic about pay, job security and meaning, and heavier delegators reported learning at the same rate as others. ([Anthropic, Jun 26, 2026](https://www.anthropic.com/research/economic-index-june-2026-report)) *Method: N about 9,700 linked respondents with 5+ sessions, survey not representative (about 30% computer and mathematical occupations, 12% women), self-reported, selection not ruled out.*
- Anthropic reports that AI autonomy is higher in Claude Code than in chat and Cowork for 26 of 31 output types, by 0.37 points on a 1 to 5 scale on average; a blog-post task takes a median 13 chat rounds but a single prompt in Claude Code. ([Anthropic, Jun 26, 2026](https://www.anthropic.com/research/economic-index-june-2026-report)) *Method: Chat and Cowork vs Claude Code sessions, mid-2026 sample, model-judged autonomy scale, gap persists within the same model (Sonnet: 0.26 points).*
- In about 400,000 Claude Code sessions (October 2025 to April 2026), people made about 70% of the planning decisions but only about 20% of the execution decisions. ([Anthropic, Jun 16, 2026](https://www.anthropic.com/research/claude-code-expertise)) *Method: About 400,000 interactive sessions from about 235,000 people, Oct 2025 to Apr 2026, Claude Code via CLI, Claude.ai and desktop, classifier-attributed decisions, vendor-reported.*
- OpenAI's Codex paper found Codex made up 99.8% of output tokens across Codex and ChatGPT among OpenAI workers, 63.3% among organizational users and 16.5% among individual users as of June 11, 2026. ([OpenAI, Jun 2026](https://cdn.openai.com/pdf/5d1e1489-21c0-43e4-9d42-f87efdbf0082/the-shift-to-agentic-ai-evidence-from-codex.pdf)) *Method: Vendor-reported usage telemetry, OpenAI staff are unrepresentative by the authors' own statement.*
- Anthropic's February 2026 sample (Feb 5 to 12, about 1 million Claude.ai conversations) showed augmentation up slightly on Claude.ai and automation down sharply in first-party API data, with coding moving from Claude.ai to the API. ([Anthropic, Mar 24, 2026](https://www.anthropic.com/research/economic-index-march-2026-report)) *Method: Claude.ai and 1P API, 1M conversations sampled from each, Feb 5-12 2026.*
- Anthropic found that Claude users with 6 or more months of tenure use Claude more collaboratively and have a 10% higher conversation success rate, and Anthropic says this contradicts its own 2025 guess that automated use is more typical of experienced users. ([Anthropic, Mar 24, 2026](https://www.anthropic.com/research/economic-index-march-2026-report)) *Method: Claude.ai, February 2026.*
- Anthropic measured users granting Claude Code more autonomy with experience: full auto-approve rose from roughly 20% of sessions for new users to over 40% for experienced users, and the 99.9th percentile turn length nearly doubled from under 25 to over 45 minutes between October 2025 and January 2026. ([Anthropic, Feb 18, 2026](https://www.anthropic.com/research/measuring-agent-autonomy)) *Method: Interactive Claude Code sessions, users who signed up after 2025-09-19, vendor-reported, software engineering dominates the sample.*
- Anthropic's November 2025 sample found augmentation back ahead of automation on Claude.ai (52% augmented, 45% automated), reversing the August 2025 result in which automation was ahead. ([Anthropic, Jan 15, 2026](https://www.anthropic.com/research/anthropic-economic-index-january-2026-report)) *Method: Claude.ai conversations, November 2025 sample, Anthropic classifier, vendor-reported.*
- Anthropic's directive share (reported on this page in December 2025 as 27% to 39%) fell back from 39% in August 2025 to 32% in November 2025, and Anthropic says the August spike overstated how fast automation was growing, while the January 2025 to November 2025 direction still points to more automation. ([Anthropic, Jan 15, 2026](https://www.anthropic.com/research/anthropic-economic-index-january-2026-report)) *Method: Claude.ai, directive mode only (one of the two automation modes).*
- In Anthropic's November 2025 sample, first-party API traffic was 64% directive and about three-quarters automation, against 32% directive and under half automation on Claude.ai. ([Anthropic, Jan 15, 2026](https://www.anthropic.com/research/anthropic-economic-index-january-2026-report)) *Method: 1P API vs Claude.ai, November 2025, the September 2025 report's 77% API automation figure was August 2025 data.*

4 corrections to the December 2025 text on this page are marked in place below, labelled "Corrected November 1, 2026".

---

## Definitions

### Automation (Directive) - Anthropic Framework
- Task completion with minimal user input
- Feedback loops
- Full task delegation
- "Give AI a job and let it run"

### Augmentation (Collaborative) - Anthropic Framework
- Interactive collaboration
- Learning together
- Task iteration
- Validation processes
- Back-and-forth dialogue

---

## Historical Trends

### [Anthropic Economic Index](https://www.anthropic.com/research/anthropic-economic-index-september-2025-report) (Claude)

**Temporal Shift in Interaction Patterns:**
- Late 2024: 27% directive conversations
- August 2025: 39% directive conversations
- **Significance**: First report where automation approached/exceeded augmentation
- **Interpretation**: Growing user confidence in delegating full tasks to AI

**Business API Usage:**
- 77% of enterprise API use involves automation patterns
- Full task delegation is the dominant enterprise pattern
- Business-focused interactions concentrated in:
  - Coding: 44% of API use
  - Administrative support: Significant portion

### [OpenAI ChatGPT Usage Study](https://openai.com/index/how-people-are-using-chatgpt/)

**Work vs Personal Shift:**
- Mid-2024: 53% non-work prompts
- Mid-2025: 72% non-work prompts
- **Interpretation**: ChatGPT becoming more of a personal advisor than work automation tool

**Message Categories:**
- "Asking" (seeking advice): 49% of messages
- "Doing" (task-oriented): 40% of messages
  - Includes drafting text, planning, programming

**Overall Positioning:**
- 73% usage for personal tasks *Corrected November 1, 2026: The 73% is the non-work share in June 2025, and Asking is a separate 49% ([OpenAI paper, Sep 2025](https://cdn.openai.com/pdf/a253471f-8260-40c6-a2cc-aa93fe9f142e/economic-research-chatgpt-usage-paper.pdf)).*
- Users value it as real-time advisor for decision-making > automation tool
- Pattern suggests augmentation/advisory use dominates consumer behavior

---

## Platform-Specific Patterns

### ChatGPT (OpenAI)
**Primary Use Mode:** Augmentation/Advisory
- Top uses: Practical guidance, seeking information, writing
- Real-time advisor for life decisions
- Interactive question-answer patterns dominate
- Lower automation, higher collaboration

### Claude (Anthropic)
**Primary Use Mode:** Automation
- 36% of conversations: Software development
- 77% of business API: Full task delegation *Corrected November 1, 2026: The 77% covers all automation patterns in August 2025, not only full delegation ([Anthropic, Sep 15, 2025](https://www.anthropic.com/research/anthropic-economic-index-september-2025-report)). The directive share alone was 64% in November 2025 ([Anthropic, Jan 15, 2026](https://www.anthropic.com/research/anthropic-economic-index-january-2026-report)).*
- "Set it and forget it" pattern emerging
- Higher automation, especially in enterprise contexts

### Microsoft Copilot
**Hybrid Model:**
- **Desktop usage**: Co-worker pattern (collaborative)
  - Information retrieval (most popular)
  - Assistance with work tasks
  - Iterative refinement

- **Mobile usage**: Advisor pattern (augmentation)
  - Health and wellness tracking
  - Life management advice
  - Personal decision support

**Context Matters:**
- Same tool, different interaction patterns based on device/context
- Desktop = automation for work
- Mobile = augmentation for life

### Google Gemini
**Enterprise Integration Focus:**
- 63% enterprise users
- Deep workspace integration suggests automation patterns
- Workflow embedding rather than standalone consultation

---

## Quantified Productivity Impacts

### [Microsoft Copilot](https://microsoft.ai/news/its-about-time-the-copilot-usage-report-2025/) - Workplace Productivity Research

**Early Adopter Study:**
- 70% felt more productive
- 29% faster in searching, writing, summarizing
- Caught up on missed meetings 4x faster
- 85% reach good first draft faster

**[New Employee Integration Study](https://www.microsoft.com/en-us/research/publication/new-employee-copilot-usage-insights-into-productivity-and-socialization/) (125 Microsoft interns):**
- Higher Copilot usage → better socialization
- Higher usage → stronger team identification
- Dramatic efficiency gains: "Hours → minutes on tasks"
- Most valued use cases:
  1. Information retrieval
  2. Writing assistance
  3. Coding assistance

---

## The Great Divergence

### Key Finding from [Fortune](https://fortune.com/2025/09/15/openai-chatgpt-claude-anthropic-work-personal-use-new-data/), [Bloomberg](https://www.bloomberg.com/news/articles/2025-09-15/anthropic-finds-businesses-are-mainly-using-ai-to-automate-work), [The Neuron](https://www.theneuron.ai/explainer-articles/a-tale-of-two-ais-how-new-reports-from-openai-and-anthropic-reveal-a-global-split-in-ais-revolution) Analysis

**Two Parallel AI Revolutions:**
1. **Individual Users**: AI as personal advisor for life decisions
   - Augmentation dominant
   - ChatGPT leading this category
   - Interactive, consultative patterns
   - Focus on guidance and decision support

2. **Business Users**: AI as automation engine for work
   - Automation dominant
   - Claude leading this category
   - Directive, task-completion patterns
   - Focus on efficiency and output

**Interpretation:**
- ChatGPT emerging as personal/exploratory tool
- Claude emerging as work-focused productivity tool
- Different platforms optimizing for different interaction paradigms
- User expectations diverging by context (work vs personal)

---

## Implications for Research

### Labor Market Questions
- If businesses prefer automation (77%), what happens to jobs that can be fully delegated?
- Does augmentation create new skilled labor categories?
- Is the automation/augmentation split permanent or transitional?

### Technology Development
- Will platforms continue to specialize?
- Is there a winner-take-all dynamic forming?
- Can one platform serve both automation and augmentation well?

### User Behavior
- What drives users to choose automation vs augmentation?
- Does automation reduce skill development?
- Does augmentation enhance learning outcomes?

### Measurement Challenges
- How to classify hybrid interactions?
- Does device/context shift interaction mode?
- Are current frameworks (Anthropic's definitions) sufficient?

---

## Data Gaps

1. **Longitudinal patterns**: Need data beyond 2025 to confirm trend continuation *Corrected November 1, 2026: 2026 reports from Anthropic, OpenAI and Google now extend beyond 2025.*
2. **Cross-platform usage**: Do users use different platforms for different modes?
3. **Skill-level correlation**: Does expertise affect automation vs augmentation preference?
4. **Task complexity**: Which types of tasks favor automation vs augmentation?
5. **Industry variation**: Does automation dominance vary by sector?

---

## Statistical Summary

| Platform | Automation Dominance | Augmentation Dominance | Primary Context |
|----------|---------------------|------------------------|----------------|
| Claude API | 77% | 23% | Business/Enterprise |
| ChatGPT | ~27% | ~73% | Personal/Consumer |
| Copilot Desktop | Moderate | Moderate | Workplace |
| Copilot Mobile | Low | High | Personal Life |

*Corrected November 1, 2026: The API split is 77% automation and 12% augmentation, not 23% augmentation ([Anthropic, Sep 15, 2025](https://www.anthropic.com/research/anthropic-economic-index-september-2025-report)).*

*Corrected November 1, 2026: The 27% and 73% are OpenAI's work and non-work shares, not automation and augmentation. OpenAI's own split is Asking 49%, Doing 40%, Expressing 11% ([OpenAI paper, Sep 2025](https://cdn.openai.com/pdf/a253471f-8260-40c6-a2cc-aa93fe9f142e/economic-research-chatgpt-usage-paper.pdf)).*

**Trend Direction:** ↑ Automation (27% → 39% in Anthropic data, late 2024 → Aug 2025)
