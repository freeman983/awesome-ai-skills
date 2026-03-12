# Awesome AI Skills

精选高质量 AI 技能提示词集合 — 复制、粘贴，即可在任何大语言模型中使用。

[English](README.md)

## 什么是 Skill？

**Skill** 是一个结构化的提示词文件（`SKILL.md`），能将通用大语言模型变成领域专家。每个 Skill 包含：

- **元数据** — 名称、描述、触发词
- **领域知识** — 框架、原则、最佳实践
- **输出模板** — 结构化格式，确保输出一致性
- **质量标准** — 明确定义什么是好的输出

无需框架。无需 API Key。无需依赖。复制 `SKILL.md` 内容到系统提示词即可。

## 技能列表

### 教育

| 技能 | 描述 |
|------|------|
| [概念解释器](education/explain-concept/SKILL.md) | 用费曼技巧解释任何概念，支持三级深度递进 |
| [闪卡生成器](education/flashcard-maker/SKILL.md) | 生成适配间隔重复学习的闪卡（兼容 Anki） |
| [课程设计师](education/lesson-planner/SKILL.md) | 基于布鲁姆分类法和逆向设计的课程规划 |

### 创意

| 技能 | 描述 |
|------|------|
| [命名生成器](creative/naming-generator/SKILL.md) | 为产品、公司、功能生成创意名称，含语言学分析 |
| [融资 PPT](creative/pitch-deck/SKILL.md) | 按成熟融资框架创建投资人演示大纲 |
| [品牌声音](creative/brand-voice/SKILL.md) | 定义和文档化品牌的声音、语调和沟通风格 |

### 写作

| 技能 | 描述 |
|------|------|
| [公众号文章](writing/writing-wechat-article/SKILL.md) | 撰写适配移动端阅读和传播的微信公众号文章 |

### 研究

| 技能 | 描述 |
|------|------|
| [深度研究](research/research-topic/SKILL.md) | 使用钻石框架进行结构化多角度深度研究 |

## 使用方法

### 方式一：直接复制粘贴

1. 打开任意 `SKILL.md` 文件
2. 复制全部内容
3. 粘贴为系统提示词（或添加到消息前面），在 ChatGPT、Claude 或任何大模型中使用
4. 开始提问

### 方式二：作为应用的系统提示词

```python
# 示例：加载 Skill 作为系统提示词
with open("education/explain-concept/SKILL.md") as f:
    skill_prompt = f.read()

response = client.messages.create(
    model="claude-sonnet-4-20250514",
    system=skill_prompt,
    messages=[{"role": "user", "content": "解释量子纠缠"}]
)
```

### 方式三：配合 AI IDE 使用

将 `SKILL.md` 文件放入项目的 skill 目录。大多数 AI 驱动的 IDE（Claude Code、Cursor 等）可以自动加载为上下文。

## SKILL.md 格式规范

```markdown
---
name: skill-id
description: 何时使用此技能。包含触发词。
---

# 技能标题

[领域知识、框架、模板、质量标准...]
```

Front matter 使用 YAML 格式。正文是标准 Markdown — 像给领域专家做简报一样写。

### 设计原则

1. **自包含** — 每个技能独立工作，无需交叉引用
2. **框架驱动** — 基于成熟方法论（费曼技巧、布鲁姆分类法等）
3. **输出导向** — 清晰的模板让 LLM 知道该产出什么
4. **质量把关** — 明确的标准定义什么是好的输出

## 贡献

请参阅 [CONTRIBUTING.md](CONTRIBUTING.md) 了解如何提交新技能。

## 许可证

[MIT](LICENSE)
