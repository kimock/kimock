# Safety Violation — Key Issue Analysis Report (March 2026)

**Project:** SDN Module Expansion PJT
**Analysis Period:** March 2026 (01.03.2026 – 28.03.2026)
**Method:** KeyBERT (paraphrase-multilingual-MiniLM-L12-v2)
**Total Records Analyzed:** 198건
**Report Date:** 2026-03-31

---

## 1. Executive Summary

2026년 3월 28일까지 기록된 안전 위반 198건을 KeyBERT 텍스트 분석한 결과,
**추락·고소작업** 이슈가 전체의 48.7%로 1위를 유지했으며,
**정리정돈·통행로** 위반(38.1%)이 Rank 2로 상승하고
**인양·리깅** 이슈(31.5%)는 Rank 3으로 하락했다.
**구조·붕괴(Structural/Collapse)** 이슈가 전월 대비 2배 이상 증가(17 → 35건)하며 Rank 4로 급부상했다.

미조치(Uncompleted) 건수는 전체 198건 중 **129건(65.2%)** 으로, 전체 조치 이행률은 34.8%에 그치고 있다.
전월(Feb 2026, 30건) 대비 **6.6배 급증** — 현장 작업량 증가에 따른 체계적 안전 관리 강화 시급.

**W7 (25–28.03) 특이사항:** Hankuk 20건(64.5%) 집중 — props/jacks 불량, diagonal bracing 균열, 개구부 미차단 등 구조·붕괴·추락 복합 이슈 급증. Hankuk 총 건수 97건으로 DSHI(91건)를 재역전.

---

## 2. Data Overview

| 항목 | 내용 |
|------|------|
| 분석 기간 | 06.03.2026 – 28.03.2026 |
| 총 건수 | 198건 |
| 조치 완료 | 69건 (34.8%) |
| 미조치 | 129건 (65.2%) |
| 주요 Vendor | Hankuk (97건), DSHI (91건), Daemyoung (8건) |
| 주요 Location | Module 1F (84건), Module 2F (82건), Module GF (32건) |
| 담당 Inspector | Rahul Mor, Surender Kumar |

> **Vendor 순위 재역전:** W7(25–28.03)에서 Hankuk 20건 집중 발생 → Hankuk(97건)이 DSHI(91건)을 재역전하여 1위. W5(23.03) 당시 DSHI 집중 점검으로 DSHI가 일시 앞섰으나 W6·W7 이후 Hankuk 재역전.

---

## 3. Issue Ranking

| Rank | Issue Category | Count | % | Severity |
|------|---------------|------:|---:|----------|
| 1 | Fall / Working at Height (추락·고소작업) | 96 | 48.7% | 🔴 Critical |
| 2 | Housekeeping / Access Way (정리정돈·통행로) | 75 | 38.1% | 🟡 Medium |
| 3 | Lifting / Rigging (인양·리깅) | 62 | 31.5% | 🔴 Critical |
| 4 | Structural / Collapse (구조·붕괴) | 35 | 17.8% | 🟠 High |
| 5 | Equipment / Vehicle (장비·차량) | 25 | 12.7% | 🟠 High |
| 6 | Electrical / Fire (전기·화재) | 18 | 9.1% | 🔴 Critical |
| 7 | Other (기타·행정) | 14 | 7.1% | ⚪ Low |
| 8 | Falling Object / Material (낙하물) | 11 | 5.6% | 🟠 High |
| 9 | PPE / Training (PPE·교육) | 10 | 5.1% | 🟡 Medium |
| 10 | Gas / Explosion (가스·폭발) | 8 | 4.1% | 🔴 Critical |

> 1건이 복수 카테고리에 해당될 수 있으므로 합계 > 100%
>
> **순위 변동 (vs. 153건 기준):** Housekeeping↑ Rank3→2 / Lifting↓ Rank2→3 / Structural↑ Rank7→4 (17→35건)

---

## 4. Top Issue Detail

### 🔴 Rank 1 — Fall / Working at Height (96건, 48.7%)

고소작업 중 추락 위험이 전체 이슈의 절반에 육박하며 W7에서 19건 추가 발생.
W7 신규 패턴: 안전대 앵커 불량, 개구부 미차단, 리바 위 작업, 비계 불안전 개구부 등 반복.
안전대 미체결·개구부 미차단·비계 불안전 작업이 지속적 반복 패턴.

