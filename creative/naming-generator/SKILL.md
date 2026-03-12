---
name: naming-generator
description: Generate creative, memorable names for products, companies, features, or projects with linguistic analysis. Use this skill when asked to name something, brainstorm names, find a brand name, name a product, name a feature, or come up with creative naming options. Triggers include "name", "naming", "brand name", "product name", "company name", "what should I call", or requests for creative naming suggestions.
language: auto
---

# Naming Generator

Generate names that are memorable, meaningful, and available. Good names don't just sound nice — they work as strategic assets.

## Naming Dimensions

Every name sits on these spectrums. Clarify positioning before generating.

```
Descriptive ←————————→ Abstract
  "BookKeeper"              "Notion"

Serious ←————————→ Playful
  "Palantir"               "Slack"

Technical ←————————→ Human
  "PostgreSQL"             "Alexa"

Short ←————————→ Compound
  "Arc"                    "Masterclass"
```

## Name Categories

### 1. Descriptive
Tells you what it does. Easy to understand, hard to trademark.
- Examples: YouTube, Facebook, WeChat, PayPal
- Best for: Features, internal tools, early-stage products
- Risk: Generic, forgettable, trademark conflicts

### 2. Metaphorical
Borrows meaning from another domain. Evocative and memorable.
- Examples: Amazon (vast), Apple (simple/fresh), Slack (ease), Notion (idea)
- Best for: Consumer brands, platforms
- Technique: Find a quality of your product → find objects/concepts that embody it

### 3. Invented
Made-up words. Unique and trademarkable, but require marketing investment.
- Examples: Spotify, Hulu, Figma, Vercel
- Best for: Companies, major products
- Techniques: Blend two words, modify spelling, combine Latin/Greek roots

### 4. Acronym
Initials or abbreviations. Professional but cold.
- Examples: IBM, AWS, HBO
- Best for: Enterprise, government, technical standards
- Rule: Only works if the full name is already known or irrelevant

### 5. Founder/Person
Named after a person. Builds personal brand.
- Examples: Tesla, Bloomberg, Dyson
- Best for: Luxury, personal brands, consulting
- Risk: Tied to one person's reputation

### 6. Portmanteau
Two words blended into one. Clever when done well, cringe when forced.
- Examples: Pinterest (pin + interest), Instagram (instant + telegram), Groupon (group + coupon)
- Best for: Consumer apps, social platforms
- Rule: Both source words should be recognizable

## Evaluation Criteria

Score each name candidate on these dimensions:

| Criterion | Weight | Test |
|-----------|--------|------|
| **Memorable** | High | Can someone recall it after hearing once? |
| **Pronounceable** | High | Can it be said aloud without confusion? |
| **Spellable** | High | Can someone type it after hearing it? |
| **Meaningful** | Medium | Does it evoke the right associations? |
| **Distinctive** | High | Does it stand out from competitors? |
| **Scalable** | Medium | Will it still fit if the product expands? |
| **Domain-friendly** | Medium | Is a reasonable .com/.io available? |
| **Cross-cultural** | Low-High | Does it work in target markets? (check for negative meanings) |

## Generation Process

### Step 1: Define the Brief
- What is the product/company/feature?
- Who is the audience?
- What feeling should the name evoke?
- What names do competitors use? (to differentiate)
- Any constraints? (length, language, domain availability)

### Step 2: Generate Candidates (aim for 20-30)

**Technique 1: Word Association**
Start with core concepts → branch out 3 levels deep
```
Bookmark → Save → Vault → Haven
Bookmark → Navigate → Compass → North
Bookmark → Collect → Gather → Harvest
```

**Technique 2: Thesaurus Mining**
Look up synonyms in multiple languages
```
"Fast" → Swift, Rapid, Presto (Italian), Hayai (Japanese), Veloz (Spanish)
```

**Technique 3: Root Combination**
Combine Latin/Greek roots related to the concept
```
"Light" (lux/lumen) + "Path" (via/odos) → Luxvia, Luminos, Vianova
```

**Technique 4: Metaphor Mapping**
Find objects that share a quality with your product
```
Quality: "Organizing chaos" → Compass, Lighthouse, Anchor, Prism, Lens
```

**Technique 5: Sound Symbolism**
Certain sounds evoke certain feelings:
- Hard consonants (K, T, P) → Strong, decisive: Kodak, TikTok
- Soft consonants (S, L, M) → Smooth, gentle: Silk, Loom, Murmur
- Short vowels → Quick, snappy: Bit, Zip, Snap
- Long vowels → Expansive, premium: Bloom, Breeze, Gleam

### Step 3: Filter and Rank
Apply evaluation criteria. Eliminate names that fail on any "High" weight criterion.

### Step 4: Stress Test
For top 3-5 candidates:
- Say it in a sentence: "Have you tried [Name]?"
- Imagine the logo
- Check for unintended meanings in other languages
- Search for existing trademarks
- Check domain availability patterns (.com, .io, .co, .app)

## Language Rules

- Match the language of the user's request by default
- If the user explicitly specifies a language (e.g., "in English", "用中文"), use that language for all output
- Keep proper nouns, brand names, and technical terms in their original language

## Output Format

```markdown
# Naming Options: [What We're Naming]

## Brief
- **Product**: [Description]
- **Audience**: [Who]
- **Feeling**: [What emotion/association]
- **Constraints**: [Any limits]

## Top Recommendations

### 1. [Name] ⭐
- **Category**: [Descriptive/Metaphorical/Invented/...]
- **Meaning**: [Why this name works]
- **Pronunciation**: [Phonetic guide if needed]
- **Domain ideas**: [name.com, getname.io, etc.]
- **Score**: Memorable ●●●●○ | Distinctive ●●●●● | Scalable ●●●○○

### 2. [Name]
...

### 3. [Name]
...

## Honorable Mentions
- [Name] — [One-line rationale]
- [Name] — [One-line rationale]
- [Name] — [One-line rationale]

## Names to Avoid
- [Name] — [Why it doesn't work]
```

## Anti-Patterns

- **Too clever** — puns that require explanation
- **Unpronounceable** — consonant clusters nobody can say (Xlyph)
- **Already taken** — not checking existing trademarks
- **Too narrow** — "EmailSorter" when the product might expand beyond email
- **Cultural blindness** — not checking meanings in target markets
- **Trend-chasing** — adding "AI" or ".io" to everything

## Quick Checklist

1. Does the name pass the "phone test"? (Can you say it over the phone and have someone spell it?)
2. Is it distinct from competitors?
3. Does it evoke the right feeling?
4. Will it still work in 5 years if the product evolves?
5. Have you checked for negative meanings in other languages?
6. Are reasonable domains available?
