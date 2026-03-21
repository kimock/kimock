# Safety Violation — Key Issue Analysis Report

**Project:** SDN Module Expansion PJT
**Analysis Period:** Dec 2025 – Mar 2026
**Method:** KeyBERT (paraphrase-multilingual-MiniLM-L12-v2)
**Total Records Analyzed:** 142건
**Report Date:** 2026-03-21

---

## 1. Executive Summary

Dec 2025부터 Mar 2026까지 기록된 안전 위반 142건을 KeyBERT 텍스트 분석한 결과,
**추락·고소작업** 이슈가 전체의 45%로 압도적 1위를 차지했으며,
**인양·리깅** 이슈가 28%로 뒤를 이었다.
두 이슈는 고소 인양 작업 중 동시 발생하는 패턴이 반복되고 있어 집중 관리가 필요하다.

---

## 2. Monthly Data Volume

| Month | Records |
|-------|--------:|
| Dec 2025 | 11건 |
| Feb 2026 | 30건 |
| Mar 2026 | 103건 |
| **합계** | **144건** (유효 분석: 142건) |

> Mar 2026 데이터가 전체의 72%를 차지 — 현장 활동 증가 반영

---

## 3. Issue Ranking

| Rank | Issue Category | Count | % | Severity |
|------|---------------|------:|---:|----------|
| 1 | Fall / Working at Height (추락·고소작업) | 64 | 45.1% | 🔴 Critical |
| 2 | Lifting / Rigging (인양·리깅) | 40 | 28.2% | 🔴 Critical |
| 3 | Housekeeping / Access Way (정리정돈·통행로) | 23 | 16.2% | 🟡 Medium |
| 4 | Equipment / Vehicle (장비·차량) | 17 | 12.0% | 🟠 High |
| 5 | Other (기타·행정) | 18 | 12.7% | ⚪ Low |
| 6 | Electrical / Fire (전기·화재) | 12 | 8.5% | 🔴 Critical |
| 7 | Falling Object / Material (낙하물) | 9 | 6.3% | 🟠 High |
| 8 | PPE / Training (PPE·교육) | 5 | 3.5% | 🟡 Medium |
| 9 | Gas / Explosion (가스·폭발) | 4 | 2.8% | 🔴 Critical |
| 9 | Structural / Collapse (구조·붕괴) | 4 | 2.8% | 🟠 High |

> 1건이 복수 카테고리에 해당될 수 있으므로 합계 > 100%

---

## 4. Top Issue Detail

### 🔴 Rank 1 — Fall / Working at Height (64건, 45.1%)

고소작업 중 추락 위험이 전체 이슈의 절반에 육박.
안전대 미체결, 개구부 미차단, 비계 불안전 작업이 반복 패턴.

**핵심 키워드:** `safety harness` · `edge area` · `lifeline` · `scaffold` · `boom lift` · `opening` · `jack/props` · `pfas`

**대표 사례:**
- *"Crane lifting steel beams with workers on the elevated platform; inadequate fall protection, engineer was out of boom bucket in risky manner"*
- *"Working in boom lift bucket near electrical cables or live line"*
- *"Worker was standing on jack/Props in unsafe manner, can slip and will get injury"*

---

### 🔴 Rank 2 — Lifting / Rigging (40건, 28.2%)

인양 작업 중 신호수 부재, 무단 진입, 불량 리깅 자재 사용이 주요 원인.
Rank 1과 동시 발생 케이스 다수 (고소 인양 작업).

**핵심 키워드:** `signalman` · `crane` · `web sling` · `shackle` · `unauthorized entry` · `lifting area` · `deck sheet` · `underneath`

**대표 사례:**
- *"No barricade of working area of scissor lift & no signalman"*
- *"During lifting process some workers were observed in the lifting area and materials can fall"*
- *"The rounds from web sling were not removed before start lifting"*

---

### 🟡 Rank 3 — Housekeeping / Access Way (23건, 16.2%)

