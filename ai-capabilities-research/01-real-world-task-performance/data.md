**← [Back to Overview](./README.md)** | **[Sources →](./sources.md)**

---

# Real-World Task Performance: Detailed Data

## November 2026 evidence

*Updated November 1, 2026. The November 2026 section is current. Everything after it is the December 2025 compilation, kept as dated history. Superlatives and words like "latest", "leading" or "now" in that older text describe December 2025.*

- Google's Gemini 4 Argon model card (Oct 13, 2026) lists Agent's Last Exam pass rate at 39.5% for Argon, 34.2% for GPT-6 Astra and 38.2% for Claude Opus 5.5, while OpenAI's GPT-6 Astra page reports 59.3% for Astra on a benchmark of the same name; methods or settings differ between the two vendors. ([Google DeepMind, Oct 13, 2026](https://deepmind.google/models/model-cards/gemini-4-argon/); [OpenAI, GPT-6 Astra page, undated](https://openai.com/index/gpt-6-astra/))
- Anthropic reports Claude Opus 5.5 at 1846 Elo on GDPval-AA v2.1 at max effort, against 1735 for Fable 5.1 and 1708 for Opus 5; the same table lists GPT-6 Astra at 1542 and GPT-5.6 Sol at 1588 (Sep 22, 2026). ([Anthropic, Sep 22, 2026](https://www.anthropic.com/claude-opus-5-5)) *Method: Vendor-reported using Artificial Analysis's GDPval-AA v2.1.*
- Anthropic's own Opus 5.5 launch page says benchmark margins at current capability levels are a less reliable guide to real-world differences, and that the gap between Opus 5.5 and Fable 5.1 is narrower in its own use than the scores suggest. ([Anthropic, Sep 22, 2026](https://www.anthropic.com/claude-opus-5-5)) *Method: Vendor statement, a counterweight to using single benchmark numbers in the cross-lab table.*
- From GPT-5.6 (Jul 9, 2026) OpenAI's launch table reports GDPval-AA v2, an Artificial Analysis Elo scale, instead of the GDPval win-or-tie rate: GPT-5.6 Sol 1,747.8, Claude Fable 5 1,759.6, GPT-5.5 1,493.7, Gemini 3.1 Pro Preview 962.3. ([OpenAI, Jul 9, 2026](https://openai.com/index/gpt-5-6/)) *Method: OpenAI-reported (vendor) result.*
- OpenAI's GPT-5.5 launch table reports GDPval wins-or-ties of 84.9% for GPT-5.5, 83.0% for GPT-5.4, 82.3% for GPT-5.5 Pro, 82.0% for GPT-5.4 Pro, 80.3% for Claude Opus 4.7 and 67.3% for Gemini 3.1 Pro (Apr 23, 2026); the OpenAI launch pages checked after this one report other benchmarks. ([OpenAI, Apr 23, 2026](https://openai.com/index/introducing-gpt-5-5/)) *Method: OpenAI-reported (vendor) result.*
- OpenAI reports that GPT-5.4 matched or beat industry professionals on 83.0% of GDPval comparisons, up from 70.9% for GPT-5.2 (Mar 5, 2026). ([OpenAI, Mar 5, 2026](https://openai.com/index/introducing-gpt-5-4/)) *Method: OpenAI-reported (vendor) result.*
- Anthropic reports that Claude Opus 4.6 scored about 144 Elo points above OpenAI's GPT-5.2 and 190 above Claude Opus 4.5 on GDPval-AA (Feb 5, 2026). ([Anthropic, Feb 5, 2026](https://www.anthropic.com/news/claude-opus-4-6)) *Method: Vendor-reported.*
- OpenAI reports that GPT-5.2 Thinking beat or tied industry professionals on 70.9% of GDPval comparisons judged by expert humans, against 38.8% for GPT-5 on the same measure (Dec 11, 2025). ([OpenAI, Dec 11, 2025](https://openai.com/index/introducing-gpt-5-2/)) *Method: OpenAI-reported (vendor) result.*
- Scale AI's Remote Labor Index (240 real freelance projects, 230 held private) lists Claude Opus 5.5 first at a 21.25% automation rate, with GPT 6 Astra at 20.83%, Fable 5.1 at 17.92% and Gemini Argon 4 at 17.08%. ([Scale AI, undated page, read Nov 1, 2026](https://www.scale.com/leaderboard/rli)) *Method: Page is undated, it lists Gemini Argon 4 (released Oct 13, 2026) as 'NEW', so it was updated after that.*
- At launch the Remote Labor Index top agent (Manus) completed only 2.5% of the projects to a client-acceptable standard, which Scale describes as near zero; later rows (Opus 5.5 21.25%) show the rate rising but still below one in four. ([Scale AI, undated page, read Nov 1, 2026](https://www.scale.com/leaderboard/rli)) *Method: Page undated.*
- Stanford's 2026 AI Index reports that top models score 60 to 90% on evaluations in tax, mortgage processing, corporate finance and legal reasoning, with the top 15 models separated by as little as 3 percentage points. ([Stanford HAI, undated page, read Nov 1, 2026](https://hai.stanford.edu/ai-index/2026-ai-index-report/technical-performance)) *Method: Compilation of third-party benchmarks, not a new measurement, the page says 'high competency and reliability are required remain a great challenge'.*

2 corrections to the December 2025 text on this page are marked in place below, labelled "Corrected November 1, 2026".

---

## [GDPval](https://openai.com/index/gdpval/) Benchmark Design

### Task Construction Methodology

**Source Professionals:**
- Average 14 years of industry experience
- Drawn from 44 occupations across 9 sectors
- Create tasks based on representative work

**Sectors Covered:**
1. Professional, Scientific, and Technical Services
2. Finance and Insurance
3. Information Technology
4. Healthcare and Social Assistance
5. Educational Services
6. Manufacturing
7. Retail Trade
8. Administrative Services
9. Arts, Entertainment, and Recreation

**Task Types:**
- Written deliverables (reports, briefs, emails)
- Visual deliverables (presentations, charts)
- Technical deliverables (spreadsheets, code)
- Creative deliverables (designs, content)
- Audio/video deliverables

### Evaluation Methodology

**Blinded Pairwise Comparison:**
- Expert graders from same occupation
- Cannot identify which output is AI vs. human
- Rate on quality dimensions:
  - Accuracy
  - Completeness
  - Formatting/aesthetics
  - Appropriateness for context
  - Overall quality

**Scoring:**
- Win: AI output rated better than expert
- Tie: AI output rated equivalent to expert
- Loss: AI output rated worse than expert

---

## Model Performance Data

### [GDPval](https://openai.com/index/gdpval/) Gold Set Results (220 tasks)

**Win + Tie Rates (Expert Parity or Better):**

| Model | Win+Tie Rate | Primary Strength |
|-------|--------------|------------------|
| Claude Opus 4.1 | ~50%+ | Aesthetics, formatting |
| GPT-5 | ~45-50% | Accuracy, domain knowledge |
| GPT-5 Thinking | ~40-45% | Balanced |
| Gemini 3 Pro | ~33-40% | Varies by task |
| Grok | ~20-33% | Varies by task |

*Corrected November 1, 2026: The paper reports 47.6% wins or ties for Claude Opus 4.1 and a 39.0% win rate for GPT-5 ([GDPval paper](https://cdn.openai.com/pdf/d5eb7428-c4e9-4a33-bd86-86dd4bcf12ce/GDPval.pdf)).*

**Performance by Dimension:**

| Dimension | Best Model | Notes |
|-----------|------------|-------|
| Accuracy | GPT-5 | Domain-specific knowledge |
| Formatting | Claude Opus 4.1 | Document layout, slide design |
| Completeness | Claude Opus 4.1 | Covers all requirements |
| Prompt Following | GPT-5 | Instruction adherence |

### Performance Variation by Task Type

**Tasks Where AI Performs Best:**
- Structured document creation
- Data transformation and analysis
- Research synthesis
- Routine correspondence
- Technical documentation

**Tasks Where AI Performs Worst:**
- Highly ambiguous requirements
- Tasks requiring external knowledge
- Client relationship judgment
- Novel strategic decisions
- Multi-stakeholder negotiations

---

## Speed and Cost Analysis

### Time Comparison

| Task Type | Human Expert | AI | Ratio |
|-----------|-------------|-----|-------|
| Report Writing | 4-8 hours | 2-5 minutes | ~100x |
| Spreadsheet Analysis | 2-4 hours | 1-3 minutes | ~80x |
| Presentation Creation | 3-6 hours | 3-8 minutes | ~60x |
| Email Drafting | 15-30 minutes | 10-30 seconds | ~60x |

### Cost Comparison

| Factor | Human Expert | AI (API) |
|--------|-------------|----------|
| Hourly rate equivalent | $50-200/hr | $0.50-5/hr |
| Per-task cost (complex) | $100-500 | $1-5 |
| Per-task cost (simple) | $25-100 | $0.10-0.50 |

**Note**: AI costs assume API pricing; consumer subscriptions have different economics.

---

## Trajectory Analysis

### Historical Performance on GDPval

| Model | Release | Win+Tie Rate | Delta from Previous |
|-------|---------|--------------|---------------------|
| GPT-4o | Spring 2024 | ~25% | Baseline |
| GPT-4o (updated) | Fall 2024 | ~30% | +5% |
| GPT-5 | Summer 2025 | ~50% | +20% |

**Implication**: Performance more than doubled in 14 months.

### Projected Trajectory

If current trend continues:
- Late 2026: 70-80% expert parity *Corrected November 1, 2026: This was a projection, not a finding. See the dated GDPval results in the update above.*
- 2027: Majority of professional tasks at expert level *Corrected November 1, 2026: this was a projection, not a finding.*

**Caveats**:
- Improvement may not be linear
- Remaining tasks may be harder to crack
- New task types may emerge

---

## Occupation-Specific Findings

### Occupations with Highest AI Performance

1. **Technical Writer**: High accuracy, formatting strength
2. **Data Analyst**: Spreadsheet and analysis excellence
3. **Marketing Coordinator**: Content generation, campaign materials
4. **Administrative Assistant**: Correspondence, scheduling, documentation
5. **Junior Software Developer**: Code generation, debugging

### Occupations with Lowest AI Performance

1. **Executive/Senior Manager**: Strategic judgment required
2. **Sales Professional**: Relationship and negotiation focus
3. **Healthcare Provider**: Physical examination, patient interaction
4. **Legal Counsel**: High-stakes judgment, liability concerns
5. **Creative Director**: Vision and direction (vs. execution)

---

## Implications by Sector

### Professional Services
- Junior-level task automation potential high
- Senior judgment and client relationships remain human
- Training pathway disruption likely

### Finance and Insurance
- Analysis and reporting highly automatable
- Regulatory judgment requires human oversight
- Risk assessment increasingly AI-augmented

### Information Technology
- Development productivity gains significant
- Architecture and design judgment human-led
- Code review and debugging automated

### Healthcare
- Documentation and administrative tasks automatable
- Diagnosis support (not replacement) emerging
- Patient interaction remains human-centric

### Education
- Content creation highly automatable
- Assessment design disrupted
- Student interaction and mentorship remain human

---

## Data Gaps

1. **Non-US occupations**: GDPval focused on US GDP sectors
2. **Non-English tasks**: Limited multilingual evaluation
3. **Physical tasks**: Not covered by current benchmarks
4. **Long-horizon projects**: Tasks limited to single-session completion
5. **Team collaboration**: Individual task focus only

---

## Key Takeaways for Universities

1. **~50% of professional tasks** approaching AI parity in quality
2. **100x cost/speed advantage** makes AI economically compelling
3. **Quality improving rapidly** (~2x in 14 months)
4. **Judgment and relationships** remain human advantages
5. **Workforce preparation** must include AI collaboration skills
