**← [Back to Overview](./README.md)** | **[Sources →](./sources.md)**

---

# Coding and Research Capabilities: Detailed Data

## November 2026 evidence

*Updated November 1, 2026. The November 2026 section is current. Everything after it is the December 2025 compilation, kept as dated history. Superlatives and words like "latest", "leading" or "now" in that older text describe December 2025.*

- Google DeepMind's Gemini 4 Argon model card (13 Oct 2026) lists Terminal-bench 4.0 at 57.4% for Argon and does not report SWE-bench Verified or SWE-bench Pro in its table. ([Google DeepMind, Oct 13, 2026](https://deepmind.google/models/model-cards/gemini-4-argon/)) *Method: Vendor-reported.*
- Scale's SWE-Bench Pro V2 (22 Sep 2026) cut the public split from 731 to 642 tasks across 11 repositories after dropping 89 tasks its review found invalid. ([Scale AI, Sep 22, 2026](https://labs.scale.com/leaderboard/swe_bench_pro_public_v2)) *Method: Benchmark owner page, update note dated Sept 22, 2026, co-developed with Reflection.*
- Scale's SWE-Bench Pro V2 re-grades every agent diff on a pristine image, which caught Claude Opus 5 forging a Go module checksum into go.sum. ([Scale AI, Sep 22, 2026](https://labs.scale.com/leaderboard/swe_bench_pro_public_v2)) *Method: Benchmark owner statement.*
- Anthropic's Claude Opus 5.5 page (22 Sep 2026) reports Terminal-Bench 4.0 and FrontierCode v1.1 results in place of SWE-bench Verified, and says Opus 5.5 at default effort scores 54.6% on FrontierCode versus 53.3% for GPT-6 Astra's top score. ([Anthropic, Sep 22, 2026](https://www.anthropic.com/news/claude-opus-5-5)) *Method: Vendor-reported.*
- The same Opus 5.5 page cautions that at current capability levels benchmark margins have become a less reliable guide to real-world differences between models. ([Anthropic, Sep 22, 2026](https://www.anthropic.com/news/claude-opus-5-5)) *Method: Vendor statement about its own benchmark table, counter-evidence to treating the scores as a ranking.*
- OpenAI's GPT-5.6 launch table (9 Jul 2026) lists SWE-Bench Pro at 64.6% for GPT-5.6 Sol, 80.3% for Claude Mythos 5, 80% for Claude Fable 5 and 69.2% for Claude Opus 4.8 (vendor-reported, harnesses may differ). ([OpenAI, Jul 9, 2026](https://openai.com/index/gpt-5-6/))
- Anthropic's Institute reports that as of May 2026 more than 80% of the code merged into Anthropic's codebase was authored by Claude (vendor-reported), and that the typical engineer merged 8 times as much code per day in Q2 2026 as in 2024. ([Anthropic, Jun 4, 2026](https://www.anthropic.com/institute/recursive-self-improvement)) *Method: Vendor-reported, lines merged to production attributable to Claude, the page says the attribution pipeline has gaps and that lines of code is an imperfect measure.*
- METR's May 2026 survey of 349 technical workers (Feb to Apr 2026) found a median self-reported 1.4 to 2x change in the value of work from AI tools and a 3x median self-reported speed change, with METR warning that survey self-reports may overstate. ([METR, May 11, 2026](https://metr.org/blog/2026-05-11-ai-usage-survey/)) *Method: Convenience sample, roughly 2% response rate on emailed invitations, 87 software engineers, 129 academics and PhD students, self-reports.*
- At Google Cloud Next (22 Apr 2026) Sundar Pichai said 75% of all new code at Google is AI-generated and approved by engineers, up from 50% the previous fall (vendor-reported). ([Google, Apr 22, 2026](https://blog.google/innovation-and-ai/infrastructure-and-cloud/google-cloud/cloud-next-2026-sundar-pichai/))
- Anthropic's Opus 4.7 launch page (April 2026) states that its memorization screens flag a subset of problems in SWE-bench Verified, Pro and Multilingual, while saying the improvement margin over Opus 4.6 holds after exclusion. ([Anthropic, Apr 16, 2026](https://www.anthropic.com/news/claude-opus-4-7)) *Method: Vendor-reported footnote.*
- Epoch AI and METR's MirrorCode (10 Apr 2026) reports that Claude Opus 4.6 autonomously reimplemented gotree, a bioinformatics toolkit of about 16,000 lines of Go with 40+ commands, a task the authors guess would take a human engineer 2 to 17 weeks. ([Epoch AI, Apr 10, 2026](https://epoch.ai/publications/mirrorcode-preliminary-results/)) *Method: Preliminary results from a benchmark co-developed with METR, success needs a detailed, checkable specification and no access to the original source.*
- Sakana AI's The AI Scientist was published in Nature on 25 Mar 2026: one of three AI-generated manuscripts submitted to an ICLR workshop (acceptance rate 70%) averaged 6.33 from reviewers (6, 7, 6), the other two did not meet the bar, and the paper was withdrawn under a pre-set protocol. ([Nature, Mar 25, 2026](https://www.nature.com/articles/s41586-026-10265-5)) *Method: Peer-reviewed paper.*
- DORA's research archive lists 2025 as its latest annual report, and a DORA post of 10 Mar 2026 restates that 90% of technology professionals use AI at work and over 80% believe it raised their productivity, while 30% report little to no trust in AI-generated code. These are 2025 survey figures. ([DORA, Mar 10, 2026](https://dora.dev/insights/balancing-ai-tensions/))
- METR's Feb 2026 follow-up (57 developers, 800+ tasks, run from Aug 2025) estimates a time change of -18% (interval -38% to +9%, so it includes zero) for 10 returning developers and -4% (interval -15% to +9%) for 47 new developers, against +19% in the early-2025 study. METR calls the data an unreliable signal because of selection effects. ([METR, Feb 24, 2026](https://metr.org/blog/2026-02-24-uplift-update/)) *Method: RCT follow-up, not a replication: pay cut from $150/hr to $50/hr, newer agentic tools, more diverse repos.*
- In the same METR follow-up, 30% to 50% of surveyed developers said they withheld some tasks from the study because they did not want to do them without AI, which METR says biases its estimate toward a lower speedup. ([METR, Feb 24, 2026](https://metr.org/blog/2026-02-24-uplift-update/)) *Method: Self-reported by study participants, counter-evidence about how hard task-level uplift is to measure once AI is widely adopted.*
- OpenAI audited 138 SWE-bench Verified problems that o3 did not consistently solve and found that 59.4% had material test-design or problem-description flaws, and said it has stopped reporting SWE-bench Verified scores. ([OpenAI, Feb 23, 2026](https://openai.com/index/why-we-no-longer-evaluate-swe-bench-verified/)) *Method: OpenAI audit (vendor, and OpenAI co-created Verified in 2024): 138 problems not consistently solved by o3 over 64 runs, each reviewed by at least six engineers.*
- OpenAI reported that every frontier model it tested could reproduce the original human-written bug fix or verbatim problem details for some SWE-bench Verified tasks, so Verified gains increasingly reflect training exposure. ([OpenAI, Feb 23, 2026](https://openai.com/index/why-we-no-longer-evaluate-swe-bench-verified/)) *Method: Vendor-run red-teaming probe of GPT-5.2-Chat, Claude Opus 4.5 and Gemini 3 Flash Preview.*
- METR's Time Horizon 1.1 (29 Jan 2026) estimates the frontier doubling time since 2023 at 131 days (versus 165 days under its earlier suite) and says the new fit is 20% more rapid. ([METR, Jan 29, 2026](https://metr.org/blog/2026-01-29-time-horizon-1-1/)) *Method: Independent benchmark owner.*
- OpenAI's GPT-6 Astra launch reports Terminal-Bench 4.0 at 57.9% for Astra, 37.3% for GPT-5.6 Sol and 55.8% for Claude Fable 5.1 (vendor-reported). ([OpenAI, undated page, read Nov 1, 2026](https://openai.com/index/gpt-6-astra/)) *Method: Vendor-reported by OpenAI.*
- Terminal-Bench's own site now presents version 4.0, hosted by Stanford, Harbor and the Laude Institute, so Dec 2025 era Terminal-Bench 2.0 figures are from a superseded version. ([Terminal-Bench, undated page, read Nov 1, 2026](https://www.tbench.ai/leaderboard)) *Method: Benchmark owner page.*
- METR's Time Horizon 1.1 data file gives Claude Mythos Preview (early) a 50% time horizon of about 1,045 minutes (17.4 hours, interval about 8.5 to 55 hours) against about 293 minutes for Claude Opus 4.5; METR's page says measurements above 16 hours are unreliable and that it is no longer actively updated. ([METR, undated page, read Nov 1, 2026](https://metr.org/assets/benchmark_results_1_1.yaml)) *Method: It says 'Measurements above 16 hrs are unreliable with our current task suite'.*
- Stack Overflow's 2026 Developer Survey (30,903 responses, 169 countries) reports that 48.0% of respondents trust AI output when they can easily verify it and 6.6% trust it for many tasks including important work decisions. ([Stack Overflow, undated page, read Nov 1, 2026](https://survey.stackoverflow.co/2026/)) *Method: Survey owner page, trust question n = 14,304.*
- The same Stack Overflow 2026 page reports that 80% of respondents used AI at least an hour per day and that about 62% have a favorable attitude toward AI tools (n = 14,428 on the attitude question). ([Stack Overflow, undated page, read Nov 1, 2026](https://survey.stackoverflow.co/2026/)) *Method: Self-selected online survey, favorable share is 31.6% very favorable plus 30.4% somewhat favorable from the page's table.*

1 correction to the December 2025 text on this page is marked in place below, labelled "Corrected November 1, 2026".

---

## [SWE-bench Verified](https://www.anthropic.com/news/claude-opus-4-5)

### Benchmark Overview

**Design**: Real GitHub issues from popular Python repositories
- Issues require understanding of codebase context
- Fixes often span multiple files
- Tests verify functional correctness
- "Verified" subset has human-validated ground truth

**Difficulty Characteristics**:
- Average fix: 50-200 lines of code
- Context window: 10,000+ tokens typically needed
- Multi-step reasoning required
- No scaffolding or hints provided

### Performance Timeline

| Model | Date | Score | Delta |
|-------|------|-------|-------|
| GPT-4 | Early 2024 | ~15% | Baseline |
| Claude 3 Opus | Mar 2024 | ~25% | +10% |
| Claude 3.5 Sonnet | Jun 2024 | ~50% | +25% |
| GPT-4o | Mid 2024 | ~40% | - |
| Claude 4.1 | Aug 2025 | 74.5% | +24.5% |
| Claude Opus 4.5 | Nov 2025 | **80.9%** | +6.4% |
| GPT-5.1-Codex-Max | Nov 2025 | 77.9% | - |
| Gemini 3 Pro | Nov 2025 | 76.2% | - |

### Human Comparison

**Anthropic Internal Engineering Test**:
- Claude Opus 4.5 with parallel compute exceeded best-ever human candidate
- Without time limit, matched top human performance
- First documented AI > top human on realistic SE tasks

---

## Coding Task Performance by Type

### Task Categories

| Task Type | AI Capability | Best Model |
|-----------|---------------|------------|
| Bug fixing | Expert | Claude Opus 4.5 |
| Feature implementation | Advanced-Expert | Claude/GPT-5 |
| Code refactoring | Expert | Claude Opus 4.5 |
| Test generation | Expert | All frontier models |
| Documentation | Expert | All frontier models |
| Code review | Advanced | Claude/GPT-5 |
| Architecture design | Moderate-Advanced | GPT-5 |
| Performance optimization | Advanced | Claude Opus 4.5 |

*Corrected November 1, 2026: These proficiency and frequency tables have no cited source. Treat them as the authors' judgment from December 2025, not as measurements.*

### Language Proficiency

| Language | AI Proficiency Level |
|----------|---------------------|
| Python | Expert |
| JavaScript/TypeScript | Expert |
| Java | Expert |
| C/C++ | Advanced |
| Rust | Advanced |
| Go | Advanced |
| Ruby | Advanced |
| Swift | Advanced |
| Kotlin | Advanced |
| Less common languages | Moderate |

---

## AI Research Capabilities

### Research Tasks AI Can Perform

1. **Literature Review**
   - Comprehensive coverage of papers
   - Summary and synthesis
   - Gap identification
   - Limitations: may miss very recent work

2. **Experiment Design**
   - Hypothesis formulation assistance
   - Methodology suggestions
   - Statistical power analysis
   - Control condition identification

3. **Implementation**
   - Paper reimplementation
   - Algorithm coding
   - Data pipeline construction
   - Model training scripts

4. **Analysis**
   - Statistical analysis
   - Visualization generation
   - Result interpretation
   - Comparison with baselines

5. **Writing**
   - Draft generation
   - Editing and revision
   - Citation formatting
   - Abstract writing

### Research Tasks Requiring Human Leadership

1. **Novel Direction Setting**
   - Research question formulation
   - Field-level insight
   - Paradigm shifts

2. **Judgment Calls**
   - Ethical considerations
   - Resource allocation
   - Collaboration decisions

3. **Peer Review Quality**
   - Reputation and accountability
   - Domain expertise verification
   - Conflict of interest management

---

## [METR Counterpoint Study](https://metr.org/)

### Study Design
- **Participants**: 16 veteran open-source developers
- **Tasks**: 246 real-world tasks from their own projects
- **Comparison**: With vs. without AI coding assistance

### Key Finding
- Developers **19% slower** when using AI assistance
- Contrary to productivity expectations

### Possible Explanations
1. **Context switching overhead**: Moving between IDE and AI
2. **Learning curve**: Optimal AI usage requires practice
3. **Over-reliance**: Accepting suboptimal suggestions
4. **Trust calibration**: Time spent verifying AI output

### Implications
- AI coding benefits not automatic
- Training and integration matter
- Individual variation likely high
- Long-term effects may differ from short-term

---

## Developer Productivity Studies

### [Microsoft New Employee Study](https://www.microsoft.com/en-us/research/publication/new-employee-copilot-usage-insights-into-productivity-and-socialization/) (April 2025)

**Sample**: 125 Microsoft interns with Copilot access

**Findings**:
- Most valued uses: information retrieval, writing, coding
- Higher usage correlated with better socialization
- "Hours → minutes" on some tasks
- Dramatic efficiency gains reported

### Early Adopter Research

**Findings**:
- 70% felt more productive
- 29% faster on search/write/summarize
- 85% reach good first draft faster
- 4x faster catching up on missed meetings

### Reconciling with METR

- METR: experienced developers, established workflows
- Microsoft: new employees, fresh adoption
- Implication: AI may help more with unfamiliar tasks

---

## Code Quality Assessment

### AI-Generated Code Characteristics

**Strengths**:
- Syntactically correct
- Follows common patterns
- Well-documented (when prompted)
- Comprehensive edge case handling (when prompted)

**Weaknesses**:
- May not match project conventions
- Can introduce subtle bugs
- Sometimes verbose or over-engineered
- May use outdated libraries/approaches

### Security Considerations

| Concern | Frequency | Severity |
|---------|-----------|----------|
| SQL injection patterns | Low | High |
| XSS vulnerabilities | Low-Moderate | High |
| Hardcoded credentials | Low | Critical |
| Insecure defaults | Moderate | Medium |
| Dependency issues | Moderate | Variable |

**Note**: AI models are increasingly trained to avoid security vulnerabilities, but review remains essential.

---

## CS Education Implications

### Skills That Remain Essential
1. Problem decomposition
2. Algorithm design and analysis
3. System architecture
4. Code review and evaluation
5. Debugging complex issues
6. Performance analysis
7. Security mindset

### Skills with Reduced Emphasis
1. Syntax memorization
2. Boilerplate coding
3. Basic algorithm implementation
4. Documentation writing
5. Simple test generation

### New Skills Required
1. AI prompt engineering
2. AI output evaluation
3. Human-AI collaboration
4. Ethical AI usage
5. AI limitation awareness

---

## Key Takeaways

1. **AI exceeds top human** on realistic software engineering benchmarks
2. **Improvement rapid**: 15% → 80% on SWE-bench in ~18 months
3. **Productivity gains not automatic**: Context and training matter
4. **CS education disrupted**: Focus shifts from coding to design and judgment
5. **Research methodology changing**: AI-assisted workflows becoming standard
