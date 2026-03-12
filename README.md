# Awesome AI Skills

A curated collection of high-quality AI skill prompts — copy, paste, and use with any LLM.

[中文文档](README_CN.md)

## What is a Skill?

A **Skill** is a structured prompt (stored as `SKILL.md`) that turns a general-purpose LLM into a domain expert. Each skill contains:

- **Front matter** — metadata (name, description, triggers)
- **Domain knowledge** — frameworks, principles, best practices
- **Output templates** — structured formats for consistent results
- **Quality criteria** — what "good" looks like for this domain

No framework required. No API keys. No dependencies. Just copy the `SKILL.md` content into your system prompt and go.

## Skills

### Education

| Skill | Description |
|-------|-------------|
| [Explain Concept](education/explain-concept/SKILL.md) | Explain any concept using the Feynman Technique with progressive depth levels |
| [Flashcard Maker](education/flashcard-maker/SKILL.md) | Generate flashcards optimized for spaced repetition (Anki-compatible) |
| [Lesson Planner](education/lesson-planner/SKILL.md) | Design lesson plans using Bloom's Taxonomy and backward design |

### Creative

| Skill | Description |
|-------|-------------|
| [Naming Generator](creative/naming-generator/SKILL.md) | Generate creative names for products, companies, features with linguistic analysis |
| [Pitch Deck](creative/pitch-deck/SKILL.md) | Create investor pitch deck outlines following proven fundraising frameworks |
| [Brand Voice](creative/brand-voice/SKILL.md) | Define and document a brand's voice, tone, and communication style |

### Writing

| Skill | Description |
|-------|-------------|
| [WeChat Article](writing/writing-wechat-article/SKILL.md) | Write engaging WeChat Official Account articles optimized for mobile reading |

### Research

| Skill | Description |
|-------|-------------|
| [Deep Topic Research](research/research-topic/SKILL.md) | Conduct structured multi-angle research using the Diamond Framework |

## How to Use

### Option 1: Direct Copy-Paste

1. Open any `SKILL.md` file
2. Copy the entire content
3. Paste it as a system prompt (or prepend to your message) in ChatGPT, Claude, or any LLM
4. Start asking questions in that domain

### Option 2: As System Prompts in Your App

```python
# Example: Load a skill as system prompt
with open("education/explain-concept/SKILL.md") as f:
    skill_prompt = f.read()

response = client.messages.create(
    model="claude-sonnet-4-20250514",
    system=skill_prompt,
    messages=[{"role": "user", "content": "Explain quantum entanglement"}]
)
```

### Option 3: With Claude Code / Cursor / AI IDEs

Place `SKILL.md` files in your project's skill directory. Most AI-powered IDEs can pick them up as context.

## SKILL.md Format

```markdown
---
name: skill-id
description: When to use this skill. Include trigger words.
language: auto
---

# Skill Title

[Domain knowledge, frameworks, templates, quality criteria...]
```

The front matter uses YAML. The body is standard Markdown — write it like you're briefing a domain expert.

### Language Control

Every skill includes a `language` field in front matter and a `Language Rules` section in the body:

| Value | Behavior |
|-------|----------|
| `auto` | Match the user's input language (default) |
| `en` | Always output in English |
| `zh-CN` | Always output in Simplified Chinese |
| Any locale | Force that language |

With `auto`, if you ask in Chinese you get Chinese output. If you ask in English you get English. Users can also override inline: "用中文写" or "write in English".

### Design Principles

1. **Self-contained** — Each skill works independently, no cross-references needed
2. **Framework-driven** — Built on proven methodologies (Feynman Technique, Bloom's Taxonomy, etc.)
3. **Output-oriented** — Clear templates so the LLM knows exactly what to produce
4. **Quality-gated** — Explicit criteria for what makes a good output

## Examples

- [NavHub Pitch Deck](examples/navhub-pitch-deck.md) — A real-world pitch deck outline generated using the [Pitch Deck](creative/pitch-deck/SKILL.md) skill

## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines on submitting new skills.

## License

[MIT](LICENSE)
