---
name: brand-voice
description: Define and document a brand's voice, tone, and communication style. Use this skill when asked to create brand guidelines, define brand voice, establish tone of voice, create a style guide, or build communication standards. Triggers include "brand voice", "tone of voice", "brand guidelines", "style guide", "brand personality", "communication style", "brand identity", or requests to define how a brand should sound.
language: auto
---

# Brand Voice Designer

Define a brand voice that's consistent, recognizable, and impossible to fake. A brand voice isn't what you say — it's how you say everything.

## Core Concept

### Voice vs. Tone
- **Voice** = Personality. Constant. Who you are. (Confident, warm, witty)
- **Tone** = Mood. Variable. Adapts to context. (Celebratory in launches, empathetic in outages)

A person has one voice but many tones. So does a brand.

## Voice Definition Framework

### Step 1: Brand Personality Spectrum

Position the brand on each axis:

```
Formal ←——●————————→ Casual
Reserved ←————●——————→ Expressive
Serious ←————————●——→ Playful
Authoritative ←——●————————→ Approachable
Technical ←————————●——→ Simple
Traditional ←————●——————→ Innovative
```

### Step 2: Voice Attributes (Pick 3-4)

Choose 3-4 adjectives that define the voice. For each, define what it IS and what it ISN'T.

| Attribute | What It Is | What It Isn't |
|-----------|-----------|--------------|
| **Confident** | Direct, clear, decisive | Arrogant, dismissive, aggressive |
| **Warm** | Friendly, empathetic, human | Saccharine, unprofessional, vague |
| **Witty** | Clever, surprising, sharp | Sarcastic, try-hard, offensive |
| **Expert** | Knowledgeable, precise, credible | Jargon-heavy, condescending, academic |

### Step 3: Voice Chart

For each attribute, provide a spectrum with examples:

```markdown
## Attribute: [Name]

**Definition**: [One sentence]

**Do**: [Specific behaviors]
**Don't**: [Specific anti-behaviors]

**Example — On brand**:
"We shipped the fix in 47 minutes. Here's what went wrong and how we're preventing it."

**Example — Off brand**:
"We sincerely apologize for any inconvenience this may have caused to our valued customers."
```

## Tone Adaptation Matrix

Same voice, different tones across contexts:

| Context | Tone Shift | Example |
|---------|-----------|---------|
| **Product launch** | Excited, confident | "It's here. And it's faster than we promised." |
| **Error/Outage** | Honest, calm, accountable | "We broke search for 12 minutes. Here's exactly what happened." |
| **Onboarding** | Encouraging, clear | "You're set up. Let's build something." |
| **Pricing page** | Transparent, no-pressure | "Pick what works. Change anytime." |
| **Support reply** | Patient, solution-focused | "Got it. Here's the fix — takes about 2 minutes." |
| **Social media** | Relaxed, human | "Monday mood: debugging code we wrote on Friday." |
| **Legal/Policy** | Clear, respectful | "Your data is yours. Here's exactly what we collect and why." |
| **Bad news** | Direct, empathetic | "We're sunsetting X. Here's why, and here's your migration path." |

## Writing Rules

### Vocabulary

Define three lists:

**Words We Use** (brand vocabulary):
```
build, ship, craft, simple, clear, fast, honest, together
```

**Words We Avoid** (off-brand vocabulary):
```
leverage, synergy, utilize, disrupt, revolutionary, best-in-class, world-class
```

**Words We Never Use** (hard no):
```
[Competitor names in negative context], profanity, discriminatory language
```

### Sentence Style

| Rule | Example |
|------|---------|
| Short sentences preferred | "It works. It's fast. It's free." |
| Active voice always | "We fixed the bug" not "The bug was fixed" |
| Second person for users | "You can..." not "Users can..." |
| Contractions are fine | "We're" not "We are" (unless emphasis needed) |
| Numbers over words | "3 steps" not "three steps" |

### Punctuation & Formatting

| Element | Rule |
|---------|------|
| Exclamation marks | Max 1 per page. Earn it. |
| Emojis | [Define: Never / Sparingly / Freely] |
| Capitalization | Sentence case for headings. No ALL CAPS. |
| Oxford comma | [Yes / No — pick one, be consistent] |
| Ellipsis | Avoid. They signal uncertainty. |

## Channel-Specific Guidelines

| Channel | Length | Formality | Special Rules |
|---------|--------|-----------|--------------|
| Website copy | Concise | Medium | Scannable, benefit-led |
| Email | Medium | Medium-High | Clear subject lines, one CTA |
| Social (X) | Short | Low | Personality-forward, conversational |
| Social (LinkedIn) | Medium | Medium | Thought leadership, professional |
| Documentation | Detailed | Medium | Task-oriented, no marketing speak |
| In-app UI | Minimal | Low | Action verbs, no jargon |
| Blog | Long-form | Medium | Opinionated, educational |

## Language Rules

- Match the language of the user's request by default
- If the user explicitly specifies a language (e.g., "in English", "用中文"), use that language for all output
- Keep proper nouns, brand names, and technical terms in their original language

## Output Format

```markdown
# [Brand Name] — Voice & Tone Guide

## Brand Personality
[2-3 sentences describing who the brand is as a person]

## Voice Attributes

### 1. [Attribute]
**Definition**: [One sentence]
**Do**: [Behaviors]
**Don't**: [Anti-behaviors]
**On-brand**: "[Example]"
**Off-brand**: "[Example]"

### 2. [Attribute]
...

### 3. [Attribute]
...

## Tone Matrix

| Context | Tone | Example |
|---------|------|---------|
| [Context] | [Tone words] | "[Example]" |
...

## Writing Rules
- [Rule 1]
- [Rule 2]
...

## Vocabulary
**Use**: [word list]
**Avoid**: [word list]
**Never**: [word list]

## Channel Guidelines
[Table or per-channel sections]

## Quick Reference Card
[One-page summary for daily use]
```

## Anti-Patterns

- **Voice by committee** — trying to be everything to everyone (results in bland)
- **Aspiration without reality** — defining a voice the team can't actually write in
- **Too many attributes** — more than 4 voice attributes = no voice at all
- **No examples** — rules without before/after examples are useless
- **Ignoring context** — same tone for error messages and marketing (tone must adapt)
- **Corporate default** — falling back to "professional" when unsure (professional is not a personality)

## Quick Checklist

1. Can someone new to the team write on-brand copy using this guide?
2. Are there clear examples for every rule?
3. Does the voice feel like a real person, not a committee?
4. Is the tone matrix covering all key contexts?
5. Are the "don't" examples as clear as the "do" examples?
6. Would you recognize this brand's writing without seeing the logo?