**핵심 키워드:** `scaffolding` · `edge area height` · `unsafe opening` · `worker standing` · `unsafe manner` · `near edge area` · `snap hook` · `lifeline` · `anchor bolt` · `fall arrestor` · `unsafe access way` · `rebar walking`

**대표 사례:**
- *"Worker was standing on height (14m) on narrow beam & anchor point (lifeline) is also far from him, risky condition"*
- *"Worker is moving at height without anchoring safety harness in lifeline, he holded the snap hooks of safety harness in his hands"*
- *"Many workers knotted their safety harness lanyards which significantly reduce the strength of fall protection equipment"*
- *"Unsafe access way to the working point"* *(W7 신규)*
- *"Worker walking/standing on the rebars without fall protection at height"* *(W7 신규)*
- *"Safety harness lanyards knotted at height which is not safe"* *(W7 신규)*
- *"Near edge area at height worker was sitting without anchoring of safety harness"* *(W7 신규)*

**미조치:** 56건 (58.3%)

---

### 🟡 Rank 2 — Housekeeping / Access Way (75건, 38.1%)

W7에서 12건 추가 발생하며 Lifting/Rigging을 제치고 Rank 2로 상승.
자재 산재 및 통행로 미확보로 인한 낙상·충돌 유발 — 전월 대비 지속 증가.
W7 신규 패턴: safety net 위 낙하물 미제거, 산재된 loose materials, rebars near access way.

**핵심 키워드:** `materials scattered haphazard` · `access way` · `uneven staking` · `scattered` · `poor housekeeping` · `trip hazard` · `storage` · `loose materials` · `safety net material`

**대표 사례:**
- *"Materials from near access way needs to be clear, all area lacks proper safe access, materials scattered in haphazard manner"*
- *"Poor housekeeping of materials and storage boxes, lack of designated storage areas"*
- *"Loose materials scattered in haphazard manner at scaffolding near opening area"* *(W7 신규)*
- *"Materials from safety net need to be removed"* *(W7 신규)*
- *"Materials/rebars placing in access way"* *(W7 신규)*

**미조치:** 55건 (73.3%)

---

### 🔴 Rank 3 — Lifting / Rigging (62건, 31.5%)

W7에서 10건 추가 발생. 신호수 부재, 리프팅 구역 무단 진입이 주요 원인.
W7 신규: 크레인 신호수 미배치 반복, 인양 구역 무단 접근, line of fire 노출.

**핵심 키워드:** `signalman` · `rounds web sling` · `lifting area` · `unauthorized entry` · `underneath` · `boom lift` · `tag line` · `line of fire` · `banks man` · `lifting box`

**대표 사례:**
- *"No signalman during lifting operation; workers observed entering lifting zone"*
- *"The rounds from web sling were not removed before start lifting"*
- *"Repeated safety violation — No signalman for Lifting area, unauthorized worker giving signal"* *(W7 신규)*
- *"During rebars shifting person were standing in line of fire"* *(W7 신규)*
- *"Signalman was giving signal to crane operator standing just near the material inside the barricade"* *(W7 신규)*

**미조치:** 42건 (67.7%)

---

### 🟠 Rank 4 — Structural / Collapse (35건, 17.8%) ← **급상승**

W7에서 11건 추가 발생 — 전체 35건 중 31.4%가 W7에 집중.
Props/jacks 불량 고정, diagonal bracing 균열, 불안전 stacking이 W7 신규 주요 패턴.
중대재해(빔 낙하·구조물 붕괴)로 직결될 수 있는 고위험 패턴.

**핵심 키워드:** `collapse` · `narrow beam` · `sharp edges rebars` · `beams without support` · `props jacks` · `diagonal bracing` · `cracking` · `unstable` · `single wooden` · `heavy steel` · `scaffold pipe stacking`

**대표 사례:**
- *"Worker was standing on height (14m) on single narrow beam"*
- *"Multiple beams were without side support — chances of fall of beams on nearby workers"*
- *"Props/jacks placed on single wooden piece & tightened with wire instead of standard clamping"* *(W7 신규)*
- *"Diagonal bracing started cracking at the bottom — potential for sudden component failure"* *(W7 신규)*
- *"Heavy steel beam resting on a narrow, unstable stack of slippers with no load distribution"* *(W7 신규)*
- *"Due to irregular & unsafe stacking of scaffold pipes, during shifting, pipes displaced from forklift"* *(W7 신규)*

**미조치:** 19건 (54.3%)

---

### 🟠 Rank 5 — Equipment / Vehicle (25건, 12.7%)

