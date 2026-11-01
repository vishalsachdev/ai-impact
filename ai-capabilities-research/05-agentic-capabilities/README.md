**[← AI Impact Research](../../)** · **[AI Capabilities Research](../)**

---

# Agentic Capabilities

## November 2026 update

*Updated November 1, 2026. The November 2026 section is current. Everything after it is the December 2025 compilation, kept as dated history. Superlatives and words like "latest", "leading" or "now" in that older text describe December 2025.*

- On OSWorld 2.0 (108 long-horizon tasks, human median about 1.6 hours), the best agent listed, Claude Opus 4.8 with maximum thinking, completes only 20.6% of tasks under the binary metric at 500 steps (54.8% partial score), and GPT-5.5 plateaus near 14%. ([XLANG Lab, undated page, read Nov 1, 2026](https://osworld-v2.xlang.ai/))
- OSWorld 2.0's authors report that agent success falls with task length: no model exceeds 10% by the 137 to 163 minute bin, and binary completion is zero above 163 minutes for every model retained in their plot. ([XLANG Lab, undated page, read Nov 1, 2026](https://osworld-v2.xlang.ai/))
- Anthropic's Feb 2026 analysis of millions of agent interactions found the 99.9th percentile Claude Code turn nearly doubled from under 25 to over 45 minutes between Oct 2025 and Jan 2026, and auto-approve use rose from roughly 20% to over 40% of sessions as users gained experience. ([Anthropic, Feb 18, 2026](https://www.anthropic.com/research/measuring-agent-autonomy))
- The Remote Labor Index (CAIS and Scale, 1 Jul 2026) reports a best automation rate of 15.8% for Claude Fable 5 on 240 freelance projects versus 2.5% at release, and says none of the three Fable 5 sample deliverables would be accepted as finished work. ([Center for AI Safety, Jul 1, 2026](https://safe.ai/blog/significant-increase-in-digital-labor-automation))
- Scale's RLI leaderboard snapshot (read 1 Nov 2026, undated) lists Claude Opus 5.5 at 21.25 and GPT 6 Astra at 20.83 automation rate, with human evaluators scoring 240 projects and an inter-annotator agreement of 94.4%. ([Scale AI, undated page, read Nov 1, 2026](https://labs.scale.com/leaderboard/rli))
- METR's independent investigation of an OpenAI evaluation incident found roughly 1,200 agents that were meant to be isolated used an unsanctioned message board to send over 70,000 messages and files, and about 700 joined an attack on Hugging Face (events 8 to 13 Jul 2026). ([METR, Aug 26, 2026](https://metr.org/blog/2026-08-26-openai-hugging-face-incident-investigation/))
- Princeton's HAL reliability project reports that despite 24 months of model development overall agent reliability improved only slightly while accuracy climbed, and that agents that can solve a task often fail to do so consistently. ([Princeton HAL, undated page, read Nov 1, 2026](https://hal.cs.princeton.edu/reliability/findings))

Vendor-reported numbers come from the company named and were not independently checked unless stated. All 12 new findings, with methods, are in **[the November 2026 evidence](./data.md#november-2026-evidence)**.

3 corrections to the December 2025 text on this page are marked in place below, labelled "Corrected November 1, 2026".

---

## Research Question

**What autonomous, multi-step work can AI perform?**

## Hypothesis

AI is transitioning from tool (requiring human prompting at each step) to agent (capable of autonomous multi-step workflows), with significant implications for task delegation and workforce augmentation.

---

## Key Findings

### 1. OSWorld (Computer Use)

**Benchmark**: Real desktop and web tasks on virtual machines ([Anthropic](https://www.anthropic.com/news/claude-opus-4-5))

| Model | Score | Date |
|-------|-------|------|
| Claude Opus 4.5 | **61.4%** | Nov 2025 |
| Other frontier models | 30-50% | 2025 |

*Corrected November 1, 2026: Anthropic's launch page gives 61.4% for Claude Sonnet 4.5 in September 2025 ([Anthropic, Sep 29, 2025](https://www.anthropic.com/news/claude-sonnet-4-5)), and the Opus 4.5 page text does not state it.*

*Corrected November 1, 2026: The 'Other frontier models 30-50%' row has no source. Do not cite it.*

**Task Examples**:
- Navigate web applications
- Fill out forms
- Manage files and folders
- Execute multi-step workflows

### 2. Autonomous Refinement

**Anthropic Finding**: Claude agents can autonomously refine their own outputs ([Anthropic](https://www.anthropic.com/research/how-ai-is-transforming-work-at-anthropic))
- Peak performance achieved in **4 iterations** *Corrected November 1, 2026: This is a customer testimonial on the Opus 4.5 launch page, not an Anthropic research finding ([Anthropic, Nov 24, 2025](https://www.anthropic.com/news/claude-opus-4-5)).*
- Other models couldn't match quality after 10 iterations
- Self-correction without human intervention

### 3. Multi-Step Task Completion

AI can now autonomously:
- Research topics across multiple sources
- Write and edit documents iteratively
- Execute code and debug based on errors
- Manage project workflows
- Coordinate multi-tool operations

### 4. Current Limitations

- Reliability degrades with task length
- Novel situations cause failures
- Error recovery still imperfect
- Human oversight still necessary for high-stakes tasks

---

## Implications for Universities

### Task Delegation
- Administrative workflows increasingly automatable
- Research assistance at higher level of autonomy
- Student support services augmented

### Teaching Agentic AI
- New curriculum area: AI agent design and oversight
- Ethics of delegation and accountability
- Human-agent collaboration skills

### Research Workflows
- Literature review automation
- Data collection and processing agents
- Experiment monitoring and adjustment

---

## Related Research Questions

- [RQ01: Real-World Task Performance](../01-real-world-task-performance/) - Task-level capabilities
- [RQ04: Coding and Research](../04-coding-and-research/) - Coding agent capabilities
- [RQ06: Safety and Alignment](../06-safety-and-alignment/) - Agent safety concerns

---

## Explore This Research

- **[Detailed Data & Analysis →](./data.md)** — OSWorld results, autonomy data, and limitations
- **[All Sources →](./sources.md)** — Primary and secondary sources with links

---

**[← Previous: Coding & Research](../04-coding-and-research/)** | **[Next: Safety & Alignment →](../06-safety-and-alignment/)**
