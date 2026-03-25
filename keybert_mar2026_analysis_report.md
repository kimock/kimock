# Safety Violation — Key Issue Analysis Report (March 2026)

**Project:** SDN Module Expansion PJT
**Analysis Period:** March 2026 (01.03.2026 – 23.03.2026)
**Method:** KeyBERT (paraphrase-multilingual-MiniLM-L12-v2)
**Total Records Analyzed:** 153건
**Report Date:** 2026-03-25

---

## 1. Executive Summary

2026년 3월 23일까지 기록된 안전 위반 153건을 KeyBERT 텍스트 분석한 결과,
**추락·고소작업** 이슈가 전체의 48.4%로 1위를 차지했으며,
**인양·리깅** 이슈가 36.6%로 뒤를 이었다.
**정리정돈·통행로** 위반(28.8%)도 지속적으로 반복되고 있다.

미조치(Uncompleted) 건수는 전체 153건 중 **104건(68.0%)** 으로, 조치 이행률이 낮아 현장 안전 관리 강화가 시급하다.
전월(Feb 2026, 30건) 대비 **5.1배 급증** — 현장 작업량 증가에 따른 체계적 안전 관리 필요.

**W5 (23.03) 특이사항:** 9건 전부 DSHI — 해당일 DSHI 구역 집중 점검 실시에 따른 결과로, 벤더별 위험도 비교 시 W5 수치는 별도 해석 필요.

---

## 2. Data Overview

| 항목 | 내용 |
|------|------|
| 분석 기간 | 06.03.2026 – 23.03.2026 |
| 총 건수 | 153건 |
| 조치 완료 | 49건 (32.0%) |
| 미조치 | 104건 (68.0%) |
| 주요 Vendor | DSHI (76건), Hankuk (68건), Daemyoung (7건) |
| 주요 Location | Module 1F (68건), Module 2F (59건), Module GF (26건) |
| 담당 Inspector | Rahul Mor, Surender Kumar |

> **Vendor 순위 변동:** W5(23.03)에서 DSHI 9건 추가 → DSHI(76건)가 Hankuk(68건)을 역전하여 1위. 단, W5는 DSHI 구역 집중 점검일로 순수 벤더 비교에는 주의 필요.

---

## 3. Issue Ranking

| Rank | Issue Category | Count | % | Severity |
|------|---------------|------:|---:|----------|
| 1 | Fall / Working at Height (추락·고소작업) | 74 | 48.4% | 🔴 Critical |
| 2 | Lifting / Rigging (인양·리깅) | 56 | 36.6% | 🔴 Critical |
| 3 | Housekeeping / Access Way (정리정돈·통행로) | 44 | 28.8% | 🟡 Medium |
| 4 | Other (기타·행정) | 26 | 17.0% | ⚪ Low |
| 5 | Equipment / Vehicle (장비·차량) | 21 | 13.7% | 🟠 High |
| 6 | Electrical / Fire (전기·화재) | 18 | 11.8% | 🔴 Critical |
| 7 | Structural / Collapse (구조·붕괴) | 17 | 11.1% | 🟠 High |
| 8 | PPE / Training (PPE·교육) | 8 | 5.2% | 🟡 Medium |
| 8 | Falling Object / Material (낙하물) | 8 | 5.2% | 🟠 High |
| 10 | Gas / Explosion (가스·폭발) | 6 | 3.9% | 🔴 Critical |

> 1건이 복수 카테고리에 해당될 수 있으므로 합계 > 100%

---

## 4. Top Issue Detail

### 🔴 Rank 1 — Fall / Working at Height (74건, 48.4%)

고소작업 중 추락 위험이 전체 이슈의 절반에 육박.
안전대 미체결, 개구부 미차단, 비계 불안전 작업, 좁은 빔 위 작업이 반복 패턴.
W5에서 6건 추가 발생(앵커볼트 불량·바리케이드 이완·추락방지대 불량 연결 등) — 고소작업 리스크 지속.

**핵심 키워드:** `scaffolding` · `edge area height` · `unsafe opening` · `worker standing` · `unsafe manner` · `near edge area` · `snap hook` · `lifeline` · `anchor bolt` · `fall arrestor`