지게차·크레인·Scissor Lift·Boom Lift 운용 중 작업자 충돌 위험.
W7 신규: boom lift 이동 구역 미차단, 불안전 발판.

**핵심 키워드:** `scissor lift` · `tip over` · `center of gravity` · `boom lift` · `cordoned off` · `forklift`

**대표 사례:**
- *"100% height of scissor lift was used/opened — center of gravity moves higher, tip over hazard"*
- *"During boom lift movement area was not cordoned off"* *(W7 신규)*
- *"No signalman for this scissor lift"* *(W7 신규)*

**미조치:** 23건 (92.0%)

---

### 🔴 Rank 6 — Electrical / Fire (18건, 9.1%)

전기 접지 미비 및 소화 시설·PDB 접근 차단이 주요 패턴. 빈도는 낮으나 중대재해 직결 위험.
W6(24.03)에서 3건 추가 — 일일 최다 전기 발생일.

**핵심 키워드:** `earthing` · `core drill` · `hydrant access blocked` · `conduit pipes` · `fire extinguisher` · `PDB` · `welding` · `electric shock`

**미조치:** 13건 (72.2%)

---

### 🔴 Rank 10 — Gas / Explosion (8건, 4.1%)

W6(24.03)에서 2건 추가 발생. 가스 실린더 취급 불량은 즉각 조치 필요.
Module GF에서 5건 집중 (전체의 62.5%).

**핵심 키워드:** `high pressure gas cylinders` · `filled oxygen cylinders` · `single chain` · `cylinder storage`

**미조치:** 5건 (62.5%)

---

## 5. Location-wise Breakdown

| Category | Module 1F | Module 2F | Module GF |
|----------|----------:|----------:|----------:|
| Fall / Working at Height | 31 | 63 | 2 |
| Lifting / Rigging | 31 | 18 | 13 |
| Housekeeping / Access Way | 34 | 30 | 11 |
| Equipment / Vehicle | 18 | 6 | 1 |
| Electrical / Fire | 5 | 3 | 10 |
| Structural / Collapse | 18 | 15 | 2 |
| Gas / Explosion | 3 | 0 | 5 |
| **합계** | **84** | **82** | **32** |

**주요 특이사항:**
- **Module 2F** — 추락 이슈 압도적 집중 (63건 / 전체 추락의 65.6%); W7에서 18건 추가로 1F와 격차 확대
- **Module 1F** — 추락·인양·정리정돈 균형 발생; W7 장비·구조 이슈 집중
- **Module GF** — 전기·화재 이슈 집중 (10건 / GF 전체의 31.3%), 가스 취급 이슈도 집중; W7 이후 발생 급감

---

## 6. Vendor-wise Breakdown

| Vendor | 총 건수 | 주요 이슈 Top 3 |
|--------|-------:|----------------|
| **Hankuk** | 97 | 추락(52) · 정리정돈(47) · 구조붕괴(21) |
| **DSHI** | 91 | 추락(44) · 인양(41) · 정리정돈(24) |
| **Daemyoung** | 8 | 전기(4) · 기타(3) · 정리정돈(2) |
| Halim | 1 | 정리정돈(1) |
| Samho | 1 | 정리정돈(1) |

**주요 특이사항:**
- **Hankuk** — W7(25–28.03)에서 20건 집중 발생, 총 97건으로 DSHI 재역전; 구조붕괴 이슈(21건)의 대부분이 W7 신규
- **DSHI** — W5(23.03) 집중 점검 이후 W6·W7에서 추가 15건; 인양·추락 이슈 여전히 지배적
- **Daemyoung** — 전기 이슈 4건 모두 미조치 (Module GF 집중)

---

## 7. Completion Status Analysis

| 구분 | 건수 | 비율 |
|------|-----:|-----:|
| 조치 완료 (Yes) | 69 | 34.8% |
| 미조치 (No) | 129 | 65.2% |

**미조치 카테고리별:**

| Category | 미조치 건수 | 미조치율 |
|----------|----------:|--------:|
| Fall / Working at Height | 56 | 58.3% |
| Housekeeping / Access Way | 55 | 73.3% |
| Lifting / Rigging | 42 | 67.7% |
| Structural / Collapse | 19 | 54.3% |
| Equipment / Vehicle | 23 | **92.0%** |
| Electrical / Fire | 13 | 72.2% |
| PPE / Training | 8 | 80.0% |
| Falling Object / Material | 9 | 81.8% |
| Gas / Explosion | 5 | 62.5% |
| Other | 11 | 78.6% |

