[English](./README.md) | **한국어**

## heripo lab 소개

heripo lab은 고고학과 소프트웨어 엔지니어링을 결합하는 비영리단체입니다. 발굴조사보고서 속 지식을 원문·출처와 함께 데이터로 옮기고, 연구자와 사회가 활용할 수 있도록 오픈소스 도구와 연구 플랫폼을 만듭니다.

## 🕖 연혁

- 2026년 11월 7일 — 제50회 한국고고학전국대회 미래세대 토론회에서 「축적에서 순환으로, 한국고고학의 다음 50년」 발표 (김홍연, 조하영) — 연구·개발 성과의 교육·콘텐츠 활용과 지식 순환의 비전 제시
- 2026년 11월 6일 — 제50회 한국고고학전국대회에서 「발굴조사보고서의 데이터 전환을 위한 3단계 모델과 개방 전략」 포스터 발표 (조하영, 김홍연, 김가은)
- 2026년 10월 30일 — [heripo engine 0.2.0](https://github.com/heripo-lab/heripo-engine/tree/v0.2.0) 출시, 고고학 데이터 원장 추출 구현
- 2026년 9월 — 발굴조사보고서 기반 고고학 연구 지원 도구 [헤리포 베이스캠프](https://heripo.app) 알파 테스트 시작
- 2026년 7월 — [부산대학교 대학원 고고학과](https://archaeology.pusan.ac.kr/archaeology/index..do)에서 「관계로 보는 고고학: 사회관계망분석(SNA)」을 주제로 특강 (조하영) — [강의 자료](https://github.com/heripo-lab/special-lecture-pnu-2026-07-hayoung)
- 2026년 7월 — [부산대학교 대학원 고고학과](https://archaeology.pusan.ac.kr/archaeology/index..do)에서 「고고학 연구자를 위한 AI 활용법: LLM의 이해, 연구자료 구조화, 보안과 검증」을 주제로 특강 (김홍연) — [강의 자료](https://github.com/heripo-lab/special-lecture-pnu-2026-07-hongyeon-index)
- 2026년 6월 — [고려대학교 대학원 고고미술사학과](https://cuhc.korea.ac.kr/cuhc/5043/subview.do)에서 「AI시대의 문화유산 연구」를 주제로 특강 (김홍연, 조하영) — [강의 자료](https://github.com/heripo-lab/special-lecture-ku-2026-06-index)
- 2026년 6월 — [데이터야놀자](https://datayanolja.com/) 2026에서 「[문과생의 꿈이 오픈소스가 되기까지: 잠든 고고학 데이터를 발굴하는 LLM 파이프라인 구축기](https://youtu.be/BUeCWE_5Sl0?si=ec2meQofZfeJ36ym)」 주제로 발표 (김홍연)
- 2026년 3월 — 김가은 소프트웨어 엔지니어 합류
- 2026년 2월 — [한국고고학회](https://www.kras.or.kr)와 MOU 체결
- 2026년 1월 — [heripo engine](https://github.com/heripo-lab/heripo-engine) 오픈소스 공개
- 2026년 1월 — 조하영 고고학·온톨로지 연구원 합류
- 2025년 11월 — [heripo research radar (한국 문화유산 뉴스레터)](https://github.com/heripo-lab/heripo-research-radar) 공개
- 2025년 11월 — [LLM Newsletter Kit (LLM 기반 뉴스레터 프레임워크)](https://github.com/heripo-lab/llm-newsletter-kit-core) 공개
- 2025년 9월 — [고고학 정보화 PoC (KCI 등재 논문 기반 PoC 스냅샷)](https://github.com/heripo-lab/archaeological-informatization-poc) 공개

## 📚 연구 목표

- **찾고 확인할 수 있는 고고학 자료**: 보고서 속 유구·유물 정보를 원문·출처와 연결하여 연구자가 탐색·비교·검증할 수 있도록 합니다. 원자료의 맥락과 해석·복원의 한계를 검토하는 전문가의 역할을 중시합니다.
- **고고학 지식의 민주화**: 사회적 비용을 들여 축적한 고고학 지식이 사회의 다양한 영역에서 활용될 수 있도록 합니다. 자료를 찾고 이해하는 장벽을 낮춰, 더 많은 사람이 근거를 확인하며 새로운 교육·전시·콘텐츠를 만드는 데 활용할 수 있게 합니다.
- **축적에서 순환으로**: 고고학 지식이 교육·전시·문화콘텐츠에 활용되고, 그 과정에서 생긴 질문과 자료가 다시 연구·보존·관리에 기여하는 방향을 추구합니다.

## ⚙️ 데이터 설계 원칙

보고서의 기록과 연구 목적에 따른 분류·해석을 구분하고, 변환 결과의 근거를 되짚을 수 있도록 설계합니다.

1. **문서 구조 추출** — 장·절, 본문, 표, 도면·사진을 추출하고 원문의 위치를 연결합니다.
2. **고고학 데이터 원장** — 보고서 작성자의 관찰·판단·해석을 원문·출처와 함께 보존합니다. 원문을 재서술하거나 정규화하지 않으며, 불확실한 판단은 검수 항목으로 남깁니다.
3. **다중 표준 모델** — 연구 목적에 따라 달라지는 분류·명명·편년 체계를 함께 다루고, 적용 범위·계보·버전을 관리합니다.
4. **온톨로지** — 유적·유구·유물과 관련 개념의 의미 관계를 연결하고, 각 관계의 근거를 추적할 수 있도록 합니다.

원장 추출은 **heripo engine 0.2.0에서 실험적으로 구현**했습니다. 현재 보고서 3종으로 개발·검증했으며, 적용 대상 확대와 원장 형식 안정화를 진행할 예정입니다. 다중 표준 모델과 온톨로지 적용은 후속 과제입니다.

## 🔓 도구와 데이터의 공개

- [heripo engine](https://github.com/heripo-lab/heripo-engine)은 Apache-2.0으로 공개한 보고서 처리·원장 추출 도구입니다.
- [heripo basecamp](https://heripo.app)는 보고서 데이터를 탐색하고 원문과 함께 살펴보는 연구 지원 도구로, 초대 기반 비공개 알파 테스트 중입니다.
- 공개 가능한 변환 데이터는 출처·검수 상태·버전을 갖추어 CC BY 4.0으로 제공하고, 모델 정의·매핑 규칙도 공유할 계획입니다. 플랫폼 밖의 재사용과 상업적 활용도 지원하는 방향입니다.

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
