# 반응이 아닌 효과를 찾는 데이터 분석가 '문화선' 입니다

반응이 높은 곳이 아니라 **효과가 생기는 곳**을 찾습니다.
가설을 세우고, 데이터로 확인하고, 틀렸다면 결론을 바꿉니다.

<br>

## 대표 프로젝트

| 프로젝트 | 질문 | 핵심 결과 |
|---|---|---|
| [Who-Needs-the-Ad](https://github.com/hwasun-zip/Who-Needs-the-Ad) | 광고가 정말 필요한 유저는 누구인가 | 광고 무작위 실험 데이터로 S, T, X-Learner를 비교해 상위 10%가 증분 방문의 85.8% 차지 |
| [Cookie_Cats](https://github.com/hwasun-zip/Cookie_Cats) | 이 A/B 테스트 결과를 믿어도 될까 | 배정 비율 이상(SRM)을 발견해 최악의 가정으로 민감도 분석, 리텐션 후속 실험 설계 |
| [RetailRocket](https://github.com/hwasun-zip/RetailRocket) | 유저는 어디서 떠나고, 누구를 붙잡아야 할까 | 이벤트 로그 275만 건을 SQL로 세션화, 세그먼트 정의 편향을 찾아 결론 재검증 |

<br>

## 이렇게 분석합니다

- **반응보다 증분**: 반응할 사람이 아니라, 개입 때문에 행동이 바뀌는 사람을 찾습니다
- **결론보다 검증**: 결과를 해석하기 전에 실험 배정과 지표 정의부터 확인합니다
- **로그를 의사결정 지표로**: SQL로 행동 로그를 세션과 퍼널로 바꿔, 판단에 쓸 수 있는 지표를 만듭니다

<br>

## 다른 프로젝트

- [Saving-Temperature](https://github.com/hwasun-zip/Saving-Temperature): 적금 해지 방지를 위험 예측이 아닌 Uplift 타겟팅으로 재설계
- [FinStandard-EWS](https://github.com/hwasun-zip/FinStandard-EWS): DART 재무제표 표준화와 업종 상대지표 기반 부실위험 스코어링
- [SOC-Alert-Triage](https://github.com/hwasun-zip/SOC-Alert-Triage): 네트워크 로그 SQL 행위 탐지와 Claude API 기반 경보 트리아지
- [Catalog-AutoPilot](https://github.com/hwasun-zip/Catalog-AutoPilot): Claude API로 카탈로그 이상치 원인을 자동 판단하고 리포팅

<br>

## Skills

- **언어**: SQL, Python
- **라이브러리**: pandas, NumPy, SciPy, statsmodels, scikit-learn, LightGBM
- **도구**: Power BI, Google Colab, GitHub, Claude API
- **분석 방법**: A/B 테스트, 퍼널, 코호트, Uplift Modeling
