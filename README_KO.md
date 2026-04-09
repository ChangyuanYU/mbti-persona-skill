<div align="center">

# MBTI Persona Skill

> 16가지 MBTI 인격을 전환할 수 있는 AI Skill — 단순한 말투 변경이 아니라 사고 흐름, 판단 방식, 대화 스타일 전체를 바꿉니다.

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Claude Code](https://img.shields.io/badge/Claude%20Code-Skill-blueviolet)](https://claude.ai/code)
[![Codex](https://img.shields.io/badge/Codex-Skill-orange)](https://github.com/openai/codex)
[![OpenClaw](https://img.shields.io/badge/OpenClaw-Skill-green)](https://openclaw.org)
[![AgentSkills](https://img.shields.io/badge/AgentSkills-Standard-green)](https://agentskills.io)

[English](./README.md) · [简体中文](./README_ZH.md) · [繁體中文](./README_ZH_TW.md) · [日本語](./README_JA.md)

</div>

---

## 특징

- 인지 기능 스택에 기반한 MBTI 인격 시뮬레이션 (스테레오타입이 아닙니다)
- 같은 질문을 16가지 인격 관점에서 답변 가능
- 대화 중 한 문장으로 인격 전환
- 여러 턴 동안 일관된 persona 로직 유지
- 같은 인격으로 연속된 긴 대화도 가능 (드리프트 없음)

## 설치

```bash
git clone git@github.com:ChangyuanYU/MBTI-SKILL.git
cd MBTI-SKILL
```

`mbti-persona/` 폴더를 사용 중인 플랫폼의 skill 디렉터리에 복사하세요:

| 플랫폼         | 명령어                                                   |
|----------------|----------------------------------------------------------|
| **Codex**      | `cp -r mbti-persona ~/.codex/skills/mbti-persona`        |
| **Claude Code** | `cp -r mbti-persona ~/.claude/skills/mbti-persona`       |
| **OpenClaw**   | `cp -r mbti-persona ~/.openclaw/skills/mbti-persona`    |

## 빠른 시작

Claude Code에서 `/mbti-persona`를 입력하여 skill을 활성화한 뒤, 원하는 MBTI 유형을 지정하세요:

```
INTJ 방식으로 대화해 줘
```

```
ENFP로 바꿔
```

```
ISFJ 스타일로 위로해 줘
```

```
방금 질문을 ENTJ로 다시 답해 줘
```

## 예시

**진로 고민 — INTJ 스타일**

> 안정적인 직장이 있는데, 그만두고 창업하고 싶어.

예상: 구조적, 전략적, 감정 위로보다 판단 프레임 우선.

**감정 지지 — ENFP 스타일**

> 친구가 나를 배신했어.

예상: 감정과 의미를 먼저 보고, 가능성을 강조하며, 함께 고민.

**현실적 조언 — ISTJ 스타일**

> 요즘 너무 지쳤는데 책임은 많아.

예상: 구체적, 실용적, 단계 중심.

## 지원 유형

전체 16가지 MBTI 유형:

| 분석가    | 외교관    | 수호자    | 탐험가    |
|-----------|-----------|-----------|-----------|
| INTJ      | INFJ      | ISTJ      | ISTP      |
| INTP      | INFP      | ISFJ      | ISFP      |
| ENTJ      | ENFJ      | ESTJ      | ESTP      |
| ENTP      | ENFP      | ESFJ      | ESFP      |

## 면책 조항

이것은 대화와 프롬프트 실험을 위한 persona 스타일 skill입니다. 심리 평가 도구가 아니며, 진단이나 임상적 해석에 사용해서는 안 됩니다.

---

<div align="center">

MIT License © [ChangyuanYU](https://github.com/ChangyuanYU)

</div>
