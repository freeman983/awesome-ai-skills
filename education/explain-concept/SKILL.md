---
name: explain-concept
description: Explain any concept using the Feynman Technique with progressive depth levels. Use this skill when asked to explain something, teach a concept, break down a topic, make something understandable, or simplify complex ideas. Triggers include "explain", "what is", "how does X work", "teach me", "ELI5", "break down", "simplify", or requests to understand any technical, scientific, business, or abstract concept.
---

# Concept Explainer

Explain any concept clearly using the Feynman Technique: if you can't explain it simply, you don't understand it well enough.

## Core Method

### The Feynman Technique

1. **Name the concept** — identify exactly what we're explaining
2. **Explain in plain language** — as if teaching someone with zero background
3. **Identify gaps** — where does the simple explanation break down?
4. **Refine with analogies** — bridge the gaps using familiar experiences

### Progressive Depth

Every explanation follows three levels. Always start with Level 1 unless the user specifies otherwise.

| Level | Audience | Style | Length |
|-------|----------|-------|--------|
| **Level 1: Curious Child** | Zero background | Analogy-driven, visual, playful | 3-5 sentences |
| **Level 2: Smart Student** | Basic literacy | Structured, with terminology introduced gently | 2-3 paragraphs |
| **Level 3: Practitioner** | Working knowledge | Technical precision, edge cases, trade-offs | Full breakdown |

## Explanation Structure

### Level 1 — The Analogy

Find an analogy from everyday life. The best analogies:
- Map to the concept's **core mechanism**, not just surface similarity
- Use experiences everyone has (cooking, driving, building, playing games)
- Are honest about where they break down

```
[Concept] is like [familiar thing] because [shared mechanism].

Imagine [scenario]. That's basically what [concept] does.
```

### Level 2 — The Framework

Introduce proper terminology, but always anchor to the analogy first.

```
## What It Is
[One sentence definition using plain language]

## How It Works
[3-5 steps of the core mechanism]

## Why It Matters
[Real-world impact or application]

## Key Terms
- **Term 1**: [definition tied back to the analogy]
- **Term 2**: [definition tied back to the analogy]
```

### Level 3 — The Deep Dive

Technical precision with nuance.

```
## Formal Definition
[Precise, technical definition]

## Mechanism
[Detailed how-it-works with edge cases]

## Trade-offs & Limitations
[What it doesn't do well, common misconceptions]

## Connections
[How it relates to adjacent concepts]

## Further Reading
[What to study next]
```

## Analogy Toolkit

### For Abstract Concepts
- **Algorithms** → Recipes (step-by-step instructions)
- **Data structures** → Physical containers (shelves, filing cabinets, queues)
- **Networks** → Road systems or postal services
- **Encryption** → Locked boxes with special keys
- **APIs** → Restaurant menus (you order, kitchen handles the rest)

### For Scientific Concepts
- **DNA** → Blueprint or instruction manual
- **Entropy** → A messy room that never cleans itself
- **Quantum superposition** → A coin spinning in the air (not heads or tails yet)
- **Natural selection** → A filter that only lets certain shapes through

### For Business Concepts
- **Unit economics** → Lemonade stand profit per cup
- **Network effects** → Phone system (more users = more value)
- **Moats** → Castle defenses (what stops competitors)
- **TAM/SAM/SOM** → Ocean → Lake → Pond (market sizing)

## Quality Rules

1. **No jargon without introduction** — every technical term gets a plain-language definition on first use
2. **Analogy before abstraction** — always ground in something familiar before going technical
3. **Honest about limits** — say "this analogy breaks down when..." rather than oversimplifying
4. **One concept at a time** — if explaining X requires understanding Y, explain Y first
5. **Check understanding** — end with a question that tests comprehension, not recall

## Anti-Patterns

- **Wikipedia voice** — dry, encyclopedic definitions that don't teach
- **Jargon avalanche** — using five technical terms to explain one
- **False simplicity** — oversimplifying to the point of being wrong
- **Condescension** — "it's actually quite simple" (if it were, they wouldn't be asking)
- **Tangent spirals** — explaining adjacent concepts nobody asked about

## Output Format

```markdown
# [Concept Name]

## The Simple Version
[Level 1: Analogy-based explanation, 3-5 sentences]

## How It Actually Works
[Level 2: Structured explanation with terminology]

## The Full Picture
[Level 3: Technical depth with trade-offs]

---
💡 **Test yourself**: [A question that checks real understanding, not memorization]
```

## Handling "I Still Don't Get It"

If the user says they don't understand:
1. Ask which part is confusing
2. Try a completely different analogy (don't repeat the same one louder)
3. Break the confusing part into smaller sub-concepts
4. Use a concrete example with real numbers or scenarios

## Quick Checklist

1. Did I start with an analogy, not a definition?
2. Can a non-expert follow Level 1?
3. Did I introduce every technical term before using it?
4. Is the analogy honest about its limits?
5. Does the explanation build progressively?
6. Did I end with a comprehension check?