> **Equipment / Vehicle 미조치율 92.0%** — 25건 중 23건 미조치; 장비 안전 조치 이행 체계 재점검 시급

---

## 8. Key Findings & Recommendations

| # | 발견 사항 | 권고 조치 |
|---|---------|---------|
| 1 | 추락·인양 이슈가 전체의 **80.2%** (중복 포함) 차지 | 고소·인양 작업 전 TBM 강화, 안전대 체결 2인 확인 의무화 |
| 2 | **Structural/Collapse 35건** — W7에서 11건 급증, props·bracing·stacking 복합 결함 | 구조물 지지 상태 일일 점검 의무화, 불안전 props·jacks 즉시 교체 |
| 3 | **미조치율 65.2%** — 129건 미해결 지속 | 일일 미조치 현황 공유 및 조치 기한 준수 강제화 |
| 4 | 장비·차량 이슈 **92.0% 미조치** | Scissor Lift / JCB / Boom Lift 작업 전 안전 점검표 제출 의무화 |
| 5 | **Hankuk W7 20건 집중** — 구조붕괴·추락·정리정돈 복합 발생 | Hankuk 담당 구역 W8 집중 점검 실시 및 TBM 강화 |
| 6 | Module GF — 전기·가스 복합 위험 집중 | GF 구역 전기·가스 작업 별도 Permit-to-Work 시행 |
| 7 | 신호수(Signalman) 관련 위반 **반복 지속** (W7에서도 재발) | 인양 작업 시 신호수 배치 확인 후 작업 시작 규정 강화 |
| 8 | 3월 건수 급증 (30 → 198건, **6.6배**) | 현장 활동량 증가에 비례한 안전 인력 및 점검 빈도 확충 |

---

## 9. Weekly Trend (3월 주차별 추세)

### 9-1. 주차별 건수 및 미조치율

| 주차 | 기간 | 총 건수 | 조치완료 | 미조치 | 미조치율 |
|------|------|--------:|---------:|-------:|--------:|
| W2 | 03.06 – 03.07 | 16건 | 10건 | 6건 | 37.5% |
| W3 | 03.09 – 03.14 | 56건 | 19건 | 37건 | 66.1% |
| W4 | 03.16 – 03.21 | 72건 | 16건 | 56건 | 77.8% |
| W5 | 03.23 | 9건 | 4건 | 5건 | 55.6% |
| W6 | 03.24 | 14건 | 4건 | 10건 | 71.4% |
| W7 | 03.25 – 03.28 | 31건 | 16건 | 15건 | 48.4% |
| **합계** | | **198건** | **69건** | **129건** | **65.2%** |

> W7(25–28.03) 미조치율 48.4% — W4(77.8%) 대비 29.4%p 개선, 당일·익일 조치 활발
> W6(24.03) 미조치율 71.4% — W5 대비 악화, 단일 날짜 점검 건수 대비 조치 이행 부진

---

### 9-2. 주차별 카테고리 분포

| Category | W2 (16) | W3 (56) | W4 (72) | W5 (9) | W6 (14) | W7 (31) | 추세 |
|----------|--------:|--------:|--------:|-------:|--------:|--------:|------|
| Fall / Working at Height | 15 | 20 | 31 | 6 | 5 | 19 | ↑ W7 재급증 |
| Housekeeping / Access Way | 2 | 24 | 29 | 1 | 7 | 12 | ↑ W6·W7 지속 |
| Lifting / Rigging | 4 | 16 | 24 | 3 | 5 | 10 | ↑ W7 지속 |
| Structural / Collapse | 4 | 5 | 9 | 3 | 3 | 11 | ↑ W7 급증 |
| Equipment / Vehicle | 3 | 6 | 10 | 1 | 2 | 3 | → W5 이후 소강 |
| Electrical / Fire | 0 | 8 | 5 | 1 | 3 | 1 | → W6 재발 후 소강 |
| PPE / Training | 1 | 0 | 7 | 0 | 0 | 2 | → W4 급증 후 소강 |
| Falling Object / Material | 3 | 1 | 3 | 2 | 0 | 2 | → 전 주차 산발 |
| Gas / Explosion | 1 | 1 | 4 | 0 | 2 | 0 | → W6 재발 후 소강 |
| Other | 0 | 7 | 7 | 0 | 0 | 0 | ↓ W6 이후 미발생 |

---

### 9-3. 주차별 Vendor 분포