**대표 사례:**
- *"Worker was standing on height (14m) on narrow beam & anchor point (lifeline) is also far from him, risky condition"*
- *"Worker is moving at height without anchoring safety harness in lifeline, he holded the snap hooks of safety harness in his hands"*
- *"Many workers knotted their safety harness lanyards which significantly reduce the strength of fall protection equipment"*
- *"Scissor lift crossing over safety net — will decrease the strength & integrity of net"*
- *"Barricading ropes are in loose condition at height near edge area"* *(W5 신규)*
- *"Retractable fall arrestor rope connected to sharp edge of rebar — repeated safety observation"* *(W5 신규)*
- *"Hand tools lanyard/rope not connected during work at height in risky condition"* *(W5 신규)*

**미조치:** 46건 (62.2%)

---

### 🔴 Rank 2 — Lifting / Rigging (56건, 36.6%)

인양 작업 중 신호수 부재, 웹 슬링 라운드 미제거, 리프팅 구역 무단 진입이 주요 원인.
Rank 1과 동시 발생 케이스 다수 (고소 인양 복합 작업).
DSHI에서 집중 발생 — W5 추가 3건으로 DSHI 인양 이슈 42건으로 Fall과 동률.

**핵심 키워드:** `signalman` · `rounds web sling` · `removed start lifting` · `lifting area` · `deck sheet area` · `unauthorized entry` · `underneath` · `barricade` · `boom lift` · `incomplete staircase`

**대표 사례:**
- *"No signalman during lifting operation; workers observed entering lifting zone"*
- *"The rounds from web sling were not removed before start lifting"*
- *"During lifting process some workers were observed in the lifting area and materials can fall"*
- *"Deck sheet area below was not barricaded during lifting — unauthorized persons present"*
- *"No signalman for the boom lift in working condition"* *(W5 신규)*
- *"Unauthorized person entry not banned in the incomplete staircase area — no signage/caution, no barricade"* *(W5 신규)*

**미조치:** 42건 (75.0%)

---

### 🟡 Rank 3 — Housekeeping / Access Way (44건, 28.8%)

자재 산재 및 통행로 미확보로 인한 낙상·충돌 유발.
지속 반복되는 기본 생활안전 위반 — 현장 규율 강화 필요.
Module 1F와 Module 2F 양측에서 고르게 발생. W5 추가 없음.

**핵심 키워드:** `materials scattered haphazard` · `access way` · `uneven staking` · `scattered` · `poor housekeeping` · `trip hazard` · `storage`

**대표 사례:**
- *"Materials from near access way needs to be clear, all area lacks proper safe access, materials scattered in haphazard manner"*
- *"Poor housekeeping of materials and storage boxes, lack of designated storage areas"*
- *"Uneven staking of scaffold pipes; area was not barricaded"*
- *"Tools boxes without material information sheet & materials not removed; wheels not locked before shifting"*

**미조치:** 35건 (79.5%)

---

### 🟠 Rank 5 — Equipment / Vehicle (21건, 13.7%)

지게차·크레인·Scissor Lift 운용 중 작업자 충돌 위험.
Tip-over 위험, 바리케이드 미설치, 무단 접근 통제 실패 반복.
W5에서 Boom Lift 신호수 미배치 1건 추가 — 단, **당일 조치 완료**(Yes)로 최초 미조치 탈피.

**핵심 키워드:** `scissor lift` · `tip over` · `center of gravity` · `lift body unsafe` · `high risky position` · `boom` · `boom lift`

**대표 사례:**
- *"100% height of scissor lift was used/opened — center of gravity moves higher, tip over hazard"*
- *"Loose middle platform was used to stand over in the scissor lift on extension platform"*
- *"JCB / forklift operating without proper barrier"*
- *"No signalman for the boom lift in working condition"* *(W5 신규, 당일 완료)*

**미조치:** 20건 (95.2%) — W5 이전 100% 미조치에서 개선

---

### 🔴 Rank 6 — Electrical / Fire (18건, 11.8%)

전기 접지 미비 및 소화 시설·PDB 접근 차단이 주요 패턴.
빈도는 낮으나 중대재해 직결 위험으로 우선 처리 필요.
Module GF에서 집중 발생. W5에서 Module 2F 용접 중 어싱 미연결 1건 추가(당일 완료).

**핵심 키워드:** `earthing` · `core drill` · `hydrant access blocked` · `conduit pipes` · `fire extinguisher` · `PDB` · `welding` · `electric shock`

**대표 사례:**
- *"Stand core drill machine — no body earthing connection has been given"*
- *"PVC conduit pipes installed which are not allowed; no installation of roof modular fire extinguisher"*
- *"Fire hydrant access is blocked; materials scattered nearby"*
- *"Earthing holder was not connected during welding work — risk of severe electric shock or electrocution"* *(W5 신규, 당일 완료)*

**미조치:** 14건 (77.8%)

---

