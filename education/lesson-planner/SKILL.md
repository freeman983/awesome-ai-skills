---
name: lesson-planner
description: Design structured lesson plans aligned with learning objectives using Bloom's Taxonomy. Use this skill when asked to create a lesson plan, design a course, structure a workshop, plan a training session, or build a curriculum. Triggers include "lesson plan", "course design", "workshop", "training", "curriculum", "teaching plan", "learning objectives", or requests to structure educational content.
language: auto
---

# Lesson Planner

Design lesson plans where every activity directly serves a measurable learning objective. No busywork.

## Core Framework: Backward Design

Plan in reverse:
1. **Define outcomes** — What should learners be able to DO after this lesson?
2. **Design assessments** — How will you KNOW they can do it?
3. **Plan activities** — What experiences will GET them there?

This prevents the #1 mistake: planning activities first and hoping learning happens.

## Bloom's Taxonomy (Action Verbs)

Use these verbs to write measurable objectives. Higher levels build on lower ones.

| Level | Cognitive Process | Action Verbs | Assessment Type |
|-------|------------------|-------------|-----------------|
| **Remember** | Recall facts | List, name, identify, define, label | Quiz, matching |
| **Understand** | Explain ideas | Describe, explain, summarize, paraphrase | Short answer, diagram |
| **Apply** | Use in new situations | Solve, demonstrate, implement, calculate | Problem sets, exercises |
| **Analyze** | Break into parts | Compare, contrast, categorize, distinguish | Case studies, debates |
| **Evaluate** | Justify decisions | Critique, assess, argue, defend, prioritize | Essays, peer review |
| **Create** | Produce new work | Design, construct, develop, compose, propose | Projects, portfolios |

### Writing Objectives

Formula: **Learners will be able to [Bloom's verb] + [specific content] + [condition/context]**

```
✅ "Learners will be able to compare three sorting algorithms by time complexity"
❌ "Learners will understand sorting" (not measurable)

✅ "Learners will be able to design a REST API given a set of business requirements"
❌ "Learners will learn about APIs" (passive, vague)
```

## Lesson Structure

### The 5E Model

| Phase | Duration | Purpose | Activities |
|-------|----------|---------|-----------|
| **Engage** | 10% | Hook attention, activate prior knowledge | Question, demo, story, puzzle |
| **Explore** | 25% | Hands-on discovery before formal instruction | Experiment, group task, investigation |
| **Explain** | 25% | Introduce concepts, connect to exploration | Mini-lecture, discussion, reading |
| **Elaborate** | 30% | Apply to new contexts, deepen understanding | Practice, project, case study |
| **Evaluate** | 10% | Check understanding, reflect | Quiz, presentation, self-assessment |

### Time Allocation by Lesson Length

| Lesson Length | Engage | Explore | Explain | Elaborate | Evaluate |
|--------------|--------|---------|---------|-----------|----------|
| 30 min | 3 min | 7 min | 8 min | 9 min | 3 min |
| 60 min | 6 min | 15 min | 15 min | 18 min | 6 min |
| 90 min | 9 min | 22 min | 23 min | 27 min | 9 min |
| 3 hours | 18 min | 45 min | 45 min | 54 min | 18 min |

## Differentiation Strategies

### For Mixed-Level Groups

| Strategy | How | When |
|----------|-----|------|
| **Tiered tasks** | Same concept, different complexity | Elaborate phase |
| **Choice boards** | Multiple paths to same objective | Explore/Elaborate |
| **Scaffolding** | Graduated support removal | Throughout |
| **Flexible grouping** | Pair strong with developing | Explore phase |

## Assessment Alignment

Every objective needs a matching assessment. No orphan objectives.

```
Objective: "Compare three sorting algorithms by time complexity"
    ↓
Assessment: "Given an unsorted array of 1M elements, which algorithm would you choose and why?"
    ↓
Activity: "Run each algorithm on datasets of increasing size, record times, plot results"
```

## Language Rules

- Match the language of the user's request by default
- If the user explicitly specifies a language (e.g., "in English", "用中文"), use that language for all output
- Keep proper nouns, brand names, and technical terms in their original language

## Output Format

```markdown
# Lesson Plan: [Title]

## Overview
- **Topic**: [Subject area]
- **Duration**: [Time]
- **Level**: [Beginner / Intermediate / Advanced]
- **Prerequisites**: [What learners should already know]

## Learning Objectives
By the end of this lesson, learners will be able to:
1. [Bloom's verb] + [content] + [context] (Bloom's level)
2. [Bloom's verb] + [content] + [context] (Bloom's level)
3. [Bloom's verb] + [content] + [context] (Bloom's level)

## Materials Needed
- [List of resources, tools, handouts]

## Lesson Flow

### 1. Engage (X min)
**Activity**: [Description]
**Purpose**: [Why this hooks attention]

### 2. Explore (X min)
**Activity**: [Description]
**Grouping**: [Individual / Pairs / Small groups]
**Deliverable**: [What learners produce]

### 3. Explain (X min)
**Content**: [Key concepts to cover]
**Method**: [Lecture / Discussion / Demo]
**Check**: [Quick comprehension check]

### 4. Elaborate (X min)
**Activity**: [Description]
**Differentiation**: [How to support different levels]
**Deliverable**: [What learners produce]

### 5. Evaluate (X min)
**Method**: [Quiz / Presentation / Reflection]
**Success criteria**: [How you know objectives are met]

## Assessment Rubric
| Criteria | Developing | Proficient | Advanced |
|----------|-----------|-----------|---------|
| [Obj 1]  | [Description] | [Description] | [Description] |
| [Obj 2]  | [Description] | [Description] | [Description] |

## Extension Activities
- [For fast finishers]
- [For homework/follow-up]

## Instructor Notes
- [Common misconceptions to address]
- [Timing adjustments if running short/long]
```

## Anti-Patterns

- **Activity-first planning** — choosing fun activities then retrofitting objectives
- **Passive consumption** — lecture-only with no active learning
- **Unmeasurable objectives** — "understand", "appreciate", "be aware of"
- **Assessment mismatch** — testing recall when the objective is application
- **Time blindness** — planning 90 minutes of content for a 60-minute slot

## Quick Checklist

1. Every objective uses a Bloom's action verb?
2. Every objective has a matching assessment?
3. Activities build toward objectives (not just fill time)?
4. Time allocations are realistic?
5. Differentiation included for mixed levels?
6. Materials list is complete?
