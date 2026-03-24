# Safety Violation — Key Issue Analysis Report (March 2026)

**Project:** SDN Module Expansion PJT
**Analysis Period:** March 2026 (01.03.2026 – 21.03.2026)
**Method:** KeyBERT (paraphrase-multilingual-MiniLM-L12-v2)
**Total Records Analyzed:** 144건
**Report Date:** 2026-03-24

---

## 1. Executive Summary

2026년 3월 한 달간 기록된 안전 위반 144건을 KeyBERT 텍스트 분석한 결과,
**추락·고소작업** 이슈가 전체의 47.2%로 1위를 차지했으며,
**인양·리깅** 이슈가 36.8%로 뒤를 이었다.
**정리정돈·통행로** 위반(30.6%)도 지속적으로 반복되고 있다.

미조치(Uncompleted) 건수는 전체 144건 중 **99건(68.8%)** 으로, 조치 이행률이 낮아 현장 안전 관리 강화가 시급하다.
전월(Feb 2026, 30건) 대비 **4.8배 급증** — 현장 작업량 증가에 따른 체계적 안전 관리 필요.

---

## 2. Data Overview

| 항목 | 내용 |
|------|------|
| 분석 기간 | 06.03.2026 – 21.03.2026 |
| 총 건수 | 144건 |
| 조치 완료 | 45건 (31.3%) |
| 미조치 | 99건 (68.8%) |
| 주요 Vendor | Hankuk (68건), DSHI (67건), Daemyoung (7건) |
| 주요 Location | Module 1F (66건), Module 2F (53건), Module GF (25건) |
| 담당 Inspector | Rahul Mor, Surender Kumar |

---

## 3. Issue Ranking

| Rank | Issue Category | Count | % | Severity |
|------|---------------|------:|---:|----------|
| 1 | Fall / Working at Height (추락·고소작업) | 68 | 47.2% | 🔴 Critical |
| 2 | Lifting / Rigging (인양·리깅) | 53 | 36.8% | 🔴 Critical |
| 3 | Housekeeping / Access Way (정리정돈·통행로) | 44 | 30.6% | 🟡 Medium |
| 4 | Other (기타·행정) | 26 | 18.1% | ⚪ Low |
| 5 | Equipment / Vehicle (장비·차량) | 20 | 13.9% | 🟠 High |
| 6 | Electrical / Fire (전기·화재) | 17 | 11.8% | 🔴 Critical |
| 7 | Structural / Collapse (구조·붕괴) | 15 | 10.4% | 🟠 High |
| 8 | Falling Object / Material (낙하물) | 8 | 5.6% | 🟠 High |
| 8 | PPE / Training (PPE·교육) | 8 | 5.6% | 🟡 Medium |
| 10 | Gas / Explosion (가스·폭발) | 6 | 4.2% | 🔴 Critical |

> 1건이 복수 카테고리에 해당될 수 있으므로 합계 > 100%

---

## 4. Top Issue Detail

### 🔴 Rank 1 — Fall / Working at Height (68건, 47.2%)

고소작업 중 추락 위험이 전체 이슈의 절반에 육박.
안전대 미체결, 개구부 미차단, 비계 불안전 작업, 좁은 빔 위 작업이 반복 패턴.
전월 대비 건수 대폭 증가 — 고소작업 현장 확대에 따른 관리 강화 필요.

**핵심 키워드:** `scaffolding` · `edge area height` · `unsafe opening` · `worker standing` · `unsafe manner` · `near edge area` · `snap hook` · `lifeline`

**대표 사례:**
- *"Worker was standing on height (14m) on narrow beam & anchor point (lifeline) is also far from him, risky condition"*
- *"Worker is moving at height without anchoring safety harness in lifeline, he holded the snap hooks of safety harness in his hands"*
- *"Many workers knotted their safety harness lanyards which significantly reduce the strength of fall protection equipment"*
- *"Scissor lift crossing over safety net — will decrease the strength & integrity of net"*

**미조치:** 42건 (61.8%)

---

### 🔴 Rank 2 — Lifting / Rigging (53건, 36.8%)

인양 작업 중 신호수 부재, 웹 슬링 라운드 미제거, 리프팅 구역 무단 진입이 주요 원인.
Rank 1과 동시 발생 케이스 다수 (고소 인양 복합 작업).
DSHI에서 집중 발생 (39건 — DSHI 전체의 58%).

**핵심 키워드:** `signalman` · `rounds web sling` · `removed start lifting` · `lifting area` · `deck sheet area` · `unauthorized entry` · `underneath` · `barricade`

