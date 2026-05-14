[English](./README.md) | **한국어**

## heripo lab 소개

heripo lab은 고고학 도메인 지식과 소프트웨어 엔지니어링 기술을 결합하여, 실질적인 연구 효율화를 이끄는 오픈소스 R&D 그룹입니다.

## 🕖 연혁

- 2026년 3월 — 김가은 소프트웨어 엔지니어 합류
- 2026년 2월 — [한국고고학회](https://www.kras.or.kr)와 MOU 체결
- 2026년 1월 — [heripo engine](https://github.com/heripo-lab/heripo-engine) 오픈소스 공개
- 2026년 1월 — 조하영 고고학·온톨로지 연구원 합류
- 2025년 11월 — [heripo research radar (한국 문화유산 뉴스레터)](https://github.com/heripo-lab/heripo-research-radar) 공개
- 2025년 11월 — [LLM Newsletter Kit (LLM 기반 뉴스레터 프레임워크)](https://github.com/heripo-lab/llm-newsletter-kit-core) 공개
- 2025년 9월 — [고고학 정보화 PoC (KCI 등재 논문 기반 PoC 스냅샷)](https://github.com/heripo-lab/archaeological-informatization-poc) 공개

## 📚 연구 목표

- 고고학 발굴조사보고서는 방대한 지식을 담고 있지만, 대부분 비정형 상태로 남아 있습니다.
- heripo는 이를 단순한 기술 문제가 아니라 연구 실천의 구조적 제약으로 봅니다.
- 발굴 기록의 출처 맥락을 잃지 않으면서 구조화되고 검증 가능한 데이터로 전환합니다.
- 기술은 연구 실천을 지원하며, 해석과 판단은 연구자에게 남아 있습니다.
- heripo는 비교·누적 고고학을 위한 지속 가능한 연구 인프라를 구축합니다.

## ⚙️ 데이터 설계 원칙

heripo는 기록, 데이터 추출, 표준화, 해석을 분리하는 계층형 데이터 모델을 채택합니다:

1. 문서 구조 추출 — 장·절, 표, 도면, 사진을 원형 그대로 보존
2. 고고학 데이터 원장 — 출처에 충실하고 불변인 형태로 사실을 기록
3. 표준화 — 연구 목적에 따라 선택적으로 표준 적용
4. 온톨로지 — 유적 간 비교와 분석을 위한 의미 관계 정의

이러한 분리는 원본성, 추적 가능성, 학술적 검증 가능성을 보장합니다.

## 👥 팀 및 배경

### 🛠️ 김홍연 (Lead Engineer)

- Role: LLM 기반 비정형 데이터 추출 파이프라인 설계 및 시스템 구현
- Background:
  - 소프트웨어 엔지니어
  - 컴퓨터과학 학사
  - 고고학 학사
- Research:
  - 「대형 언어 모델(LLM)을 활용한 고고학 정보화 연구 -발굴조사보고서의 메타데이터 자동 추출 파이프라인 개념 검증-」 (2025, 『헤리티지: 역사와 과학』 제58권 제3호, KCI 등재)
    - DOI: [10.22755/kjchs.2025.58.3.34](https://doi.org/10.22755/KJCHS.2025.58.3.34)
    - [한국어 원문](https://koreascience.kr/article/JAKO202570361249829.page)
    - [공식 영문판 (PDF)](<https://files.heripo.org/archaelogical-informatization-poc/(Eng._Version)_KIM_Hongyeon_2025_A_Study_on_Archaeological_Informatization_Using_Large_Language_Models.pdf>)

### ✏️ 조하영 (Domain Researcher)

- Role: 고고학 데이터 온톨로지 설계, 데이터 스키마 정의 및 학술적 정합성 검증
- Background:
  - 고고학전공 박사과정
  - 인문정보학 석사
- Research:
  - 「해양문화유산 데이터 구조화에 대한 제언」 (2025, 『도서문화』 제66집, KCI 등재)
    - DOI: [10.22917/island.2025..66.271](https://doi.org/10.22917/island.2025..66.271)
  - [「해양문화유산 시맨틱 데이터 설계 : 태안 마도 해역 출수 고선박과 목간을 대상으로」](https://lib.aks.ac.kr/#/search/detail/1036933) (2025, 석사학위논문)

### 🛠️ 김가은 (Software Engineer)

- Role: 고고학 연구 플랫폼 개발
- Background:
  - 소프트웨어 엔지니어
  - 고고학 석사 수료
  - 고고학 학사
  - 문헌정보학 학사

## 💖 후원

heripo lab의 오픈소스 연구를 후원하려면 다음 경로를 이용할 수 있습니다:

- [Open Collective](https://opencollective.com/heripo-project): 전반적인 프로젝트 후원
- [fairy.hada.io/@heripo](https://fairy.hada.io/@heripo): 한국인 개인 후원자를 위한 원화 결제
