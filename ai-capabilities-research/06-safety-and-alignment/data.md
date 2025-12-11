**← [Back to Overview](./README.md)** | **[Sources →](./sources.md)**

---

# Safety and Alignment: Detailed Data

## Prompt Injection Resistance

### What is Prompt Injection?

Attempts to override model instructions through:
- Direct instruction insertion in user input
- Embedded commands in documents/data
- Multi-turn manipulation
- Encoded or obfuscated instructions

### Model Comparison ([Anthropic Transparency Hub](https://www.anthropic.com/transparency/model-report))

| Model | Resistance Level | Notes |
|-------|------------------|-------|
| Claude Opus 4.5 | **Industry leading** | Hardest to trick |
| GPT-5 | Strong | Improved from GPT-4 |
| Gemini 3 | Strong | Google's investment |
| Open-source models | Variable | Often weaker |

### Anthropic's Approach

Claude Opus 4.5 improvements:
- Substantial progress on robustness
- Training specifically for injection resistance
- Constitutional AI methods
- Red teaming validation

---

## Jailbreak Analysis

### Common Jailbreak Techniques

1. **Direct Override**
   - "Ignore previous instructions"
   - Explicit instruction replacement
   - Success rate: Very low on frontier models

2. **Roleplay/Persona**
   - "You are now DAN (Do Anything Now)"
   - Character-based circumvention
   - Success rate: Low-moderate

3. **Gradual Escalation**
   - Multi-turn normalization
   - Incremental boundary pushing
   - Success rate: Moderate on some models

4. **Encoding/Obfuscation**
   - Base64 encoding
   - ROT13 or custom ciphers
   - Tokenization exploitation
   - Success rate: Variable

5. **Context Manipulation**
   - Fictional framing
   - Academic/research framing
   - Historical context
   - Success rate: Moderate

### Jailbreak Success Rates (Estimated)

| Technique | Claude 4.5 | GPT-5 | Gemini 3 |
|-----------|------------|-------|----------|
| Direct override | <1% | <1% | <1% |
| Roleplay | 2-5% | 3-7% | 3-8% |
| Escalation | 5-10% | 5-12% | 5-15% |
| Encoding | 3-8% | 5-10% | 5-12% |
| Context manipulation | 5-15% | 8-18% | 8-20% |

**Note**: Rates are approximate; actual rates vary by specific prompt and model version.

---

## Hallucination Analysis

### Definition

Hallucination: Model generates false information presented as fact
- Fabricated facts, citations, or details
- Plausible but incorrect statements
- Confident assertions without basis

### Hallucination Categories

1. **Factual Hallucination**
   - False facts about real entities
   - Incorrect dates, statistics, names

2. **Citation Hallucination**
   - Non-existent papers or sources
   - Wrong authors or titles

3. **Logical Hallucination**
   - Invalid reasoning presented as valid
   - Contradictory conclusions

4. **Capability Hallucination**
   - Claiming abilities the model lacks
   - False certainty about actions

### Hallucination Rates by Domain

| Domain | Estimated Rate | Notes |
|--------|----------------|-------|
| Common knowledge | 2-5% | Generally accurate |
| Technical details | 5-15% | Variable accuracy |
| Recent events | 15-30% | Knowledge cutoff issues |
| Obscure topics | 20-40% | Limited training data |
| Citations | 15-25% | Persistent problem |
| Numbers/statistics | 10-20% | Often approximate |

### Improvement Trajectory

| Model Generation | Avg Hallucination Rate |
|------------------|------------------------|
| GPT-3 era | 30-40% |
| GPT-4 era | 15-25% |
| Current frontier | 5-15% |

---

## Safety Training Methods

### Constitutional AI (Anthropic)

**Approach**:
- Train model on principles (constitution)
- Self-critique and revision
- Minimal human labeling
- Scalable safety alignment

**Strengths**:
- Principled and transparent
- Scales with capability
- Adaptable to new concerns

### RLHF (OpenAI, Google)

**Approach**:
- Human feedback on outputs
- Reward model training
- Policy optimization
- Iterative refinement

**Strengths**:
- Direct human preferences
- Proven effectiveness
- Continuous improvement

### Safety-Capability Frontier

| Configuration | Safety | Capability |
|---------------|--------|------------|
| Maximum safety | Very high | Reduced |
| Balanced | High | Good |
| Maximum capability | Moderate | Very high |

**Observation**: No model achieves both maximum safety and maximum capability simultaneously.

---

## Model-Specific Safety Profiles

### Claude (Anthropic)

**Strengths**:
- Leading prompt injection resistance
- Constitutional AI transparency
- Strong refusal on harmful content
- Consistent safety behavior

**Characteristics**:
- May refuse borderline requests
- Explicit about limitations
- Cautious on sensitive topics

### GPT-5 (OpenAI)

**Strengths**:
- Extensive red teaming
- Continuous safety updates
- Strong content filtering
- Broad safety coverage

**Characteristics**:
- Balanced capability and safety
- Active moderation system
- Regular policy updates

### Gemini (Google)

**Strengths**:
- Google's safety research
- Multi-modal safety
- Enterprise focus

**Characteristics**:
- Conservative on some topics
- Strong factual grounding
- Integration with Google policies

---

## Safety Evaluation Methods

### Red Teaming

**Approach**: Adversarial testing by humans
- Dedicated red team efforts
- External researcher programs
- Bug bounties for safety issues

### Automated Evaluation

**Benchmarks**:
- TruthfulQA (hallucination)
- BBQ (bias)
- HarmBench (harmful outputs)
- Prompt injection test suites

### Real-World Monitoring

**Methods**:
- User feedback analysis
- Incident tracking
- Pattern detection
- Continuous evaluation

---

## Educational Relevance

### AI Ethics Curriculum Topics

1. **Technical Safety**
   - How safety training works
   - Evaluation methodologies
   - Trade-off analysis

2. **Deployment Decisions**
   - Risk assessment frameworks
   - Use case analysis
   - Monitoring requirements

3. **Responsible AI**
   - Dual-use concerns
   - Disclosure practices
   - Stakeholder considerations

4. **Red Teaming Skills**
   - Adversarial thinking
   - Vulnerability identification
   - Responsible disclosure

### Research Opportunities

1. **Safety Evaluation**
   - New benchmark development
   - Real-world safety measurement
   - Cross-model comparison

2. **Mitigation Techniques**
   - Prompt injection defense
   - Hallucination reduction
   - Jailbreak prevention

3. **Policy Research**
   - Governance frameworks
   - Regulatory analysis
   - International coordination

---

## Key Takeaways

1. **Claude leads on prompt injection resistance**: Industry best
2. **Hallucination rates improving**: Down to 5-15% on frontier models
3. **Safety-capability tradeoff real**: No model maximizes both
4. **Jailbreaks still possible**: 5-20% success on some techniques
5. **Rich curriculum material**: Technical and policy content for AI ethics courses