| Vendor | W2 | W3 | W4 | W5 | W6 | W7 |
|--------|---:|---:|---:|---:|---:|---:|
| Hankuk | 9 | 25 | 34 | 0 | 8 | **20** |
| DSHI | 7 | 26 | 34 | **9** | 5 | 10 |
| Daemyoung | 0 | 3 | 4 | 0 | 1 | 0 |
| Halim | 0 | 1 | 0 | 0 | 0 | 0 |
| Samho | 0 | 1 | 0 | 0 | 0 | 0 |

> **W5 특이사항:** DSHI 9건 — 23.03 DSHI 구역 집중 점검 실시일
> **W7 특이사항:** Hankuk 20건(64.5%) — 구조붕괴·추락 복합 집중, Hankuk 총 건수 97건으로 DSHI 재역전

---

### 9-4. 주차별 Location 분포

| Location | W2 | W3 | W4 | W5 | W6 | W7 |
|----------|---:|---:|---:|---:|---:|---:|
| Module 1F | 7 | 31 | 28 | 2 | 5 | 11 |
| Module 2F | 8 | 12 | 33 | 6 | 5 | 18 |
| Module GF | 1 | 13 | 11 | 1 | 4 | 1 |

> - **Module 2F** — W7에서 18건 발생 (W7 전체의 58.1%), 추락 이슈 지속 지배적
> - **Module 1F** — W3에 집중 후 W7 11건으로 재증가; 장비·구조 이슈 집중
> - **Module GF** — W6(4건) 이후 W7 1건으로 급감; 전기·가스는 GF 중점 관리 필요

---

### 9-5. 주차별 주요 특이사항

**W2 (03.06–03.07, 16건)**
- 분석 기간 초반, 추락 이슈(15건)가 전체의 94%로 압도적
- 미조치율 37.5% — 6개 주차 중 가장 낮음 (초기 현장 대응 활발)

**W3 (03.09–03.14, 56건)**
- 전주 대비 **3.5배 급증** (16 → 56건)
- Housekeeping 위반 22건으로 폭증, 전기·화재 이슈 9건 신규 등장

**W4 (03.16–03.21, 72건)**
- 최다 건수 주차 (전체의 36.4%)
- **PPE / Training 7건** — W3(0건) 대비 신규 급증
- 미조치율 **77.8%** — 최고치 기록

**W5 (03.23, 9건)**
- 9건 전부 **DSHI** — DSHI 구역 집중 점검 실시일
- 미조치율 55.6%, **Module 2F 집중** (6건 / 66.7%)

**W6 (03.24, 14건)**
- Hankuk 8건 / DSHI 5건 / Daemyoung 1건으로 분산
- **전기·화재 3건** — W5 이후 재발, Module GF 집중
- 미조치율 71.4% — W5 대비 악화

**W7 (03.25–03.28, 31건)**
- Hankuk 20건 집중 (64.5%) — 구조붕괴(11건) 급증, 추락(19건) 재급증
- **Structural / Collapse 이슈 급증**: props/jacks 단일 목재 지지, diagonal bracing 균열, scaffold pipe 불안전 적재, 불안전 자재 배치
- 미조치율 48.4% — 가장 낮은 수준, 현장 즉시 조치 활발
- 신규 위반 패턴: worker walking on rebars at height, safety harness lanyards knotted, unsafe metal plate in access way

---

## 10. Monthly Trend (누적)

| Month | Records | 누적 |
|-------|--------:|-----:|
| Dec 2025 | 11건 | 11건 |
| Feb 2026 | 30건 | 41건 |
| Mar 2026 (to 28th) | 198건 | 239건 |

> Mar 2026 데이터가 전체 누적의 82.8% 차지 — 현장 활동 급증 및 점검 강화 반영

---

## 12. Analysis Notes

- **분석 도구:** KeyBERT (sentence-transformers 기반 키워드 추출)
- **임베딩 모델:** `paraphrase-multilingual-MiniLM-L12-v2` (384-dim)
- **데이터 소스:** `data_mar2026.csv` (198건, 06.03.2026 – 28.03.2026)
- **분류 방식:** 추출 키워드와 테마별 키워드 사전(domain keyword matching) 조합
- 1건이 복수 이슈에 해당될 수 있어 카테고리별 합계 > 전체 건수
- KeyBERT keyphrase_ngram_range: (1,3), top_n=7, MMR diversity=0.5
- **업데이트:** 2026-03-31 — W6(24.03, 14건) + W7(25–28.03, 31건) 추가 반영 (이전 버전: 153건 기준, 23.03까지)
