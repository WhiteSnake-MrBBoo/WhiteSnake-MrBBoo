<div align="center">
  <h1>BUHWAN KIM · WhiteSnake-MrBBoo</h1>
  <h3>AI & Automation Backend Engineer · 백오피스 · Vision AI · RPA</h3>
</div>

<div align="center">

  <!-- Tech Belt -->
  <img src="https://img.shields.io/badge/Java-21-007396?logo=openjdk&logoColor=white" />
  <img src="https://img.shields.io/badge/Spring%20Boot-3.x-6DB33F?logo=springboot&logoColor=white" />
  <img src="https://img.shields.io/badge/Python-3.x-3776AB?logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/Flask-Backend-000000?logo=flask&logoColor=white" />
  <img src="https://img.shields.io/badge/MariaDB-DB-003545?logo=mariadb&logoColor=white" />
  <img src="https://img.shields.io/badge/YOLO-v11-00FFFF?logo=github&logoColor=black" />
  <img src="https://img.shields.io/badge/UiPath-RPA-2578F6?logo=uipath&logoColor=white" />
  <img src="https://img.shields.io/badge/Tesseract-OCR-4B8BBE?logo=tesseract&logoColor=white" />
  <img src="https://img.shields.io/badge/OpenAI-API-412991?logo=openai&logoColor=white" />
  <img src="https://img.shields.io/badge/Bootstrap-5-7952B3?logo=bootstrap&logoColor=white" />
  <img src="https://img.shields.io/badge/GitHub-Portfolio-181717?logo=github&logoColor=white" />

</div>

---

## 한 줄 소개

> 사람 손이 많이 가는 백오피스·운영 업무를  
> **Spring Boot · Python · RPA · AI(Vision/OCR/LLM)** 로 자동화하는 엔지니어입니다.

- 비즈니스 플로우를 먼저 이해하고,  
  그 위에 **백엔드·RPA·AI 파이프라인**을 얹어서 “매일 쓰는 도구”를 만드는 것을 지향합니다.  
- 단순 데모가 아니라, **운영 화면 · 엑셀 리포트 · 알림까지 끝까지 설계**하는 스타일입니다.

---

## 대표 작업 축 (What I build)

### 1. 백오피스 · 내부 도구