자재 산재 및 통행로 미확보로 인한 낙상·충돌 유발.
지속 반복되는 기본 생활안전 위반.

**핵심 키워드:** `scattered` · `haphazard` · `access way` · `housekeeping` · `uneven staking` · `trip hazard`

**대표 사례:**
- *"Poor housekeeping of materials and storage boxes, and lack of designated storage areas"*
- *"Materials scattered in access way in haphazard manner"*
- *"Uneven staking of scaffold pipes; area was not barricaded"*

---

### 🟠 Rank 4 — Equipment / Vehicle (17건, 12.0%)

지게차·JCB·크레인 운용 중 작업자 충돌 위험.
바리케이드 미설치 및 무단 접근 통제 실패.

**핵심 키워드:** `forklift` · `JCB` · `crane boom` · `scissor lift` · `tip over` · `center of gravity`

**대표 사례:**
- *"JCB is working without proper barrier"*
- *"Forklift transporting pallet with worker guiding it; no visible PPE on the guiding worker"*
- *"forklift operating on site, worker stepping onto yellow platform"*

---

### 🔴 Rank 6 — Electrical / Fire (12건, 8.5%)

전기 설비 접지 미비 및 소화 시설 접근 차단이 주요 패턴.
빈도는 낮으나 중대재해 직결 위험으로 우선 처리 필요.

**핵심 키워드:** `earthing` · `PDB` · `cable` · `core drill` · `fire hydrant` · `hot work`

**대표 사례:**
- *"Stand core drill machine — no body earthing connection has been given"*
- *"PDB access is blocked; materials scattered nearby"*
- *"Fire hydrant access is blocked; materials stored in front"*

---

### 🟠 Rank 7 — Falling Object / Material (9건, 6.3%)

인양 중 자재 낙하 및 비계 planks 간격 불량으로 인한 낙하물 위험.

**핵심 키워드:** `toe board` · `planks` · `drop` · `loose material` · `overhead`

**대표 사례:**
- *"Toe board were not installed in the scaffolding area to avoid material falling"*
- *"Uneven/Unsafe gap in the scaffolding planks, materials can fall down"*

---

### 🔴 Rank 9 — Gas / Explosion (4건, 2.8%)

빈도는 낮지만 가스통 취급 불량은 즉각 조치 필요 사안.

**대표 사례:**
- *"Improper handling of compress gas cylinder (Materials stores Yard)"*
- *"Two filled oxygen cylinders found with single chain going to lift — high chances of imbalance"*

---

## 5. Key Findings & Recommendations

| # | 발견 사항 | 권고 조치 |
|---|---------|---------|
| 1 | 추락·인양 이슈가 전체의 **73%** (중복 포함) 차지 | 고소·인양 작업 전 TBM 강화, 안전대 체결 확인 의무화 |
| 2 | 신호수(Signalman) 관련 위반 **반복** | 인양 작업 시 신호수 2인 배치 규정 및 사전 교육 |
| 3 | 정리정돈·통행로 위반이 16% — **기본 생활안전** 미준수 | 작업 종료 후 정리정돈 체크리스트 의무 제출 |
| 4 | 전기·화재(PDB/소화전 차단)는 **빈도 대비 위험도 최고** | 소화전·PDB 주변 2m 이내 자재 적치 즉시 금지 조치 |
| 5 | Mar 2026에 건수 급증 (11→30→103건) | 현장 활동량 증가에 비례한 안전 인력 확충 검토 |

---

## 6. Analysis Notes

- **분석 도구:** KeyBERT (sentence-transformers 기반 키워드 추출)
- **임베딩 모델:** `paraphrase-multilingual-MiniLM-L12-v2` (384-dim)
- **데이터 소스:** `data_dec2025.csv` / `data_feb2026.csv` / `data_mar2026.csv`
- **분류 방식:** 추출 키워드와 테마별 키워드 사전(domain keyword matching) 조합
- 1건이 복수 이슈에 해당될 수 있어 카테고리별 합계 > 전체 건수