**대표 사례:**
- *"No signalman during lifting operation; workers observed entering lifting zone"*
- *"The rounds from web sling were not removed before start lifting"*
- *"During lifting process some workers were observed in the lifting area and materials can fall"*
- *"Deck sheet area below was not barricaded during lifting — unauthorized persons present"*

**미조치:** 40건 (75.5%)

---

### 🟡 Rank 3 — Housekeeping / Access Way (44건, 30.6%)

자재 산재 및 통행로 미확보로 인한 낙상·충돌 유발.
지속 반복되는 기본 생활안전 위반 — 현장 규율 강화 필요.
Module 1F와 Module 2F 양측에서 고르게 발생.

**핵심 키워드:** `materials scattered haphazard` · `access way` · `uneven staking` · `scattered` · `poor housekeeping` · `trip hazard` · `storage`

**대표 사례:**
- *"Materials from near access way needs to be clear, all area lacks proper safe access, materials scattered in haphazard manner"*
- *"Poor housekeeping of materials and storage boxes, lack of designated storage areas"*
- *"Uneven staking of scaffold pipes; area was not barricaded"*
- *"Tools boxes without material information sheet & materials not removed; wheels not locked before shifting"*

**미조치:** 35건 (79.5%)

---

### 🟠 Rank 5 — Equipment / Vehicle (20건, 13.9%)

지게차·크레인·Scissor Lift 운용 중 작업자 충돌 위험.
Tip-over 위험, 바리케이드 미설치, 무단 접근 통제 실패 반복.

**핵심 키워드:** `scissor lift` · `tip over` · `center of gravity` · `lift body unsafe` · `high risky position` · `boom`

**대표 사례:**
- *"100% height of scissor lift was used/opened — center of gravity moves higher, tip over hazard"*
- *"Loose middle platform was used to stand over in the scissor lift on extension platform"*
- *"JCB / forklift operating without proper barrier"*

**미조치:** 20건 (100%) — 전건 미조치

---

### 🔴 Rank 6 — Electrical / Fire (17건, 11.8%)

전기 접지 미비 및 소화 시설·PDB 접근 차단이 주요 패턴.
빈도는 낮으나 중대재해 직결 위험으로 우선 처리 필요.
Module GF에서 집중 발생 (10건 — GF 전체의 40%).

**핵심 키워드:** `earthing` · `core drill` · `hydrant access blocked` · `conduit pipes` · `fire extinguisher` · `PDB`

**대표 사례:**
- *"Stand core drill machine — no body earthing connection has been given"*
- *"PVC conduit pipes installed which are not allowed; no installation of roof modular fire extinguisher"*
- *"Fire hydrant access is blocked; materials scattered nearby"*

**미조치:** 14건 (82.4%)

---

### 🟠 Rank 7 — Structural / Collapse (15건, 10.4%)

전월 대비 신규 급증 카테고리. 좁은 빔 위 작업, 지지 없는 빔 배치, 날카로운 철근 노출이 주요 원인.
중대재해(빔 낙하·작업자 충돌)로 직결될 수 있는 고위험 패턴.

**핵심 키워드:** `narrow beam` · `single narrow beam` · `sharp edges rebars` · `beams without support` · `face eye injury` · `entrapment`

**대표 사례:**
- *"Worker was standing on height (14m) on single narrow beam — high chances of fall"*
- *"Multiple beams were without side support; risky & unsafe position for beams placement; chances of fall of beams on nearby workers"*
- *"Sharp edges of rebars in access way — face/eye injury risk"*

**미조치:** 8건 (53.3%)

---

### 🔴 Rank 10 — Gas / Explosion (6건, 4.2%)

빈도는 낮지만 가스 실린더 취급 불량은 즉각 조치 필요 사안.
단일 체인 인양, 미고정 보관, 1인 단독 취급 등 복합 위험 요소 존재.
Module GF에서 집중 발생 (4건).

**핵심 키워드:** `high pressure gas cylinders` · `filled oxygen cylinders` · `single chain` · `cylinder storage` · `gas cylinder`

**대표 사례:**
- *"Two filled oxygen cylinders found with single chain going to lift — high chances of imbalance"*
- *"High pressure gas cylinders in material shifting box without tighten properly"*
- *"Unsafe handling of gas cylinder by single worker"*

---

## 5. Location-wise Breakdown

| Category | Module 1F | Module 2F | Module GF |
|----------|----------:|----------:|----------:|
| Fall / Working at Height | 28 | 38 | 11 |
| Lifting / Rigging | 27 | 15 | 11 |
| Housekeeping / Access Way | 22 | 14 | 8 |
| Equipment / Vehicle | 12 | 6 | 2 |
| Electrical / Fire | 4 | 3 | 10 |
| Structural / Collapse | 5 | 6 | 4 |
| Gas / Explosion | 1 | 1 | 4 |
| **합계** | **66** | **53** | **25** |

