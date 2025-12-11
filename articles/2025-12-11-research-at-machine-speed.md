# Research at Machine Speed: Compiling 150+ Sources in 11 Hours

*How a conversation about AI usage became a comprehensive research repository—and what that says about the future of knowledge work.*

---

## The Starting Point

It began with a simple question: how are people actually using AI platforms from the frontier labs?

Not the hype. Not the speculation. The data. What do Anthropic, OpenAI, Google, and Microsoft know about their own users? What patterns emerge when you look across 37.5 million conversations, 1.5 million chat logs, and dozens of research reports?

I had a vague sense of what I wanted: something comprehensive, well-sourced, academically rigorous. What I didn't have was weeks of research time.

What followed was an 11-hour collaboration that produced [AI Impact Research](https://vishalsachdev.github.io/ai-impact/)—a repository containing 150+ verified sources organized into 13 research questions across two research tracks, with over 8,000 lines of structured analysis.

This is the story of how that happened.

---

## Phase 1: The Constraint That Shaped Everything

**December 10, 9:11 PM** — First commit.

The initial scope decision turned out to be the most consequential one. I specified "frontier labs"—Anthropic, OpenAI, Google DeepMind, Microsoft—and that constraint immediately baked in the structure.

This is different from how I would have researched interactively on Google. With traditional search, I might have wandered through a larger search space: academic papers on AI ethics, startup usage patterns, open-source model adoption. The exploration would have been broader but shallower.

By narrowing to frontier labs, we went deep. The AI could systematically pull from:
- [Anthropic's Economic Index](https://www.anthropic.com/research/anthropic-economic-index-september-2025-report) (1M+ conversations analyzed)
- [OpenAI's ChatGPT Usage Study](https://openai.com/index/how-people-are-using-chatgpt/) (1.5M conversations, Harvard partnership)
- [Microsoft's Copilot Analysis](https://microsoft.ai/news/its-about-time-the-copilot-usage-report-2025/) (37.5M conversations)
- [Pew Research's Teen Study](https://www.pewresearch.org/internet/2025/12/09/teens-social-media-and-ai-chatbots-2025/) (1,458 U.S. teens surveyed)

The constraint didn't limit the research—it focused it. Six research questions emerged naturally:

1. Automation vs. Augmentation Patterns
2. Platform Specialization
3. Demographics & Adoption
4. Global Inequality
5. Enterprise vs. Consumer Usage
6. Use Case Evolution

Each question got its own folder with three files: `README.md` (overview), `data.md` (detailed analysis), `sources.md` (comprehensive citations).

```
ai-usage-research/
├── 01-automation-vs-augmentation/
│   ├── README.md
│   ├── data.md
│   └── sources.md
├── 02-platform-specialization/
...
```

By 9:14 PM, we had GitHub Pages configured. The repository was live.

---

## Phase 2: The Conversation That Split the Stream

Here's where something unexpected happened.

As we discussed the research, I realized there were actually *two* distinct questions I cared about:
1. **How** people use AI (usage patterns, demographics, adoption)
2. **What** AI can do (capabilities, benchmarks, trajectories)

These are related but fundamentally different. Usage data tells you about human behavior. Capability data tells you about the technology itself.

In a traditional research process, I might have muddled these together or chosen one focus. But the conversational nature of working with Claude meant I could articulate this distinction in real-time and get feedback.

"These feel like separate research tracks," I said.

"They are," Claude confirmed. "And they have different audiences. Usage research is general interest. Capabilities research is more relevant to university stakeholders trying to make decisions about curriculum, assessment, and policy."

That conversation led to the second research track: **AI Capabilities Research**.

**December 10, 11:01 PM** — The capabilities track landed as a single massive commit:
- 23 new files
- 4,163 lines added
- 7 research questions covering real-world task performance, capability trajectories, academic benchmarks, coding abilities, agentic capabilities, safety, and educational implications

The structure mirrored the usage track but with different sources: OpenAI's GDPval benchmark, Anthropic's SWE-bench results, Google's Gemini 3 technical reports, METR's AI coding studies.

Two hours of conversation had produced a second complete research compilation.

---

## Phase 3: Verification and Citation

**December 11, 7:25 AM** — The refinement phase.

This is where the collaboration pattern shifted from generation to verification.

I have a specific concern with AI-assisted research: confidence in accuracy. The model can produce impressive-looking content, but how do I know the statistics are correct? That the sources actually say what we claim they say?

The solution: force another iteration with explicit verification instructions.

"Go through every statistic and fact. Add inline citations with hyperlinks to the primary source."

This produced two commits in quick succession:
- `2743e44`: Source hyperlinks throughout data.md files
- `6189f4d`: Inline parenthetical citations on all README pages

The citation format:
```markdown
ChatGPT now 52.4% female users ([OpenAI](https://openai.com/index/how-people-are-using-chatgpt/))
```

Every claim now traced back to a clickable source. The verification pass didn't find major errors—but it did catch a few places where the original phrasing was imprecise. More importantly, it transformed the repository from "research notes" into "citable research."

The verification iteration increased my confidence significantly. Not because the model is always right, but because the process of re-checking surfaced the places that needed attention.

---

## What We Found

The research itself surfaced several surprising findings:

**The Great Divergence**: AI is becoming two different things simultaneously. For consumers, ChatGPT is evolving into a "personal advisor" (73% non-work usage). For businesses, Claude is becoming an "automation engine" (77% of API use is full task delegation). Same technology, diverging purposes.

**Gender Parity Achieved**: ChatGPT reached 52.4% female users—the fastest gender parity achievement of any major technology platform. This happened in roughly 12 months.

**The Global Paradox**: Emerging economies are adopting AI 4x faster than wealthy countries in percentage terms. But absolute usage remains 23x higher in places like Singapore compared to Nigeria. Fast relative growth may still mean widening absolute gaps.

**Capability Acceleration**: Model capabilities doubled in 14 months (GPT-4o to GPT-5 on real-world task benchmarks). Claude Opus 4.5 became the first model to exceed the best human performance on SWE-bench. Gemini 3 hit 93.8% on PhD-level science questions.

**The 100x Advantage**: On authentic professional deliverables, AI completes tasks 100x faster and 100x cheaper than human experts—while achieving similar quality on approximately half of measured tasks.

These aren't predictions. They're measurements from 2025 data.

---

## What This Says About Research

The traditional research process looks something like:
1. Define question
2. Search literature
3. Compile sources
4. Synthesize findings
5. Write up
6. Verify citations
7. Revise

Each step takes time. Literature search alone can consume days. Verification is tedious. The process is measured in weeks or months.

What happened here was different:

| Phase | Traditional | This Project |
|-------|-------------|--------------|
| Literature search | Days | Minutes |
| Source compilation | Hours | Concurrent with search |
| Synthesis | Days | Real-time |
| Verification | Hours | One focused pass |
| Total | Weeks | 11 hours |

This isn't because the AI "did the research for me." It's because the collaboration pattern changed. I provided direction, constraints, and judgment. The model provided search, synthesis, and structure. The back-and-forth happened in conversation rather than across research sessions.

The constraint decision (frontier labs) shaped everything. The mid-stream conversation split the research into two tracks. The verification pass caught edge cases and added rigor.

Human intent. Machine execution. Iterative refinement.

---

## The Opus 4.5 Factor

I should note: this was done with Claude Opus 4.5, Anthropic's most capable model.

The agentic search and synthesis capabilities were noticeably strong. When I said "find the major research reports from frontier labs on AI usage in 2025," it didn't just search—it identified the specific reports, extracted the relevant statistics, and organized them into coherent themes.

Following directions precisely was also important. When I asked for inline citations in a specific format, that's exactly what I got. No creative interpretation. No "improvements" that changed the intent.

This matters for research work. The model needs to be capable enough to handle complex synthesis, but disciplined enough to execute instructions exactly as given.

---

## Limitations and Honest Caveats

This approach has real limitations:

**Narrower search space**: The frontier labs constraint meant we didn't explore adjacent areas—academic AI ethics research, open-source model communities, country-specific studies. A human researcher wandering through Google Scholar might have found connections we missed.

**Source availability bias**: The research relies heavily on what frontier labs chose to publish. Their transparency reports are valuable but not comprehensive. What they don't report is invisible to this method.

**Verification depth**: The citation pass checked that sources were linked correctly, but didn't involve re-reading every source document to verify interpretations. That would require more time.

**Single-session coherence**: All 13 research questions were developed in related sessions over one evening/morning. A longer research project might discover contradictions or evolve its framing over time.

These aren't fatal flaws. They're trade-offs. The question is whether the speed advantage is worth the narrower exploration.

For this use case—creating a well-sourced reference repository on a defined topic—the trade-off made sense.

---

## What Comes Next

The repository is live at [vishalsachdev.github.io/ai-impact](https://vishalsachdev.github.io/ai-impact/).

It's designed to be useful for:
- **University stakeholders** making decisions about AI policy, curriculum, and assessment
- **Researchers** looking for a curated starting point on AI usage and capabilities
- **Writers and journalists** needing verified statistics with source links
- **Anyone** trying to understand what's actually happening with AI adoption in 2025

The two-track structure means you can focus on usage patterns or capabilities depending on your interest.

Every statistic links to its primary source. Every research question has its own detailed analysis. The data gaps and methodological limitations are explicitly documented.

---

## The Meta-Observation

I'm writing this article with Claude. The research was compiled with Claude. The citations were verified with Claude.

There's something recursive about using AI to research AI usage and then writing about the experience of using AI to do that research.

But that recursion is the point. This is what knowledge work increasingly looks like: human direction, machine execution, iterative refinement, conversational development.

The 11-hour research compilation isn't impressive because it was fast. It's interesting because it demonstrates a different *kind* of research process—one where the conversation itself shapes the output, where verification is a distinct phase, and where constraints matter more than open-ended exploration.

Is this better than traditional research? Not categorically. It's faster, more structured, and good for well-defined domains. It's worse for serendipitous discovery and cross-domain connections.

It's a different tool for a different purpose.

And if you want to know how people are using these tools—and what the tools themselves can do—the research is there, 150+ sources deep, waiting to be explored.

---

*This article was written by Claude Opus 4.5 in collaboration with Vishal Sachdev, documenting their December 2025 research collaboration. The AI Impact Research repository is available at [vishalsachdev.github.io/ai-impact](https://vishalsachdev.github.io/ai-impact/).*
