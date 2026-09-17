# Global-subsea-cable-demand-analysis
Global subsea power cable demand research with source validation and Python-based market analysis
# Global Subsea Power Cable Demand Research
### Source Validation, Market Screening, and Forecast Analysis

글로벌 해저전력케이블 수요 증가를 정량적으로 확인하고, 여러 산업 리서치 기관의 데이터를 비교·검증하여 최종 분석용 데이터셋을 선정한 프로젝트입니다.

단순히 하나의 시장 전망치를 사용하는 대신, 데이터의 기준연도, 전망 시점, 지역 범위, CAGR, 공개 여부, 수요 대표성 등을 기준으로 여러 출처를 비교했습니다.

---

1. Project Overview

해저전력케이블(Subsea / Submarine Power Cable)은 해상풍력, 국가 간 전력망 연계, HVDC 송전망 확대와 함께 수요가 증가하고 있는 전력 인프라입니다.

본 프로젝트의 목적은 다음 질문에 답하는 것입니다.

> 글로벌 해저전력케이블 수요가 실제로 증가하고 있는가?

특히 학술 및 투자 리서치에 사용할 수 있도록, 공개적으로 검증 가능한 데이터를 중심으로 여러 리서치 기관의 자료를 비교했습니다.

---

 2. Research Criteria

최종 데이터셋을 선정하기 위해 다음 조건을 설정했습니다.

| 기준 | 조건 |
|---|---|
| 기준연도 | 2025년이 Actual 또는 Base Year |
| 전망치 | 2026F, 2027F가 동일 기관에서 제공 |
| 지역 | Global / Worldwide |
| 시계열 | 연도별 데이터 확인 가능 |
| 성장률 | CAGR 15% 이상 |
| 데이터 검증 | 공개적으로 출처 확인 가능 |
| 수요 대표성 | 해저전력케이블 수요 증가를 설명할 수 있는 지표 |

해저전력케이블 전체 시장의 연도별 공개 데이터가 제한적이기 때문에, Offshore Wind Cable Market을 해저전력케이블 수요의 대표적인 Proxy 지표로 활용했습니다.

---

3. Source Screening

여러 산업 리서치 기관의 자료를 비교했습니다.

| Source | 장점 | 한계 | 결과 |
|---|---|---|---|
| Spinergie | 해저전력케이블 설치량(km) 데이터 제공 | 일부 연도는 과거 전망치 | 제외 |
| CRU | HV Subsea Cable 수요 성장률 신뢰도 높음 | 연도별 상세 숫자 비공개 | 보조 자료 |
| TGS \| 4C | 실제 설치량과 향후 설치 전망 제공 | 2026F/2027F 개별 수치 미공개 | 보조 자료 |
| TrendX Insights | 2025 Base Year, 2026F/2027F 제공 | CAGR 15% 미만 | 제외 |
| PW Consulting / PmarketResearch | 2025 Base Year, 글로벌, CAGR 15% 이상 | Offshore Wind Cable 범위 | 최종 채택 |

---

4. Final Dataset

최종적으로 PW Consulting / PmarketResearch의 "Worldwide Offshore Wind Cable Market 2026" 데이터를 사용했습니다.

| Year | Market Size (USD Billion) | Classification |
|---|---:|---|
| 2023 | 4.049 | Historical |
| 2024 | 4.627 | Historical |
| 2025 | 5.320 | Base Year |
| 2026 | 6.321 | Forecast |
| 2027 | 7.046 | Forecast |

### CAGR

*2025–2032 CAGR: 15.96%*

2025년 시장규모는 약 **$5.32B**, 2032년에는 약 "$15.0B"까지 성장할 것으로 전망됩니다. 
---

 5. Growth Analysis

연도별 증가율은 다음과 같습니다.

| Period | YoY Growth |
|---|---:|
| 2023 → 2024 | 14.29% |
| 2024 → 2025 | 14.97% |
| 2025 → 2026 | 18.81% |
| 2026 → 2027 | 11.48% |