**주요 특이사항:**
- **Module 2F** — 추락 이슈 가장 집중 (38건 / 전체 추락의 56%)
- **Module 1F** — 추락·인양 복합 발생 다수, 장비 사고 집중
- **Module GF** — 전기·화재 이슈 집중 (10건 / GF 전체의 40%), 가스 취급 이슈도 집중

---

## 6. Vendor-wise Breakdown

| Vendor | 총 건수 | 주요 이슈 Top 3 |
|--------|-------:|----------------|
| **Hankuk** | 68 | 추락(32) · 정리정돈(24) · 인양(14) |
| **DSHI** | 67 | 추락(36) · 인양(39) · 장비(17) |
| **Daemyoung** | 7 | 전기(4) · 기타(3) |
| Halim | 1 | 정리정돈(1) |
| Samho | 1 | 정리정돈(1) |

**주요 특이사항:**
- **DSHI** — 인양·리깅 이슈가 39건으로 집중 (전체 인양 이슈의 73.6%)
- **Hankuk** — 추락·정리정돈 이슈 비중 높음 (Module 2F 작업 집중)
- **Daemyoung** — 전기 이슈 4건 모두 미조치 (Module GF 집중)

---

## 7. Completion Status Analysis

| 구분 | 건수 | 비율 |
|------|-----:|-----:|
| 조치 완료 (Yes) | 45 | 31.3% |
| 미조치 (No) | 99 | 68.8% |

**미조치 카테고리별:**

| Category | 미조치 건수 | 미조치율 |
|----------|----------:|--------:|
| Fall / Working at Height | 42 | 61.8% |
| Lifting / Rigging | 40 | 75.5% |
| Housekeeping / Access Way | 35 | 79.5% |
| Equipment / Vehicle | 20 | **100%** |
| Electrical / Fire | 14 | 82.4% |
| Structural / Collapse | 8 | 53.3% |
| PPE / Training | 6 | 75.0% |
| Falling Object / Material | 6 | 75.0% |
| Gas / Explosion | 3 | 50.0% |

> **Equipment / Vehicle 100% 미조치** — 즉각 조치 필요

---

## 8. Key Findings & Recommendations

| # | 발견 사항 | 권고 조치 |
|---|---------|---------|
| 1 | 추락·인양 이슈가 전체의 **84%** (중복 포함) 차지 | 고소·인양 작업 전 TBM 강화, 안전대 체결 2인 확인 의무화 |
| 2 | 신호수(Signalman) 관련 위반 **반복** — DSHI 집중 | 인양 작업 시 신호수 배치 확인 후 작업 시작 규정 강화 |
| 3 | **미조치율 68.8%** — 3월 급증 후 후속 조치 부진 | 일일 미조치 현황 공유 및 조치 기한 준수 강제화 |
| 4 | 장비·차량 이슈 **100% 미조치** | Scissor Lift / JCB 작업 전 안전 점검표 제출 의무화 |
| 5 | Module GF — 전기·가스 복합 위험 집중 | GF 구역 전기·가스 작업 별도 Permit-to-Work 시행 |
| 6 | **Structural / Collapse 신규 급증** (전월 0 → 15건) | 무지지 빔 작업·좁은 빔 위 작업 즉시 중단 및 안전 계획 수립 |
| 7 | 3월 건수 급증 (30 → 144건, **4.8배**) | 현장 활동량 증가에 비례한 안전 인력 및 점검 빈도 확충 검토 |

---

## 9. Monthly Trend (누적)

| Month | Records | 누적 |
|-------|--------:|-----:|
| Dec 2025 | 11건 | 11건 |
| Feb 2026 | 30건 | 41건 |
| Mar 2026 | 144건 | 185건 |

> Mar 2026 데이터가 전체 누적의 77.8% 차지 — 현장 활동 급증 및 점검 강화 반영

---

## 10. Analysis Notes

- **분석 도구:** KeyBERT (sentence-transformers 기반 키워드 추출)
- **임베딩 모델:** `paraphrase-multilingual-MiniLM-L12-v2` (384-dim)
- **데이터 소스:** `data_mar2026.csv` (144건)
- **분류 방식:** 추출 키워드와 테마별 키워드 사전(domain keyword matching) 조합
- 1건이 복수 이슈에 해당될 수 있어 카테고리별 합계 > 전체 건수
- KeyBERT keyphrase_ngram_range: (1,3), top_n=7, MMR diversity=0.5