### 🟠 Rank 7 — Structural / Collapse (17건, 11.1%)

좁은 빔 위 작업, 지지 없는 빔 배치, 날카로운 철근 노출이 주요 원인.
W5에서 2건 추가 — 추락방지대 날카로운 철근 연결, 불안전 위치 하부 작업.
중대재해(빔 낙하·작업자 충돌)로 직결될 수 있는 고위험 패턴.

**핵심 키워드:** `narrow beam` · `single narrow beam` · `sharp edges rebars` · `beams without support` · `face eye injury` · `entrapment` · `retractable fall arrestor` · `unsafe position`

**대표 사례:**
- *"Worker was standing on height (14m) on single narrow beam — high chances of fall"*
- *"Multiple beams were without side support; risky & unsafe position for beams placement; chances of fall of beams on nearby workers"*
- *"Sharp edges of rebars in access way — face/eye injury risk"*
- *"Retractable fall arrestor rope connected to sharp edge of rebar — risky condition"* *(W5 신규)*
- *"Korean person of DSHI standing in unsafe position by holding staircase structure — risky condition"* *(W5 신규)*

**미조치:** 9건 (52.9%)

---

### 🔴 Rank 10 — Gas / Explosion (6건, 3.9%)

빈도는 낮지만 가스 실린더 취급 불량은 즉각 조치 필요 사안.
단일 체인 인양, 미고정 보관, 1인 단독 취급 등 복합 위험 요소 존재.
Module GF에서 집중 발생 (4건). W5 추가 없음.

**핵심 키워드:** `high pressure gas cylinders` · `filled oxygen cylinders` · `single chain` · `cylinder storage` · `gas cylinder`

**대표 사례:**
- *"Two filled oxygen cylinders found with single chain going to lift — high chances of imbalance"*
- *"High pressure gas cylinders in material shifting box without tighten properly"*
- *"Unsafe handling of gas cylinder by single worker"*

---

## 5. Location-wise Breakdown

| Category | Module 1F | Module 2F | Module GF |
|----------|----------:|----------:|----------:|
| Fall / Working at Height | 29 | 43 | 11 |
| Lifting / Rigging | 28 | 16 | 12 |
| Housekeeping / Access Way | 22 | 14 | 8 |
| Equipment / Vehicle | 13 | 6 | 2 |
| Electrical / Fire | 4 | 4 | 10 |
| Structural / Collapse | 5 | 8 | 4 |
| Gas / Explosion | 1 | 1 | 4 |
| **합계** | **68** | **59** | **26** |

**주요 특이사항:**
- **Module 2F** — 추락 이슈 가장 집중 (43건 / 전체 추락의 58.1%); W5 추락 5건 추가로 격차 확대
- **Module 1F** — 추락·인양 복합 발생 다수, 장비 사고 집중
- **Module GF** — 전기·화재 이슈 집중 (10건 / GF 전체의 38.5%), 가스 취급 이슈도 집중; W5 인양 1건 추가

---

## 6. Vendor-wise Breakdown

| Vendor | 총 건수 | 주요 이슈 Top 3 |
|--------|-------:|----------------|
| **DSHI** | 76 | 추락(42) · 인양(42) · 장비(18) |
| **Hankuk** | 68 | 추락(32) · 정리정돈(24) · 인양(14) |
| **Daemyoung** | 7 | 전기(4) · 기타(3) |
| Halim | 1 | 정리정돈(1) |
| Samho | 1 | 정리정돈(1) |

**주요 특이사항:**
- **DSHI** — W5(23.03)는 DSHI 구역 집중 점검일로 9건 집중 기록; 인양·추락 이슈 각각 42건으로 동률 (W4까지 기준으로도 리깅 이슈 압도적)
- **DSHI Vendor 순위 역전** — W5 집중 점검 영향으로 총 건수 Hankuk(68) 추월; 건수 단순 비교보다 이슈 패턴 중심 분석 권장
- **Hankuk** — 추락·정리정돈 이슈 비중 높음 (Module 2F 작업 집중), W5 추가 없음
- **Daemyoung** — 전기 이슈 4건 모두 미조치 (Module GF 집중)

---

## 7. Completion Status Analysis

| 구분 | 건수 | 비율 |
|------|-----:|-----:|
| 조치 완료 (Yes) | 49 | 32.0% |
| 미조치 (No) | 104 | 68.0% |

**미조치 카테고리별:**

