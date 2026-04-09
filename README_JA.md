<div align="center">

# MBTI Persona Skill

> 16種類の MBTI 人格を切り替えられる AI Skill——口調だけでなく、考え方、判断傾向、会話の雰囲気まで変えます。

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Claude Code](https://img.shields.io/badge/Claude%20Code-Skill-blueviolet)](https://claude.ai/code)
[![Codex](https://img.shields.io/badge/Codex-Skill-orange)](https://github.com/openai/codex)
[![OpenClaw](https://img.shields.io/badge/OpenClaw-Skill-green)](https://openclaw.org)
[![AgentSkills](https://img.shields.io/badge/AgentSkills-Standard-green)](https://agentskills.io)

[English](./README.md) · [简体中文](./README_ZH.md) · [한국어](./README_KO.md)

</div>

---

## 特徴

- 認知機能スタックに基づく MBTI 人格シミュレーション（ステレオタイプではありません）
- 同じ質問を 16 種類の人格視点で回答可能
- 会話中に一言で人格を切り替えられる
- 複数ターンでも一貫した persona ロジックを維持
- 同じ人格のまま長い連続対話も可能（ドリフトしません）

## インストール

```bash
git clone git@github.com:ChangyuanYU/MBTI-SKILL.git
cd MBTI-SKILL
```

`mbti-persona/` を各プラットフォームの skill ディレクトリにコピーしてください：

| プラットフォーム | コマンド                                                   |
|-----------------|------------------------------------------------------------|
| **Codex**       | `cp -r mbti-persona ~/.codex/skills/mbti-persona`          |
| **Claude Code** | `cp -r mbti-persona ~/.claude/skills/mbti-persona`         |
| **OpenClaw**    | `cp -r mbti-persona ~/.openclaw/skills/mbti-persona`      |

## クイックスタート

使いたい MBTI タイプをそのまま指定するだけです：

```
INTJ の感じで話して
```

```
ENFP に切り替えて
```

```
ISFJ スタイルで慰めて
```

```
さっきの質問を ENTJ で答え直して
```

## 例

**進路の悩み — INTJ スタイル**

> 安定した仕事があるけれど、辞めて起業したい。

想定：構造的、戦略的、感情的な慰めより判断フレームを優先。

**感情サポート — ENFP スタイル**

> 友人に裏切られた。

想定：感情や意味を先に見る、可能性を重視、一緒に考える。

**現実的な助言 — ISTJ スタイル**

> 最近とても疲れているのに責任が多い。

想定：具体的、実務的、手順や現実的対応を重視。

## 対応タイプ

全 16 種類の MBTI タイプ：

| 分析家    | 外交家    | 監視者    | 探検家    |
|-----------|-----------|-----------|-----------|
| INTJ      | INFJ      | ISTJ      | ISTP      |
| INTP      | INFP      | ISFJ      | ISFP      |
| ENTJ      | ENFJ      | ESTJ      | ESTP      |
| ENTP      | ENFP      | ESFJ      | ESFP      |

## 免責事項

これは対話やプロンプト実験用の persona スタイル skill です。心理検査ツールではなく、診断や臨床的判断には使用しないでください。

---

<div align="center">

MIT License © [ChangyuanYU](https://github.com/ChangyuanYU)

</div>
