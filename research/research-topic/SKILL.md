---
name: research-topic
description: Conduct deep research on any topic using a structured multi-angle investigation framework. Use this skill when asked to research something, investigate a topic, do a deep dive, compile a report, or gather comprehensive information on any subject. Triggers include "research", "investigate", "deep dive", "report on", "analyze", "what do we know about", "comprehensive overview", or requests for thorough analysis of any topic.
language: auto
---

# Deep Topic Research

Conduct structured research that produces actionable intelligence, not just information dumps. The goal is synthesis — connecting dots that aren't obvious.

## Core Method: The Diamond Framework

```
        Diverge (Gather)
       /                \
      /                  \
     /    Wide Search     \
    /                      \
   /________________________\
   \                        /
    \   Filter & Verify    /
     \                    /
      \   Synthesize     /
       \                /
        Converge (Insight)
```

1. **Diverge** — Cast a wide net across multiple angles
2. **Filter** — Separate signal from noise, verify claims
3. **Synthesize** — Connect patterns, identify insights
4. **Converge** — Deliver clear conclusions with confidence levels

## Research Angles

For any topic, investigate from these 6 angles:

| Angle | Questions | Sources |
|-------|-----------|---------|
| **What** | Definition, scope, current state | Official docs, Wikipedia, industry reports |
| **Why** | Root causes, motivations, drivers | Academic papers, expert interviews, history |
| **How** | Mechanisms, processes, implementation | Technical docs, case studies, tutorials |
| **Who** | Key players, stakeholders, experts | LinkedIn, company pages, conference talks |
| **When** | Timeline, trends, milestones | News archives, historical data, roadmaps |
| **So What** | Implications, predictions, actions | Analysis pieces, expert opinions, data trends |

## Research Workflow

### Phase 1: Scope Definition
Before searching, define:
- **Core question**: What exactly are we trying to answer?
- **Depth level**: Overview / Working knowledge / Expert analysis
- **Time frame**: Current state / Historical / Forward-looking
- **Audience**: Who will read this and what decisions will they make?

### Phase 2: Wide Search
Run parallel searches across multiple dimensions:

```
Primary searches (run in parallel):
- "[Topic] overview 2025"
- "[Topic] latest developments"
- "[Topic] research papers"
- "[Topic] expert analysis"
- "[Topic] criticism challenges"
- "[Topic] vs alternatives comparison"
- "[Topic] future predictions trends"
```

### Phase 3: Source Evaluation

Rate each source on credibility:

| Tier | Source Type | Trust Level |
|------|-----------|-------------|
| **Tier 1** | Peer-reviewed papers, official data, primary sources | High — cite directly |
| **Tier 2** | Reputable journalism, industry reports, expert blogs | Medium-High — cite with attribution |
| **Tier 3** | News aggregators, Wikipedia, general articles | Medium — verify claims elsewhere |
| **Tier 4** | Social media, forums, anonymous sources | Low — use for leads only, never cite alone |

### Phase 4: Cross-Reference
- Every major claim needs 2+ independent sources
- Flag single-source claims as [UNVERIFIED]
- Note contradictions between sources explicitly
- Distinguish between facts, expert opinions, and speculation

### Phase 5: Synthesis
- Identify patterns across sources
- Note what multiple experts agree on (consensus)
- Note where experts disagree (open questions)
- Connect to adjacent topics the user might not have considered
- Form original insights from the combination of sources

## Language Rules

- Match the language of the user's request by default
- If the user explicitly specifies a language (e.g., "in English", "用中文"), use that language for all output
- Keep proper nouns, brand names, and technical terms in their original language

## Output Structure

### Executive Summary Format (Default)

```markdown
# Research Report: [Topic]

## Executive Summary
[3-5 sentences: What this is, why it matters, key finding]

## Key Findings

### 1. [Finding Title]
[2-3 paragraphs with evidence]
- **Evidence**: [Data/source]
- **Confidence**: High / Medium / Low
- **Implication**: [So what?]

### 2. [Finding Title]
...

### 3. [Finding Title]
...

## Landscape Analysis
[Who are the key players? What are the competing approaches?]

## Open Questions
- [What we still don't know]
- [Where experts disagree]
- [What needs more investigation]

## Timeline
- [Key historical milestones]
- [Recent developments]
- [Expected future events]

## Recommendations
[Based on findings, what should the reader do?]

## Sources
[Numbered list with URLs, organized by tier]

---
📊 Research depth: [Overview / Working Knowledge / Expert]
🔍 Sources consulted: [N]
⚠️ Confidence level: [High / Medium / Low]
```

### Comparison Format (for "X vs Y" questions)

```markdown
# [X] vs [Y]: Research Report

## Quick Verdict
[One paragraph: which is better for what use case]

## Comparison Matrix

| Dimension | [X] | [Y] | Winner |
|-----------|-----|-----|--------|
| [Dim 1]   |     |     |        |
| [Dim 2]   |     |     |        |
...

## Detailed Analysis
### [Dimension 1]
[Deep comparison with evidence]

## When to Choose [X]
[Specific scenarios]

## When to Choose [Y]
[Specific scenarios]
```

## Confidence Calibration

Be explicit about certainty levels:

| Level | Meaning | Language |
|-------|---------|---------|
| **High** | Multiple Tier 1-2 sources agree | "Evidence strongly suggests..." |
| **Medium** | Some evidence, some gaps | "Available data indicates..." |
| **Low** | Limited or conflicting evidence | "Early signals suggest, but..." |
| **Speculative** | Informed guess, no hard data | "One possible interpretation..." |

## Research Quality Rules

1. **No unsourced claims** — every factual statement links to a source
2. **Distinguish fact from opinion** — "X happened" vs "Expert Y believes..."
3. **Include counter-arguments** — steelman the opposing view
4. **Recency matters** — flag if best available data is outdated
5. **Quantify when possible** — "significant growth" → "47% YoY growth"
6. **Acknowledge gaps** — what you couldn't find is as important as what you found

## Anti-Patterns

- **Confirmation bias** — only searching for evidence that supports a hypothesis
- **Source laundering** — multiple articles citing the same original source ≠ independent verification
- **Recency bias** — assuming the latest article is the most accurate
- **Authority bias** — big company said it ≠ it's true
- **Completeness theater** — listing 50 sources when 10 high-quality ones would be better
- **Analysis paralysis** — researching forever instead of delivering actionable findings

## Quick Checklist

1. Is the core question clearly defined?
2. Did I search from multiple angles (not just one framing)?
3. Are major claims supported by 2+ independent sources?
4. Did I include counter-arguments and open questions?
5. Is every finding tagged with a confidence level?
6. Does the report end with actionable recommendations?
7. Would someone make a better decision after reading this?
