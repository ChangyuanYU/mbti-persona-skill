<div align="center">

# MBTI Persona Skill

> 一個可以切換 16 種 MBTI 人格的 AI Skill——不只是語氣變化，而是從思維路徑、決策方式到對話風格的整體切換。

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Claude Code](https://img.shields.io/badge/Claude%20Code-Skill-blueviolet)](https://claude.ai/code)
[![Codex](https://img.shields.io/badge/Codex-Skill-orange)](https://github.com/openai/codex)
[![OpenClaw](https://img.shields.io/badge/OpenClaw-Skill-green)](https://openclaw.org)
[![AgentSkills](https://img.shields.io/badge/AgentSkills-Standard-green)](https://agentskills.io)

[English](./README.md) · [简体中文](./README_ZH.md) · [한국어](./README_KO.md) · [日本語](./README_JA.md)

</div>

---

## 特性

- 基於認知功能棧的 MBTI 人格模擬，而非刻板印象
- 同一問題可以用 16 種人格視角分別回答
- 對話中途一句話即可切換人格
- 多輪對話中保持一致的 persona 邏輯
- 支援同一種人格的連續長對話，不會偏移

## 安裝

```bash
git clone git@github.com:ChangyuanYU/MBTI-SKILL.git
cd MBTI-SKILL
```

將 `mbti-persona/` 複製到你所用平台的 skill 目錄：

| 平台           | 命令                                                   |
|----------------|--------------------------------------------------------|
| **Codex**      | `cp -r mbti-persona ~/.codex/skills/mbti-persona`      |
| **Claude Code** | `cp -r mbti-persona ~/.claude/skills/mbti-persona`     |
| **OpenClaw**   | `cp -r mbti-persona ~/.openclaw/skills/mbti-persona`  |

## 快速開始

在 Claude Code 中輸入 `/mbti-persona` 啟用 skill，然後告訴模型你想要的人格類型：

```
用 INTJ 的方式和我說話
```

```
切換到 ENFP
```

```
以 ISFJ 的風格安慰我
```

```
現在換成 ENTJ，重新回答剛才的問題
```

## 範例

**職業選擇 — INTJ 風格**

> 我有一份穩定工作，但很想辭職創業。

預期：關注長期結構，強調決策框架，較少情緒安撫。

**情緒支持 — ENFP 風格**

> 朋友背叛了我。

預期：關注感受和意義，強調可能性與自我一致，陪你一起想而非直接定論。

**現實建議 — ISTJ 風格**

> 我最近很累，但還有很多責任。

預期：具體、務實、強調可執行步驟。

## 支援的類型

全部 16 種 MBTI 類型：

| 分析家    | 外交家    | 守衛者    | 探險家    |
|-----------|-----------|-----------|-----------|
| INTJ      | INFJ      | ISTJ      | ISTP      |
| INTP      | INFP      | ISFJ      | ISFP      |
| ENTJ      | ENFJ      | ESTJ      | ESTP      |
| ENTP      | ENFP      | ESFJ      | ESFP      |

## 免責聲明

這是一個用於對話和 prompt 實驗的人格風格 Skill，不是心理測評工具，不應用於臨床診斷或嚴肅心理評估。

---

<div align="center">

MIT License © [ChangyuanYU](https://github.com/ChangyuanYU)

</div>