- **T-Commerce · OCR + GPT 백오피스**  
  상품 기술서(이미지·PDF)를 Tesseract-OCR로 텍스트화하고,  
  GPT로 쇼호스트 멘트/상품 요약/마케팅 포인트를 생성한 뒤  
  DB·Excel로 관리하는 백오피스.  
  → 반복적인 카피·요약 작업을 자동화하고, AI 사용량/토큰도 추적 가능한 구조.  
  → Repo: [bboo_technology](https://github.com/WhiteSnake-MrBBoo/bboo_technology)

- **직업상담 행정망 + AI Career Advisor**  
  공공 데이터 기반 직업 정보 + 프로필 데이터를 묶어서  
  진로 추천/상담을 도와주는 웹 애플리케이션.  
  → 행정망 스타일의 정보 구조 위에 AI 분석을 더하는 실험.  
  → Repo: [aicareeradvisor](https://github.com/WhiteSnake-MrBBoo/aicareeradvisor)

- **Excel 기반 구성/설정 자동화**  
  Java + Apache POI로 엑셀을 “설정 관리 도구”처럼 사용.  
  → 대량 설정·코드 템플릿을 엑셀에서 정의하고, 서버에서 자동 반영.  
  → Repo: [excel_config](https://github.com/WhiteSnake-MrBBoo/excel_config)

---

### 2. Vision AI · 실시간 대시보드

- **CCTV Vision AI Dashboard**  
  Python + Ultralytics YOLO + OpenCV + Flask 기반.  
  폴리곤 Region 단위로 객체를 카운팅/알림하고,  
  실시간 차트/알림 패널/반응형 UI까지 한 화면에 묶은 프로젝트.  
  → 단순 “모델 정확도”보다, **운영자가 하나의 화면에서 상황을 읽고 결정하게 만드는 UI/UX**에 집중.  
  → 상세 스토리: [information_portfolio – CCTV Vision AI](https://github.com/WhiteSnake-MrBBoo/information_portfolio)

---

### 3. RPA · STT · LLM 파이프라인

- **UiPath + ChatGPT 리뷰 요약 파이프라인**  
  Blind/리뷰 텍스트를 긍정/부정/결론 3축으로 요약하고,  
  Dt_Blind_Ai_Result 스키마로 정리해 Excel로 내보내는 RPA 플로우.  
  → 대량 텍스트 분석 리드타임을 줄이고, 프롬프트·파이프라인을 표준화.

- **로컬 STT + LLM 연동 실험 (GPU)**  
  Python에서 로컬 STT 엔진(faster-whisper 등)을 돌리고,  
  Spring Boot와 연동해 “음성 → 텍스트 → AI 처리” 파이프라인을 구축.  
  → Repo: [llm_gpu](https://github.com/WhiteSnake-MrBBoo/llm_gpu)

---

### 4. 팀 프로젝트 · HexaStay (호텔 관리자 ERP)

- Spring Boot 3.4 + MariaDB + Thymeleaf로 호텔 ERP 생태계를 구축.  
- 객실/회원/예약, QR 인증, 이메일 발송, WebSocket 기반 알림,  
  고급 관리자 대시보드(블랙/골드 HexaStay Admin 컨셉)까지 설계.  
- 하나의 roomlist.html을 상태별(체크인/체크아웃/표시/숨김)로 재사용하는 구조 등  
  **재사용성과 유지보수성**에 신경 쓴 아키텍처.  

→ 상세 소개와 PPT 링크: [information_portfolio](https://github.com/WhiteSnake-MrBBoo/information_portfolio)

---

## Tech Stack

| 영역 | 주요 기술 |
|------|-----------|
| Backend | Java 21, Spring Boot 3.x, Spring Data JPA, Thymeleaf, ModelMapper, Validation, Spring Mail |
| Data / Infra | MariaDB, JPA, Query 설계, AWS(기본 서비스 활용), Apache POI(Excel) |
| Vision / ML | Python 3.x, Ultralytics YOLO v5–v11, OpenCV, Flask, Socket.IO, Threading |
| RPA | UiPath, VB.NET Invoke Code, Newtonsoft JSON, Excel Activities |
| AI / LLM | OpenAI API, GPT 계열 모델, Prompt 설계, 비용/토큰 모니터링 설계 |
| Frontend | HTML5, CSS3, Bootstrap 5, JavaScript, jQuery, Ajax/Fetch, Canvas 기반 UI |
| Tools | IntelliJ IDEA, Git & GitHub, HeidiSQL, MobaXterm, Linux 환경 |

---

## 지금 집중하는 것 (Now)

- **실제 조직에서 바로 쓸 수 있는 AI + Automation 도구**  
  - OCR/STT/LLM을 기존 업무 흐름에 자연스럽게 녹이는 방법  
  - Vision AI를 “알람과 의사결정 UI”로 설계하는 패턴  
- **내부 운영자를 위한 대시보드 & 백오피스 UX**  
  - HexaStay Admin 컨셉처럼,  
    데이터·알람·필터·Excel Export가 한 화면에서 자연스럽게 연결되는 구조.
- **표준화된 파이프라인**  
  - Prompt, 모델 설정, Excel/리포트 구조를 템플릿화해서  
    다른 도메인에도 반복 적용할 수 있는 프레임워크 만들기.

---

## 더 보기 & 연락

- 상세 포트폴리오 및 케이스 스터디:  
  → [information_portfolio](https://github.com/WhiteSnake-MrBBoo/information_portfolio)
- 대표 AI 백오피스 프로젝트:  
  → [bboo_technology](https://github.com/WhiteSnake-MrBBoo/bboo_technology)
- Email: **mrbulsapabb@gmail.com**

> “새로운 업무 흐름을 자동화하거나, Vision/OCR/LLM을 서비스에 녹이고 싶다면  
>  언제든지 코드와 아키텍처로 이야기할 준비가 되어 있습니다.”
