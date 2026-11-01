**[← AI Impact Research](../../)** · **[AI Capabilities Research](../)**

---

# Agentic Capabilities

> **Archived text from December 2025.** This page is not kept up to date, and it holds figures the [corrections log](../../../../corrections.md) marks as wrong or unsourced. Do not cite it as current. See the [current page](../../../../ai-capabilities-research/05-agentic-capabilities/README.md).


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