| Category | 미조치 건수 | 미조치율 |
|----------|----------:|--------:|
| Fall / Working at Height | 46 | 62.2% |
| Lifting / Rigging | 42 | 75.0% |
| Housekeeping / Access Way | 35 | 79.5% |
| Equipment / Vehicle | 20 | **95.2%** |
| Electrical / Fire | 14 | 77.8% |
| Structural / Collapse | 9 | 52.9% |
| PPE / Training | 6 | 75.0% |
| Falling Object / Material | 6 | 75.0% |
| Gas / Explosion | 3 | 50.0% |

> **Equipment / Vehicle 미조치율 95.2%** — W5에서 Boom Lift 1건 당일 완료로 100%에서 소폭 개선, 그러나 여전히 매우 높아 즉각 조치 필요

---

## 8. Key Findings & Recommendations

| # | 발견 사항 | 권고 조치 |
|---|---------|---------|
| 1 | 추락·인양 이슈가 전체의 **85.0%** (중복 포함) 차지 | 고소·인양 작업 전 TBM 강화, 안전대 체결 2인 확인 의무화 |
| 2 | 신호수(Signalman) 관련 위반 **반복** — DSHI 집중, W5에서도 재발 | 인양 작업 시 신호수 배치 확인 후 작업 시작 규정 강화 |
| 3 | **미조치율 68.0%** — 3월 급증 후 후속 조치 부진 지속 | 일일 미조치 현황 공유 및 조치 기한 준수 강제화 |
| 4 | 장비·차량 이슈 **95.2% 미조치** (W5에서 소폭 개선) | Scissor Lift / JCB / Boom Lift 작업 전 안전 점검표 제출 의무화 |
| 5 | Module GF — 전기·가스 복합 위험 집중 | GF 구역 전기·가스 작업 별도 Permit-to-Work 시행 |
| 6 | **Structural / Collapse 17건** — W5에서 추락방지대 불량연결·불안전 위치 신규 패턴 | 무지지 빔 작업·좁은 빔 위 작업 즉시 중단 및 안전 계획 수립 |
| 7 | **W5(23.03) 9건 전부 DSHI** — 집중 점검 실시일로 발생 집중; 이슈 내용 자체(추락·구조)는 유효한 관리 대상 | W5 점검에서 식별된 위반 사항 우선 조치 확인 |
| 8 | 3월 건수 급증 (30 → 153건, **5.1배**) | 현장 활동량 증가에 비례한 안전 인력 및 점검 빈도 확충 검토 |

---

## 9. Weekly Trend (3월 주차별 추세)

### 9-1. 주차별 건수 및 미조치율

| 주차 | 기간 | 총 건수 | 조치완료 | 미조치 | 미조치율 |
|------|------|--------:|---------:|-------:|--------:|
| W2 | 03.06 – 03.07 | 16건 | 10건 | 6건 | 37.5% |
| W3 | 03.09 – 03.14 | 56건 | 19건 | 37건 | 66.1% |
| W4 | 03.16 – 03.21 | 72건 | 16건 | 56건 | 77.8% |
| W5 | 03.23 | 9건 | 4건 | 5건 | 55.6% |
| **합계** | | **153건** | **49건** | **104건** | **68.0%** |

> W5(23.03) 미조치율 55.6% — W4(77.8%) 대비 22.2%p 개선, 당일 현장 대응 적극성 증가
> 단, 9건 전부 DSHI 단일 벤더 발생으로 벤더 집중 위험도 상승

---

### 9-2. 주차별 카테고리 분포

| Category | W2 (16건) | W3 (56건) | W4 (72건) | W5 (9건) | 추세 |
|----------|----------:|----------:|----------:|---------:|------|
| Fall / Working at Height | 15 | 22 | 31 | 6 | ↑ 지속 증가 |
| Lifting / Rigging | 7 | 21 | 25 | 3 | ↑ 지속 증가 |
| Housekeeping / Access Way | 2 | 22 | 20 | 0 | → W5 발생 없음 |
| Equipment / Vehicle | 3 | 8 | 9 | 1 | ↑ 완만 지속 |
| Electrical / Fire | 0 | 9 | 8 | 1 | → W3 이후 고착·소폭 지속 |
| Structural / Collapse | 2 | 3 | 10 | 2 | ↑ W4 급증 후 W5 재발 |
| PPE / Training | 1 | 0 | 7 | 0 | ↑ W4 신규 급증, W5 소강 |
| Falling Object / Material | 2 | 1 | 5 | 0 | ↑ W4 증가, W5 소강 |
| Gas / Explosion | 1 | 1 | 4 | 0 | ↑ W4 증가, W5 소강 |
| Other | 4 | 9 | 13 | 0 | → W5 발생 없음 |

