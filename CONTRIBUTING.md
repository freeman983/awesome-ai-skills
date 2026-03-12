# Contributing to Awesome AI Skills

Thanks for your interest in contributing! This project thrives on community-submitted skills.

## Submitting a New Skill

### 1. Choose a Category

Place your skill in the appropriate category directory:

| Category | For skills about... |
|----------|-------------------|
| `education/` | Teaching, learning, explaining concepts |
| `creative/` | Naming, branding, ideation, design thinking |
| `writing/` | Content creation for specific platforms or formats |
| `research/` | Investigation, analysis, synthesis |
| `productivity/` | Workflows, planning, organization |
| `engineering/` | Code review, architecture, debugging |

Don't see a fitting category? Propose a new one in your PR description.

### 2. Create the Skill Directory

```
category/your-skill-name/
└── SKILL.md
```

Directory name = skill ID. Use `kebab-case`.

### 3. Write the SKILL.md

Every `SKILL.md` must include:

**Front matter** (required):

```yaml
---
name: your-skill-name
description: Clear description of when to use this skill. Include trigger words and phrases.
---
```

**Body** (required sections):

1. **Title & purpose** — What this skill does in one sentence
2. **Core framework** — The methodology or mental model driving the skill
3. **Output structure** — Templates or formats the LLM should follow
4. **Quality criteria** — What separates good output from bad

### 4. Quality Checklist

Before submitting, verify:

- [ ] `SKILL.md` has valid YAML front matter with `name` and `description`
- [ ] The skill is **self-contained** — no external dependencies or cross-references
- [ ] The skill is **framework-driven** — built on a proven methodology, not just "write good X"
- [ ] Output templates are **concrete** — the LLM knows exactly what format to produce
- [ ] You've tested the skill with at least 2 different LLMs (Claude, GPT, etc.)
- [ ] The description includes **trigger words** so users know when to reach for this skill

### 5. Submit a Pull Request

1. Fork this repository
2. Create a branch: `git checkout -b add-skill-your-skill-name`
3. Add your skill directory and `SKILL.md`
4. Submit a PR with:
   - What the skill does
   - Why it's useful
   - Example input/output showing the skill in action

## Improving Existing Skills

Found a way to make an existing skill better? PRs welcome. Common improvements:

- Adding edge case handling
- Improving output templates
- Adding new frameworks or methodologies
- Fixing unclear instructions
- Adding examples

## Style Guidelines

- Write like you're briefing a domain expert, not writing a textbook
- Use tables for structured information
- Use code blocks for templates and examples
- Keep it practical — every section should directly improve LLM output
- Avoid filler phrases ("In this skill, we will..." — just do it)

## Code of Conduct

Be respectful, constructive, and focused on making skills better. That's it.
