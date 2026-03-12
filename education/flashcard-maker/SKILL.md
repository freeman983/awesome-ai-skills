---
name: flashcard-maker
description: Generate high-quality flashcards optimized for spaced repetition learning. Use this skill when asked to create flashcards, study cards, Anki decks, revision materials, or memory aids. Triggers include "flashcard", "Anki", "study cards", "spaced repetition", "memorize", "review cards", or requests to turn content into learnable chunks.
---

# Flashcard Maker

Generate flashcards optimized for spaced repetition systems like Anki. Good flashcards test understanding, not recall of exact wording.

## Core Principles

### Minimum Information Principle
Each card tests exactly ONE piece of knowledge. If a card has "and" in the answer, split it.

### Active Recall Over Recognition
Cards should require the learner to produce the answer, not recognize it from options.

### Context Independence
Each card must be understandable without seeing other cards. No "as mentioned in card #3".

## Card Types

### Type 1: Basic (Front → Back)
Best for: Definitions, facts, translations

```
Q: What is [term]?
A: [Concise definition in your own words]
```

### Type 2: Cloze Deletion
Best for: Formulas, sequences, key phrases

```
{{c1::TCP}} operates at the {{c2::transport}} layer of the OSI model.
```

### Type 3: Reversed
Best for: Bidirectional knowledge (term ↔ definition)

```
Q: What is the term for [definition]?
A: [Term]

Q: Define [term].
A: [Definition]
```

### Type 4: Image Occlusion
Best for: Diagrams, anatomy, maps

```
Q: [Image with labeled part hidden]
A: [Hidden label revealed]
```

### Type 5: Application
Best for: Deep understanding, problem-solving

```
Q: [Scenario or problem]
   How would you apply [concept]?
A: [Solution with reasoning]
```

## Writing Rules

### Questions
- Be specific — "What does X do?" not "Tell me about X"
- Use consistent phrasing for similar card types
- Avoid yes/no questions (too easy to guess)
- Include context cues when ambiguity exists: "In [field], what is..."

### Answers
- Keep under 20 words when possible
- Use bullet points for multi-part answers (max 3 bullets)
- Bold the key term or number
- Include a mnemonic hint if the fact is hard to remember

### Distractors (for multiple choice)
- Make wrong answers plausible, not obviously wrong
- Use common misconceptions as distractors
- Keep all options similar in length and style
- Never use "all of the above" or "none of the above"

## Difficulty Calibration

| Difficulty | Card Style | Example |
|-----------|-----------|---------|
| Easy | Direct fact recall | "What year did X happen?" |
| Medium | Apply a concept | "Given X scenario, what principle applies?" |
| Hard | Synthesize or compare | "How does X differ from Y in context Z?" |

Generate a mix: 40% easy, 40% medium, 20% hard.

## Output Format

### Standard Format (Tab-separated, Anki-importable)

```
Front\tBack\tTags
What is [concept]?\t[Answer]\t[topic]::[subtopic]
```

### Rich Format (Markdown)

```markdown
## Deck: [Topic Name]
Tags: #topic #subtopic

---

### Card 1
**Q:** [Question]
**A:** [Answer]
**Tags:** topic::subtopic
**Difficulty:** easy | medium | hard

---

### Card 2
...
```

### Cloze Format

```
{{c1::Answer}} is the [context for the blank].
Tags: topic::subtopic
```

## Tag Hierarchy

Use `::` separator for nested tags (Anki convention):

```
biology::cell-biology::mitosis
programming::python::data-structures
history::world-war-2::pacific-theater
```

## Anti-Patterns

- **Verbatim textbook** — copying sentences from source material (rephrase in your own words)
- **Trick questions** — testing gotchas instead of understanding
- **Vague questions** — "What about mitosis?" (what about it?)
- **Essay answers** — if the answer is a paragraph, the card needs splitting
- **Orphan cards** — facts without context (why does this matter?)
- **Synonym traps** — accepting only one specific word when multiple are correct

## Workflow

### From Text/Article
1. Identify key concepts, facts, and relationships
2. Create basic cards for terminology
3. Create application cards for concepts
4. Create comparison cards for related ideas
5. Add tags for organization
6. Review for minimum information principle

### From Lecture/Video
1. Extract main claims and supporting evidence
2. Create cards for each claim-evidence pair
3. Add process/sequence cards for workflows
4. Create "why" cards for reasoning chains

## Quick Checklist

1. Does each card test exactly one thing?
2. Can the card be understood without other cards?
3. Is the answer under 20 words?
4. Would a wrong answer reveal a real knowledge gap?
5. Are tags hierarchical and consistent?
6. Mix of difficulty levels present?
