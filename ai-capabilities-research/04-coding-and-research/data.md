# Coding and Research Capabilities: Detailed Data

## SWE-bench Verified

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

## METR Counterpoint Study

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

### Microsoft New Employee Study (April 2025)

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
