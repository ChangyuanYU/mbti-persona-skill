<div align="center">

# MBTI Persona Skill

> A single AI skill that switches between all 16 MBTI personalities — changing thought process, decision style, and conversational feel, not just tone.

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Claude Code](https://img.shields.io/badge/Claude%20Code-Skill-blueviolet)](https://claude.ai/code)
[![Codex](https://img.shields.io/badge/Codex-Skill-orange)](https://github.com/openai/codex)
[![OpenClaw](https://img.shields.io/badge/OpenClaw-Skill-green)](https://openclaw.org)
[![AgentSkills](https://img.shields.io/badge/AgentSkills-Standard-green)](https://agentskills.io)

[简体中文](./README_ZH.md) · [한국어](./README_KO.md) · [日本語](./README_JA.md)

</div>

---

## Features

- Respond in the cognitive style of any MBTI type — not stereotypes, but function-stack-driven thinking
- Answer the same question from 16 different personality perspectives
- Switch types mid-conversation with a single sentence
- Maintain consistent persona logic across multi-turn dialogue
- Keep one MBTI persona for an extended conversation without drifting

## Installation

```bash
git clone git@github.com:ChangyuanYU/MBTI-SKILL.git
cd MBTI-SKILL
```

Copy `mbti-persona/` to your platform's skill directory:

| Platform       | Command                                                |
|----------------|--------------------------------------------------------|
| **Codex**      | `cp -r mbti-persona ~/.codex/skills/mbti-persona`      |
| **Claude Code** | `cp -r mbti-persona ~/.claude/skills/mbti-persona`     |
| **OpenClaw**   | `cp -r mbti-persona ~/.openclaw/skills/mbti-persona`  |

## Quick Start

Tell the model which type you want:

```
Talk to me as INTJ
```

```
Switch to ENFP
```

```
Comfort me in an ISFJ style
```

```
Now answer the same question again as ENTJ
```

## Examples

**Career choice — INTJ style**

> I have a stable job, but I want to quit and start a company.

Expected: structural, strategic, less emotionally reassuring.

**Emotional support — ENFP style**

> My friend betrayed me.

Expected: feeling-aware, meaning-oriented, exploratory rather than final.

**Practical advice — ISTJ style**

> I'm exhausted, but I still have many responsibilities.

Expected: concrete, practical, step-oriented.

## Supported Types

All 16 MBTI types:

| Analysts  | Diplomats | Sentinels | Explorers |
|-----------|-----------|-----------|-----------|
| INTJ      | INFJ      | ISTJ      | ISTP      |
| INTP      | INFP      | ISFJ      | ISFP      |
| ENTJ      | ENFJ      | ESTJ      | ESTP      |
| ENTP      | ENFP      | ESFJ      | ESFP      |

## Disclaimer

This is a persona-style skill for dialogue and prompt experiments. It is not a psychological assessment tool and should not be used for diagnosis or clinical interpretation.

---

<div align="center">

MIT License © [ChangyuanYU](https://github.com/ChangyuanYU)

</div>
