---
name: pitch-deck
description: Create investor pitch deck outlines following proven fundraising frameworks. Use this skill when asked to create a pitch deck, investor presentation, fundraising deck, startup pitch, or investor materials. Triggers include "pitch deck", "investor deck", "fundraising presentation", "startup pitch", "Series A deck", "seed deck", "investor slides", or requests to structure a startup presentation for investors.
language: auto
---

# Pitch Deck Builder

Create pitch deck outlines that tell a compelling investment story. Investors see hundreds of decks — yours must be clear, concise, and impossible to ignore.

## Core Philosophy

### Story Over Slides
A pitch deck is a narrative, not a data dump. Every slide advances one argument: "This is a massive opportunity, we're the team to capture it, and now is the time."

### The 10/20/30 Rule (Guy Kawasaki)
- **10 slides** maximum for the core story
- **20 minutes** to present (leaves time for Q&A)
- **30pt font** minimum (forces conciseness)

## The 10-Slide Framework

| # | Slide | Core Question | Time |
|---|-------|--------------|------|
| 1 | **Title** | Who are you? | 30s |
| 2 | **Problem** | What pain exists? | 2 min |
| 3 | **Solution** | How do you solve it? | 2 min |
| 4 | **Market** | How big is the opportunity? | 2 min |
| 5 | **Product** | What have you built? | 2 min |
| 6 | **Traction** | What proof do you have? | 2 min |
| 7 | **Business Model** | How do you make money? | 2 min |
| 8 | **Competition** | Why will you win? | 2 min |
| 9 | **Team** | Why this team? | 2 min |
| 10 | **The Ask** | What do you need? | 2 min |

## Slide-by-Slide Guide

### Slide 1: Title
```
[Company Name]
[One-line description — what you do in 10 words or fewer]
[Logo]
[Founder name, contact]
[Round: Seed / Series A / Series B]
```

Keep it clean. No paragraphs. The one-liner should pass the "mom test" — would a non-technical person understand it?

### Slide 2: Problem
**Goal**: Make the investor FEEL the pain.

Structure:
- State the problem in one sentence
- Quantify the pain (time wasted, money lost, people affected)
- Show who suffers (be specific about the persona)
- Optional: A quote from a real user experiencing the pain

```
❌ "Communication is hard for remote teams"
✅ "Remote engineering teams waste 5.2 hours/week in unnecessary meetings because async tools fail at context transfer"
```

### Slide 3: Solution
**Goal**: Show your insight, not just your product.

Structure:
- Your unique insight (what you see that others don't)
- How your solution works (3 bullet points max)
- Before/After comparison

```
Insight: [The non-obvious truth you've discovered]

How it works:
1. [Step 1 — simple language]
2. [Step 2]
3. [Step 3]
```

### Slide 4: Market Size
**Goal**: Prove the opportunity is worth pursuing.

Use TAM/SAM/SOM framework:
- **TAM** (Total Addressable Market): The entire market if you had 100% share
- **SAM** (Serviceable Addressable Market): The segment you can realistically reach
- **SOM** (Serviceable Obtainable Market): What you can capture in 3-5 years

```
TAM: $50B — Global project management software
SAM: $8B — Remote-first engineering teams
SOM: $400M — Teams using async-first workflows
```

**Rules**:
- Bottom-up > Top-down (show your math)
- Cite sources for market data
- SOM should be believable, not aspirational

### Slide 5: Product
**Goal**: Show, don't tell.

- Screenshots or demo video (2-3 key screens)
- Highlight the "aha moment" — the feature that makes users say "wow"
- Keep text minimal — let the product speak

### Slide 6: Traction
**Goal**: Prove market demand with data.

Best metrics by stage:

| Stage | Key Metrics |
|-------|------------|
| Pre-seed | Waitlist, LOIs, pilot users, engagement |
| Seed | MRR, growth rate, retention, NPS |
| Series A | ARR, unit economics, LTV/CAC, net revenue retention |

**Show the graph going up and to the right.** If you don't have revenue, show engagement, retention, or growth rate.

### Slide 7: Business Model
**Goal**: Show a clear path to revenue.

Structure:
- Revenue model (SaaS, marketplace, transaction fee, etc.)
- Pricing tiers (if applicable)
- Unit economics: CAC, LTV, LTV/CAC ratio, payback period
- Expansion revenue strategy

### Slide 8: Competition
**Goal**: Show you understand the landscape AND have a defensible position.

**Use a 2x2 matrix**, NOT a feature comparison table.
- Choose two axes that highlight YOUR strengths
- Position competitors honestly
- Show your unique quadrant

```
         High Customization
              |
   Legacy     |    YOU
   Tools      |    ★
              |
 ─────────────┼─────────────
              |
   Simple     |   New
   Tools      |   Entrants
              |
         Low Customization
```

### Slide 9: Team
**Goal**: Prove you're the right people to execute.

For each key team member (3-5 people):
- Name + Role
- One line of relevant experience (not full bio)
- Why THIS person for THIS problem

```
✅ "Jane Doe, CTO — Built the real-time infrastructure at Slack (10M concurrent users)"
❌ "Jane Doe, CTO — 15 years of experience in software engineering"
```

Highlight: domain expertise, previous exits, relevant company experience.

### Slide 10: The Ask
**Goal**: Be specific about what you need and what you'll do with it.

Structure:
- Amount raising
- Use of funds (3-4 categories with percentages)
- Key milestones this funding enables
- Timeline to next round

```
Raising: $3M Seed Round

Use of Funds:
- 50% Engineering (hire 4 engineers)
- 25% Go-to-market (first sales hire + marketing)
- 15% Operations
- 10% Buffer

18-Month Milestones:
- $1M ARR
- 50 enterprise customers
- Series A ready
```

## Appendix Slides (Optional, for Q&A)

- Detailed financial projections (3-year)
- Technical architecture
- Customer case studies
- Detailed competitive analysis
- Go-to-market strategy details
- Cap table summary

## Language Rules

- Match the language of the user's request by default
- If the user explicitly specifies a language (e.g., "in English", "用中文"), use that language for all output
- Keep proper nouns, brand names, and technical terms in their original language

## Output Format

```markdown
# [Company Name] — Pitch Deck Outline

## Slide 1: Title
[Content]

## Slide 2: Problem
[Content]

...

## Slide 10: The Ask
[Content]

---

## Appendix Recommendations
- [Which appendix slides to prepare]

## Presentation Tips
- [Specific advice for this deck]
```

## Anti-Patterns

- **Slide overload** — more than 15 slides (investors lose attention)
- **No story arc** — slides feel disconnected, no narrative thread
- **Vanity metrics** — "1M downloads" without retention or revenue
- **Competitor dismissal** — "we have no competitors" (red flag)
- **Vague ask** — "we're raising money" without amount or use of funds
- **Wall of text** — paragraphs on slides (use bullets, visuals, data)
- **Unrealistic projections** — hockey stick without supporting logic

## Quick Checklist

1. Can someone understand the business in 3 minutes?
2. Is the problem real and quantified?
3. Is the market size bottom-up, not just top-down?
4. Does traction show momentum?
5. Is the ask specific with clear milestones?
6. Would YOU invest based on this deck?
