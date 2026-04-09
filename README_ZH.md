<div align="center">

# MBTI Persona Skill

> 一个可以切换 16 种 MBTI 人格的 AI Skill——不只是语气变化，而是从思维路径、决策方式到对话风格的整体切换。

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Claude Code](https://img.shields.io/badge/Claude%20Code-Skill-blueviolet)](https://claude.ai/code)
[![Codex](https://img.shields.io/badge/Codex-Skill-orange)](https://github.com/openai/codex)
[![OpenClaw](https://img.shields.io/badge/OpenClaw-Skill-green)](https://openclaw.org)
[![AgentSkills](https://img.shields.io/badge/AgentSkills-Standard-green)](https://agentskills.io)

[English](./README.md) · [繁體中文](./README_ZH_TW.md) · [한국어](./README_KO.md) · [日本語](./README_JA.md)

</div>

---

## 特性

- 基于认知功能栈的 MBTI 人格模拟，而非刻板印象
- 同一问题可以用 16 种人格视角分别回答
- 对话中途一句话即可切换人格
- 多轮对话中保持一致的 persona 逻辑
- 支持同一种人格的连续长对话，不会偏移

## 安装

```bash
git clone git@github.com:ChangyuanYU/MBTI-SKILL.git
cd MBTI-SKILL
```

将 `mbti-persona/` 复制到你所用平台的 skill 目录：

| 平台           | 命令                                                   |
|----------------|--------------------------------------------------------|
| **Codex**      | `cp -r mbti-persona ~/.codex/skills/mbti-persona`      |
| **Claude Code** | `cp -r mbti-persona ~/.claude/skills/mbti-persona`     |
| **OpenClaw**   | `cp -r mbti-persona ~/.openclaw/skills/mbti-persona`  |

## 快速开始

在 Claude Code 中输入 `/mbti-persona` 激活 skill，然后告诉模型你想要的人格类型：

```
用 INTJ 的方式和我说话
```

```
切换到 ENFP
```

```
以 ISFJ 的风格安慰我
```

```
现在换成 ENTJ，重新回答刚才的问题
```

## 示例

**职业选择 — INTJ 风格**

> 我有一份稳定工作，但很想辞职创业。

预期：关注长期结构，强调决策框架，较少情绪安抚。

**情绪支持 — ENFP 风格**

> 朋友背叛了我。

预期：关注感受和意义，强调可能性与自我一致，陪你一起想而非直接定论。

**现实建议 — ISTJ 风格**

> 我最近很累，但还有很多责任。

预期：具体、务实、强调可执行步骤。

## 支持的类型

全部 16 种 MBTI 类型：

| 分析家    | 外交家    | 守卫者    | 探险家    |
|-----------|-----------|-----------|-----------|
| INTJ      | INFJ      | ISTJ      | ISTP      |
| INTP      | INFP      | ISFJ      | ISFP      |
| ENTJ      | ENFJ      | ESTJ      | ESTP      |
| ENTP      | ENFP      | ESFJ      | ESFP      |

## 免责声明

这是一个用于对话和 prompt 实验的人格风格 Skill，不是心理测评工具，不应用于临床诊断或严肃心理评估。

---

<div align="center">

MIT License © [ChangyuanYU](https://github.com/ChangyuanYU)

</div>
