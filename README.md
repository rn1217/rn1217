# 안녕하세요, AI & Data Engineer 구동민입니다! 👋

> **Data & AI Engineer / Backend Developer**  
> 데이터의 검증과 시스템 레벨의 제어 로직을 바탕으로, **LLM과 데이터 파이프라인을 견고한 서비스 API로 연결**합니다.  
> 모호한 추론에 의존하기보다 **SQL 매개변수 바인딩, Pydantic 유효성 검사, 로그 기반 추적**을 통해 안정적이고 재현 가능한 엔지니어링을 지향합니다.

---

## 🛠 Tech Stack

| Category | Technologies |
| :--- | :--- |
| **Languages** | `Python`, `SQL`, `JavaScript (ES6+)`, `HTML5/CSS3` |
| **Backend & APIs** | `FastAPI`, `Pydantic`, `RESTful API`, `HTTP Client Integration` |
| **Data & DB** | `MySQL`, `pandas`, `SQLD`, `빅데이터분석기사` |
| **AI & RAG** | `Gemini REST API`, `Chroma DB`, `LangChain`, `Prompt Engineering` |
| **Testing & Tools** | `pytest` (Mocking & Integration), `Git/GitHub`, `VS Code` |

---

## 🚀 Key Projects

### 1. [Food Commerce AI Assistant](https://github.com/rn1217/food-commerce-ai-assistant)
> **LLM 자연어 조건 파싱 기반 백엔드 검색 & AI 추천 서비스 (Local MVP)**
* **핵심 역할:** FastAPI 기반 검색 API 설계, MySQL 인덱싱 & 매개변수 바인딩 SQL 처리, LLM 환각(Hallucination) 방지용 검증 로직 구현.
* **주요 성과:**
  * LLM 역할을 '조건 JSON 추출'로 한정하고, 실제 DB 조회를 백엔드에서 격리하여 **SQL Injection 위험 차단**.
  * `ai_logs` 테이블 구축으로 고유 `request_id` 기반 지연 시간(Latency) 및 외부 API 오류 추적 체계 마련.
  * 외부 API Mocking 기반 단위/통합 테스트 **60개 항목 100% 통과**.

### 2. [DecaMind - RAG 기반 사내 산업 문서 검색 챗봇](https://github.com/rn1217)
> **산학협력 캡스톤디자인 (오이솔루션 협력)**
* **핵심 역할:** React 프론트엔드 UI 개발, 백엔드 연동 RESTful API 규격 정의, Chroma DB / LangChain 기반 RAG 검색 연계.
* **주요 성과:** 오이솔루션 사내 임직원 대상 무작위 규격 질의 실증 테스트 완료 및 청킹 유실 문제에 대한 메타데이터 필터링 개선점 도출.

---

## 📜 Certifications & Education

* **자격증:**
  * 🏅 **SQLD (SQL 개발자)** - 한국데이터산업진흥원
  * 🏅 **빅데이터분석기사** - 한국데이터산업진흥원
* **교육 및 학력:**
  * 🎓 **KB-Bridge AI & 금융 데이터 분석 과정** (2026.08 ~ 2026.11)
  * 🎓 **전남대학교 인공지능학부 소프트웨어전공 졸업** (2021.03 ~ 2026.08)

---

## ⚙️ Engineering Principles (일하는 방식)

1. **역할 분리를 통한 안정성 확보:** LLM에게 직접 DB 조작을 맡기지 않고, **정형 조건 추출(LLM)과 데이터 조회(SQL/Backend)**의 역할을 엄격히 분리합니다.
2. **로그와 추적 가능성:** 모든 요청에 고유 ID를 부여하고 `ai_logs`에 기록하여 장애 발생 시 재현 가능한 원인 분석 환경을 구축합니다.
3. **체크리스트 기반 검증:** 테스트 케이스 작성과 유효성 검사기(Pydantic/pandas)를 통해 시스템에 들어오는 데이터 결측 및 예외를 사전에 차단합니다.

---

📬 **Contact & Links**
- **Email:** `jokuk88@naver.com`
- **GitHub:** [https://github.com/rn1217](https://github.com/rn1217)