---

### 9-3. 주차별 Vendor 분포

| Vendor | W2 | W3 | W4 | W5 |
|--------|---:|---:|---:|---:|
| DSHI | 7 | 26 | 34 | **9** |
| Hankuk | 9 | 25 | 34 | 0 |
| Daemyoung | 0 | 3 | 4 | 0 |
| Halim | 0 | 1 | 0 | 0 |
| Samho | 0 | 1 | 0 | 0 |

> **W5 특이사항:** DSHI 9건 / Hankuk 0건 — 23.03은 DSHI 구역 집중 점검 실시일; 벤더 위험도 비교 목적으로 W5 수치를 단독 인용 시 주의

---

### 9-4. 주차별 Location 분포

| Location | W2 | W3 | W4 | W5 |
|----------|---:|---:|---:|---:|
| Module 1F | 7 | 31 | 28 | 2 |
| Module 2F | 8 | 12 | 33 | 6 |
| Module GF | 1 | 13 | 11 | 1 |

> - **Module 2F** — W5에서 6건 발생 (W5 전체의 66.7%), 추락 이슈 지속 집중
> - **Module 1F** — W3에 집중 (31건), 인양·리깅 위반 다수; W5 2건으로 소강
> - **Module GF** — W3 이후 전기·가스 이슈 지속; W5 인양 1건 추가

---

### 9-5. 주차별 주요 특이사항

**W2 (03.06–03.07, 16건)**
- 분석 기간 초반, 추락 이슈(15건)가 전체의 94%로 압도적
- 미조치율 37.5% — 4개 주차 중 가장 낮음 (초기 현장 대응 활발)
- Housekeeping 위반 단 2건 — 작업 초기 정리 상태 양호

**W3 (03.09–03.14, 56건)**
- 전주 대비 **3.5배 급증** (16 → 56건)
- Housekeeping 위반 22건으로 폭증 — 자재 반입·작업 확대에 따른 현장 혼잡 반영
- 전기·화재 이슈 9건 신규 등장 (Module GF 집중)
- 미조치율 66.1%로 상승 — 건수 급증으로 후속 조치 지연 시작

**W4 (03.16–03.21, 72건)**
- 최다 건수 주차 (전체의 47.1%)
- **Structural / Collapse 10건** — W2(2건) 대비 5배, 무지지 빔·좁은 빔 위 작업 확대
- **PPE / Training 7건** — W3(0건) 대비 신규 급증, 작업 강도 증가에 따른 PPE 소홀
- **Gas / Explosion 4건** — 가스 실린더 취급 위반 집중
- 미조치율 **77.8%** — 최고치 기록, 조치 이행 체계 재점검 필요

**W5 (03.23, 9건)**
- 9건 전부 **DSHI** — 23.03 DSHI 구역 집중 점검 실시일; 벤더 집중이 아닌 점검 집중에 따른 결과
- **Module 2F 집중** (6건 / 66.7%) — 추락 이슈 5건 포함
- 미조치율 55.6% (5건/9건) — W4 대비 개선, 당일 4건 즉시 조치 완료
- Structural/Collapse 2건 재발 (추락방지대 날카로운 연결, 불안전 위치 작업)
- 신규 이슈: 앵커볼트 이완, 바리케이드 로프 이완, 용접 중 어싱 미연결

---

## 10. Monthly Trend (누적)

| Month | Records | 누적 |
|-------|--------:|-----:|
| Dec 2025 | 11건 | 11건 |
| Feb 2026 | 30건 | 41건 |
| Mar 2026 (to 23rd) | 153건 | 194건 |

> Mar 2026 데이터가 전체 누적의 78.9% 차지 — 현장 활동 급증 및 점검 강화 반영

---

## 12. Analysis Notes

- **분석 도구:** KeyBERT (sentence-transformers 기반 키워드 추출)
- **임베딩 모델:** `paraphrase-multilingual-MiniLM-L12-v2` (384-dim)
- **데이터 소스:** `data_mar2026.csv` (153건, 06.03.2026 – 23.03.2026)
- **분류 방식:** 추출 키워드와 테마별 키워드 사전(domain keyword matching) 조합
- 1건이 복수 이슈에 해당될 수 있어 카테고리별 합계 > 전체 건수
- KeyBERT keyphrase_ngram_range: (1,3), top_n=7, MMR diversity=0.5
- **업데이트:** 2026-03-25 — W5(23.03.2026) 9건 추가 반영 (이전 버전: 144건 기준, 21.03까지)
