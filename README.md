# 💻 Server Developer | 최현범
> "데이터의 올바른 흐름과 성능 최적화를 고민하며, 비즈니스 가치를 기술로 실현하는 개발자입니다."

[![Email Badge](https://img.shields.io/badge/Email-chb1828%40naver.com-c14438?style=flat-square&logo=Gmail&logoColor=white)](mailto:chb1828@naver.com)
[![Velog Badge](https://img.shields.io/badge/Tech%20Blog-Velog-11B48A?style=flat-square&logo=Vimeo&logoColor=white)](https://velog.io/@chb1828)
[![GitHub Badge](https://img.shields.io/badge/GitHub-chb1828-181717?style=flat-square&logo=GitHub&logoColor=white)](https://github.com/chb1828)
[![Portfolio Badge](https://img.shields.io/badge/Portfolio-Link-blue?style=flat-square)](https://www.bumtfolio.com/)

---

## 🚀 Introduction
* [cite_start]**Performance-Oriented:** 불필요한 리소스 낭비를 줄이고, 올바른 흐름 제어를 통해 고성능 서버를 구현하는 데 집중합니다[cite: 4, 5].
* [cite_start]**Active Learner:** Java Reactive Programming 및 WebFlux 등 새로운 기술 스택을 적극적으로 도입하고 학습합니다[cite: 6, 7].
* [cite_start]**Communication:** 반대표, 선거관리위원 등 다양한 조직 활동 경험을 바탕으로 원활한 협업과 명확한 의사소통을 지향합니다[cite: 8, 116, 120].

---

## 🛠 Tech Stack
### Backend
* **Language:** Java, Kotlin, C#
* **Framework:** Spring Boot, Spring Data JPA, MyBatis, Spring WebFlux
* **Database:** MySQL, PostgreSQL, MongoDB, Redis
* **Search Engine:** Elasticsearch, OpenSearch

### Infra & Tools
* **DevOps:** AWS, Docker, Linux
* **Version Control:** Git, GitHub

---

## 💼 Work Experience

### 🏢 Dreamus Company (드림어스컴퍼니)
*Backend Developer | 2022.04 ~ 현재*

**1. [cite_start]신사업 티켓 프로젝트 VOC 시스템 개발 (2024.03 ~ 2024.05)** [cite: 20, 21]
* **Role:** FLO 신규 티켓 사업의 1:1 문의, 상담 메모, 카테고리 관리 등 VOC(Voice of Customer) 전체 기능 모델링 및 개발.
* [cite_start]**Challenge:** 10개 이상의 테이블이 연관된 복잡한 도메인 구조 설계 필요[cite: 23]. [cite_start]문의 내역 전체 버전을 Grouping하여 조회 시 Full Scan 방지 이슈 발생[cite: 25].
* **Action & Tech:**
    * [cite_start]JPA와 Hibernate의 심도 있는 활용을 통해 객체 지향적인 데이터 모델링 구현[cite: 24].
    * 복잡한 연관 관계를 효율적으로 조회하기 위한 쿼리 최적화 및 인덱싱 전략 수립.

**2. [cite_start]CMS 검색 엔진 도입 및 성능 개선 (2023.07 ~ 2024.02)** [cite: 31, 32]
* [cite_start]**Problem:** 8,500만 곡 이상의 데이터로 인해 CMS 관리자 곡 검색 시 15초 이상의 Timeout 발생[cite: 33].
* [cite_start]**Solution:** 기존 DB 검색 방식을 **OpenSearch(검색 엔진)** 도입으로 전환[cite: 34].
* **Action:**
    * [cite_start]색인된 데이터 구조에 최적화된 Elasticsearch Query를 Java로 구현하여 검색 로직 고도화[cite: 35].
* **Result:** 검색 속도 획기적 단축 및 타임아웃 이슈 해결.

**3. [cite_start]FLO Moood(무드) 서비스 개발 (2023.06 ~ 2023.10)** [cite: 26, 27]
* [cite_start]**Description:** YouTube Shorts와 유사한 숏폼 형태의 플레이리스트 미리듣기 서비스 개발[cite: 28].
* **Tech Focus:**
    * [cite_start]사용자 경험(UX) 향상을 위해 스크롤 시 끊김 없는 데이터 서빙이 필수적임[cite: 29].
    * [cite_start]Take down(서비스 중지)된 음원을 제외하고, 유효한 미리듣기 곡을 빠르게 제공하기 위한 **Caching 전략** 설계 및 적용[cite: 30].

**4. [cite_start]'듣템' 프로모션 이벤트 개발 (2022.07 ~ 2022.10)** [cite: 36, 37]
* [cite_start]**Challenge:** 선착순/조건 달성형 이벤트 특성상 트래픽 급증 시 중복 응모(따닥 이슈) 발생 가능성 존재[cite: 39, 40].
* [cite_start]**Solution:** **Redis Distributed Lock**을 도입하여 동시성 이슈 제어 및 데이터 무결성 보장[cite: 40].

<br>

### 🏢 (주)리턴트루
*Backend Developer | 2020.03 ~ 2022.02*

**1. [cite_start]Wellvoice 관리자 웹 & 서버 개발 (2021.08 ~ 2021.12)** [cite: 43, 44]
* **Description:** 문장을 입력하면 지정된 시간에 AI 보이스로 송출하는 예약 시스템.
* **Action:**
    * [cite_start]Naver Clova API 연동을 통한 TTS 기능 구현[cite: 46].
    * [cite_start]**Socket 통신**을 활용하여 Window Client에 실시간 데이터 생성/변경 알림 전송 및 오디오 스케줄링 구현[cite: 47].

**2. [cite_start]Secuwifi 관리자 웹 & 서버 리팩토링 (2021.03 ~ 2021.07)** [cite: 49, 50]
* **Challenge:** 기존 Spring Legacy 프로젝트의 노후화 및 유지보수 어려움.
* **Action:**
    * [cite_start]**Spring Boot로 마이그레이션** 진행 및 DB 프로시저 로직을 **MyBatis**로 전환하여 코드 가독성 및 유지보수성 향상[cite: 52].
    * [cite_start]유료 템플릿을 활용한 UI/UX 전면 재구성[cite: 53].

**3. [cite_start]BAMS (생체인증 통합 보안 관리) 웹 개발 (2020.06 ~ 2020.12)** [cite: 55, 56]
* [cite_start]**Role:** 장정맥, 지문 등 생체 정보를 활용한 4단계(출입-PC-APP-암복호화) 인증 시스템의 관리자 웹 개발[cite: 57, 58].

---

## 💻 Personal Projects & Challenge

### [cite_start]📈 업비트 급등 코인 알림 서비스 (2021.10 ~ 2021.12) [cite: 62, 63]
* **Description:** 업비트 소켓 데이터를 실시간으로 수신하여 급등 코인을 감지하고 슬랙으로 알림을 전송하는 서버.
* **Tech Stack:** Spring WebFlux, Reactive Programming
* **Key Learning:**
    * [cite_start]Spring MVC가 아닌 **Non-blocking I/O** 방식의 WebFlux를 도입하여 대용량 실시간 데이터 처리 경험[cite: 65, 66].
    * [cite_start]3개의 소켓 스트림을 처리하며 발생한 **Backpressure(배압)** 문제를 해결하며 리액티브 시스템의 안정성 확보[cite: 67].

### [cite_start]🍰 슈가파우더 (D-Day 커뮤니티 앱) [cite: 70, 72]
* **Tech:** Flutter, Firebase
* [cite_start]**Role:** Beside 프로젝트 팀원으로 참여, D-Day 공유 및 소통 기능을 갖춘 앱 서비스 전체 개발[cite: 73, 74].

---

## 🏆 Awards & Education
* [cite_start]**FLO Tech Town Hall Developer Award** (2024.06) - 신사업 공로 인정 [cite: 101, 104]
* [cite_start]**캡스톤 디자인 졸업작품 은상** (2020.01) - 웹 크롤러 및 감정 분석 시스템 [cite: 105, 108]
* [cite_start]**창업 리그 은상** (2019.01) - OCR 기반 이미지 분석 프로젝트 [cite: 110, 112]
* [cite_start]**경기과학기술대학교** 컴퓨터모바일융합과 졸업 (2014.03 ~ 2020.01) [cite: 83, 85]
