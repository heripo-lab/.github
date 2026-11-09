**English** | [한국어](./README.ko.md)

## About heripo lab

heripo lab is a nonprofit organization that brings together archaeology and software engineering. We turn knowledge in excavation reports into data linked to original records and sources, and build open-source tools and research platforms that help researchers and the wider public reuse it.

## 🕖 History

- 2026 Nov 7 — Presented “From Accumulation to Circulation: The Next 50 Years of Korean Archaeology” at the Future Generations Forum of the 50th Annual Meeting of the Korean Archaeological Society (Kim, Hongyeon & Cho, Hayoung) — R&D applications in education and cultural content, and a vision for knowledge circulation
- 2026 Nov 6 — Presented the poster “A Three-Stage Model and Openness Strategy for Transforming Excavation Reports into Data” at the 50th Annual Meeting of the Korean Archaeological Society (Cho, Hayoung; Kim, Hongyeon; Kim, Gaeun)
- 2026 Oct 30 — Released [heripo engine 0.2.0](https://github.com/heripo-lab/heripo-engine/tree/v0.2.0), implementing archaeological data ledger extraction
- 2026 Sep — Started alpha testing for [heripo basecamp](https://heripo.app), an archaeology research tool built around excavation reports
- 2026 Jul — Special Lecture: Archaeology Through Relationships: Social Network Analysis (SNA), [Department of Archaeology, Graduate School, Pusan National University](https://archaeology.pusan.ac.kr/archaeology/index..do) (Cho, Hayoung) — [Lecture Materials](https://github.com/heripo-lab/special-lecture-pnu-2026-07-hayoung)
- 2026 Jul — Special Lecture: AI for Archaeological Researchers: Understanding LLMs, Structuring Research Materials, Security, and Validation, [Department of Archaeology, Graduate School, Pusan National University](https://archaeology.pusan.ac.kr/archaeology/index..do) (Kim, Hongyeon) — [Lecture Materials](https://github.com/heripo-lab/special-lecture-pnu-2026-07-hongyeon-index)
- 2026 Jun — Special Lecture: Cultural Heritage Research in the AI Era, [Graduate School of Archaeology and Art History, Korea University](https://cuhc.korea.ac.kr/cuhc/5043/subview.do) (Kim, Hongyeon & Cho, Hayoung) — [Lecture Materials](https://github.com/heripo-lab/special-lecture-ku-2026-06-index)
- 2026 Jun — [Dataya Nolja](https://datayanolja.com/) 2026: [Building an LLM Pipeline to Excavate Sleeping Archaeological Data: How a Liberal Arts Student's Dream Became Open Source](https://youtu.be/BUeCWE_5Sl0?si=ec2meQofZfeJ36ym) (Kim, Hongyeon)
- 2026 Mar — Kim, Gaeun joined as a software engineer
- 2026 Feb — Signed an MOU with [The Korean Archaeological Society](https://www.kras.or.kr)
- 2026 Jan — Open-sourced [heripo engine](https://github.com/heripo-lab/heripo-engine)
- 2026 Jan — Cho, Hayoung joined as an archaeology & ontology researcher
- 2025 Nov — Released [heripo research radar (Korean cultural heritage newsletter)](https://github.com/heripo-lab/heripo-research-radar)
- 2025 Nov — Released [LLM Newsletter Kit (LLM-based newsletter framework)](https://github.com/heripo-lab/llm-newsletter-kit-core)
- 2025 Sep — Released [Archaeological Informatization PoC (PoC snapshot from a KCI-listed paper)](https://github.com/heripo-lab/archaeological-informatization-poc)

## 📚 Research Objectives

- **Find and verify archaeological materials**: Link information about features and artifacts to original records and sources so researchers can explore, compare, and verify it.
- **Democratize archaeological knowledge**: Help teachers, planners, and creators, as well as researchers, find materials and reuse them in their own work. Experts remain essential to reviewing source context and the limits of interpretation and reconstruction.
- **Move from accumulation to circulation**: Put archaeological knowledge to use in education, exhibitions, and cultural content, and bring the questions and materials arising from that use back into research, conservation, and management.

## ⚙️ Data Design Principles

We distinguish report records from classifications and interpretations used in research, keeping transformed data traceable to its evidence.

1. **Document structure extraction** — Extract chapters, text, tables, drawings, and photographs with links to their original locations.
2. **Archaeological data ledger** — Preserve report authors’ observations, judgments, and interpretations with original text and sources, without rewriting or normalization. Flag uncertain judgments for review.
3. **Multiple standard models** — Accommodate classification, naming, and chronological systems that vary by research purpose, with their scope, lineage, and version.
4. **Ontology** — Connect sites, features, artifacts, and related concepts through semantic relationships whose evidence can be traced.

Ledger extraction was **implemented experimentally in heripo engine 0.2.0**. It has been developed and evaluated on three reports; broader coverage and a stable ledger format are next steps. Multiple standard models and ontology integration remain future work.

## 🔓 Tools and Open Data

- [heripo engine](https://github.com/heripo-lab/heripo-engine) provides report processing and ledger extraction under Apache-2.0.
- [heripo basecamp](https://heripo.app) helps researchers explore report data alongside original records. It is in invitation-only private alpha testing.
- We plan to share eligible transformed data under CC BY 4.0 with provenance, review status, and version information, together with model definitions and mapping rules. This will support reuse outside the platform and commercial use.

## 👥 Team & Background

### 🛠️ Kim, Hongyeon (Lead Engineer)

- Role: Design of LLM-based unstructured data extraction pipeline and system implementation
- Background:
  - Software Engineer
  - B.S. in Computer Science
  - B.A. in Archaeology
- Research:
  - A Study on Archaeological Informatization Using Large Language Models (LLMs): Proof of Concept for an Automated Metadata Extraction Pipeline from Archaeological Excavation Reports (2025, *Heritage: History and Science* Vol. 58 No. 3, KCI Listed)
    - DOI: [10.22755/kjchs.2025.58.3.34](https://doi.org/10.22755/KJCHS.2025.58.3.34)
    - [Korean Original](https://koreascience.kr/article/JAKO202570361249829.page)
    - [Official English Version (PDF)](https://files.heripo.org/archaelogical-informatization-poc/(Eng._Version)_KIM_Hongyeon_2025_A_Study_on_Archaeological_Informatization_Using_Large_Language_Models.pdf)

### ✏️ Cho, Hayoung (Domain Researcher)

- Role: Archaeological data ontology design, data schema definition, and academic validation
- Background:
  - Ph.D. Student in Archaeology
  - M.A. in Cultural Informatics
- Research:
  - Considerations for Structuring Maritime Cultural Heritage Data (2025, *Journal of the Island Culture* No. 66, KCI Listed)
    - DOI: [10.22917/island.2025..66.271](https://doi.org/10.22917/island.2025..66.271)
  - [Semantic Data Design for Maritime Cultural Heritage: Focusing on Ancient Shipwrecks and Wooden Tablets Excavated from the Taean Mado waters](https://lib.aks.ac.kr/#/search/detail/1036933) (2025, Master’s Thesis)

### 🛠️ Kim, Gaeun (Software Engineer)

- Role: Development of archaeology research platforms
- Background:
  - Software Engineer
  - M.A. in Archaeology (Coursework Completed)
  - B.A. in Archaeology
  - B.A. in Library and Information Science

## 💖 Sponsor

If you'd like to support heripo lab's open-source research, you can sponsor us through:

- [Open Collective](https://opencollective.com/heripo-project) for general project sponsorship.
- [fairy.hada.io/@heripo](https://fairy.hada.io/@heripo) for Korean individual supporters who prefer KRW payments.
