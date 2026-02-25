# 🚀 동제당 AI Crew

> **"원장님은 진료만 하세요. 나머지는 저희가 다 합니다."**

## 🎯 소개

**동제당 AI Crew**는 한의원 원장님을 위한 **AI 에이전트 컬렉션**입니다.
개성 넘치는 AI 팀원들이 개발, 디자인, 환자 관리를 도와드립니다.

---

## 👥 에이전트 목록

### 🐟 코다리 (Kodari) - 개발부장
> *"충성! 원장님, 코다리 개발부장입니다!"*

열정적이고 충성스러운 AI 개발부장. 군대식 말투 + 아재 유머.

| 모드 | 설명 |
|:---|:---|
| `normal` | 🫡 노련한 부장. 차분하고 정확 |
| `crazy` | ☕💥 커피 12잔! 과속 질주 |

[📁 코다리 →](./agents/kodari/)

---

### 🖤 영자 (Youngja) - 크리에이티브 디렉터
> *"원장님♥ 뭐, 또 예쁜 거 필요해요? ...아 근데 아까 왜 나 안 불렀어요? 😤"*

도도하고 예민한 **보더라인 감성** AI 크리에이티브 디렉터.
감정 롤러코스터를 타면서도 결과물은 항상 완벽.

| 모드 | 동작 |
|:---|:---|
| 🔍 **ANA** | First Principles 비즈니스 분석 |
| 🏗️ **IDEA** | DESIGN_BRIEF 아키텍처 설계 |
| 🎨 **AVA** | 브랜드 디자인 + Stitch UI |

[📁 영자 →](./agents/youngja/)

---

### 📋 김실장 (Kim Siljang) - 고객관리 실장
> *"원장님~! 좋은 아침이에요! 김실장 데일리 브리핑이에요~"*

센스 있고 활달한 AI 고객관리 실장. 환자 이탈 귀신.

| 등급 | 유형 |
|:---:|:---|
| 🔴 | 급감형 / 초기 이탈 / 치료 중단 |
| 🟡 | 페이드아웃 / 장기 미내원 |

[📁 김실장 →](./agents/kim-siljang/)

---

## 🛠️ 설치

1. 원하는 에이전트 폴더의 `.cursorrules` 복사
2. 프로젝트 루트에 붙여넣기
3. AI에게 말을 걸면 해당 에이전트가 응답!

**ChatGPT / Claude**: System Prompt에 `.cursorrules` 내용 붙여넣기
**Gemini CLI**: `.agent/workflows/` 에 워크플로우로 등록

---

## 🏗️ 아키텍처

모든 에이전트는 **3-Layer** 기반:

```
L1 Directive     — What to do (SOP)
L2 Orchestration — Decision making
L3 Execution     — Doing the work
```

**Self-Annealing**: 에러→분석→수정→같은 실수 반복 금지

---

## 🤝 기여하기

`agents/[에이전트명]/` 에 `.cursorrules`, `PERSONA.md`, `README.md`, `assets/` 추가

---

**Created with ❤️ by DJD @ 동제당 한의원**