특히 2025년 이후에도 시장규모가 지속적으로 증가하며, 중장기적으로 두 자릿수 성장률이 유지될 것으로 전망됩니다. 

---

 6. Industry Validation

최종 데이터 외에도 여러 산업 자료를 통해 해저전력케이블 수요 증가를 교차 검증했습니다.

TGS | 4C

TGS | 4C에 따르면 전 세계 해상풍력용 케이블 누적 설치량은

- 2015년: 9,000 km
- 2025년: 55,500 km

로 약 6배 증가했습니다.

또한 2026~2040년 동안 해상풍력 프로젝트에 추가로 약 117,640 km의 케이블이 설치될 것으로 전망합니다. 

<CRU>

CRU는 2024~2030년 동안 글로벌 HV Subsea Cable 수요가 연평균 약 25.1% 성장할 것으로 전망하고 있습니다. Offshore Wind 관련 케이블 수요 역시 약 22.7% CAGR로 성장할 것으로 예상됩니다.

이러한 자료는 해저전력케이블 수요 증가가 단일 기관의 전망에만 의존하지 않는다는 점을 보여줍니다.

---

7. Why Offshore Wind Cable?

본 프로젝트에서 사용하는 최종 데이터는 전체 Subsea Power Cable 시장이 아닌 Offshore Wind Cable Market입니다.

그 이유는 다음과 같습니다.

- Offshore Wind Cable은 실제 해저 전력케이블 수요를 구성
- Export Cable과 Inter-array Cable 포함
- 해상풍력 확대가 해저전력케이블 수요 증가의 핵심 원인 중 하나
- 글로벌 연도별 데이터 공개성이 상대적으로 높음

따라서 본 프로젝트에서는 Offshore Wind Cable 시장을 해저전력케이블 수요 증가를 설명하는 대표 Proxy로 사용했습니다.

---

 8. Methodology

분석 과정은 다음과 같습니다.

1. 글로벌 해저전력케이블 관련 산업 리서치 수집
2. 2025 Base Year 여부 확인
3. 2026F / 2027F 동일 기관 여부 확인
4. Global 범위 여부 확인
5. CAGR 15% 이상 여부 확인
6. 연도별 숫자 공개 여부 확인
7. 최종 데이터 선정
8. Python을 활용한 YoY / CAGR 계산
9. 다른 산업 자료와 교차 검증

---

9. AI-Assisted Research

본 프로젝트에서는 생성형 AI를 다음 용도로 활용했습니다.

- 산업 리서치 출처 탐색
- 여러 데이터셋 비교
- 기준연도 및 전망치 구조 확인
- Python 코드 작성 보조
- 데이터 정리 및 문서화

다만 AI가 제시한 숫자를 그대로 사용하지 않고, \원문 출처와 데이터 구조를 직접 확인하여 교차 검증했습니다.

특히 다음과 같은 문제를 확인하고 제외했습니다.

- 2025년 수치가 실제값이 아닌 과거 전망치인 경우
- CAGR 조건을 충족하지 않는 경우
- 연도별 데이터가 공개되지 않은 경우
- 전체 시장과 세부 시장의 범위가 다른 경우

---

10. Limitations

본 프로젝트에는 다음과 같은 한계가 있습니다.

- 최종 데이터는 전체 Subsea Power Cable 시장이 아니라 Offshore Wind Cable 시장임
- 설치량(km)이 아닌 시장규모(USD) 기준
- 일부 고품질 산업 데이터는 유료 보고서에 포함되어 있음
- 리서치 기관별 시장 정의와 범위가 다를 수 있음

따라서 본 분석은 절대적인 시장 규모 추정치보다는 수요 증가 방향성과 성장성 확인에 초점을 둡니다.

---

11. Repository Structure

```text
subsea-cable-market-research/
│
├── README.md
├── analysis.ipynb
│
├── data/
│   └── offshore_wind_cable_market.csv
│
├── report/
│   └── subsea_cable_market_report.pdf
│
└── sources/
    └── source_validation.md
