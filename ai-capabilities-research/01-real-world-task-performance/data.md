# Real-World Task Performance: Detailed Data

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
- Late 2026: 70-80% expert parity
- 2027: Majority of professional tasks at expert level

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
