# 최현범 (Jayce)
> "데이터의 올바른 흐름과 성능 최적화를 고민하며, 비즈니스 가치를 기술로 실현하는 서버 개발자입니다."

[![Email Badge](https://img.shields.io/badge/Email-chb1828%40naver.com-c14438?style=flat-square&logo=Gmail&logoColor=white)](mailto:chb1828@naver.com)
[![GitHub Badge](https://img.shields.io/badge/GitHub-chb1828-181717?style=flat-square&logo=GitHub&logoColor=white)](https://github.com/chb1828)
[![Velog Badge](https://img.shields.io/badge/Tech%20Blog-Velog-20c997?style=flat-square&logo=Vimeo&logoColor=white)](https://velog.io/@chb1828)

---

## 🚀 Introduce
* **Performance-Oriented**
    * 불필요한 자원 낭비를 줄이고 올바른 흐름 제어를 통해 성능 및 문제 없는 서버를 구현하기 위해 노력합니다.
    * 수치(Metric)에 기반한 의사결정을 선호하며, 인프라 비용 절감과 응답 속도 개선 경험이 있습니다.
* **Active Learner**
    * Java Reactive Programming, WebFlux 등 새로운 기술에 거부감 없이 적극적으로 학습하고 도입합니다.
    * 배운 내용을 블로그에 정리하고 공유하며 함께 성장하는 문화를 지향합니다.
* **Communication**
    * 반대표, 선거관리위원회 등 다양한 조직 활동 경험을 통해 원활한 소통 능력을 길러왔습니다.
    * 명확한 의견 전달과 경청을 통해 팀의 목표 달성에 기여합니다.

---

## 🛠 Skills
* **Backend**
  * Java, Kotlin
  * Spring Boot, Spring Data JPA, MyBatis, Spring WebFlux
* **Database**
  * MySQL, MongoDB, Redis, PostgreSQL
* **Search Engine**
  * Elasticsearch, OpenSearch
* **Infrastructure & Tools**
  * AWS (EC2, RDS), Docker, Linux
  * Git, GitHub, IntelliJ IDEA

---

## 💼 Experience

### 드림어스컴퍼니 (Dreamus Company)
**Backend Developer**
*2022.04 ~ 현재*

#### 1. 신사업 티켓 프로젝트 VOC 시스템 개발
*2024.03 ~ 2024.05*

> **Description:**
> FLO 신규 티켓 사업의 1:1 문의, 상담 메모, 카테고리 관리 등 VOC(Voice of Customer) 전체 기능을 모델링하고 개발했습니다.

* **What did I do**
    * **도메인 주도 설계 및 모델링:** 10개 이상의 테이블이 얽힌 복잡한 상담 카테고리 및 문의 내역 구조를 JPA 기반으로 설계하여 데이터 무결성 확보
    * **조회 성능 최적화:** 문의 내역의 전체 버전 Grouping 조회 시 발생한 Full Scan 문제를 인덱싱 및 쿼리 최적화로 해결하여 응답 속도 개선
    * **Hibernate 심화 활용:** 초기 단계부터 JPA/Hibernate를 깊이 있게 활용하여 비즈니스 로직과 데이터 접근 계층을 효율적으로 분리

* **Tech Stack**
    * Java, Spring Boot, JPA, MySQL

#### 2. CMS 검색 엔진 도입 및 성능 개선
*2023.07 ~ 2024.02*

> **Description:**
> 8,500만 곡 이상의 음원 데이터를 관리하는 CMS에서 발생한 검색 타임아웃(15초 이상) 문제를 해결하기 위해 검색 엔진을 도입했습니다.

* **What did I do**
    * **OpenSearch(검색 엔진) 도입:** 기존 RDB 기반의 검색 로직 한계를 극복하기 위해 OpenSearch 도입 및 데이터 동기화 파이프라인 구축
    * **검색 로직 고도화:** 색인된 데이터 구조에 맞춰 Elasticsearch Query(DSL)를 Java 코드로 정교하게 구현하여 정확도 향상 및 타임아웃 이슈 완전 해결

* **Tech Stack**
    * Java, Spring Boot, OpenSearch(Elasticsearch)

#### 3. FLO Moood(무드) 서비스 개발
*2023.06 ~ 2023.10*

> **Description:**
> YouTube Shorts와 유사한 UX를 가진 숏폼 형태의 플레이리스트 미리듣기 서비스를 신규 개발했습니다.

* **What did I do**
    * **캐싱(Caching) 전략 수립:** 서비스 중지(Take down)된 음원을 제외하고 유효한 곡만 빠르게 서빙하기 위해 Redis 기반 캐싱 레이어 설계
    * **UX 최적화:** 스크롤 기반 UI에서 끊김 없는 데이터 제공을 위해 응답 속도를 최적화하고 대용량 트래픽 처리를 위한 구조 개선

* **Tech Stack**
    * Java, Spring Boot, Redis, MongoDB

#### 4. '듣템' 프로모션 이벤트 개발
*2022.07 ~ 2022.10*

> **Description:**
> 청취 시간에 따라 경품에 응모하는 선착순/조건 달성형 대규모 프로모션 이벤트를 개발했습니다.

* **What did I do**
    * **동시성 이슈(Concurrency) 제어:** 트래픽 급증 시 발생할 수 있는 중복 응모(따닥 이슈)를 **Redis Distributed Lock**을 도입하여 해결
    * **안정성 확보:** 이벤트 기간 동안 데이터 정합성을 보장하며 안정적인 서비스 운영 달성

* **Tech Stack**
    * Java, Spring Boot, Redis

<br>

### (주)리턴트루
**Backend Developer**
*2020.03 ~ 2022.02*

#### 1. Wellvoice 관리자 웹 & 서버 개발
*2021.08 ~ 2021.12*

> **Description:**
> 텍스트를 입력하면 지정된 시간에 AI 보이스로 송출해주는 안내 방송 예약 시스템입니다.

* **What did I do**
    * **Naver Clova API 연동:** 외부 TTS API를 연동하여 텍스트-음성 변환 기능 구현 및 송출 시스템 구축
    * **Socket 통신 구현:** Windows 클라이언트(방송 송출 PC)와 서버 간의 실시간 스케줄링 동기화 및 오디오 파일 전송 로직 개발

* **Tech Stack**
    * Java, Spring Boot, WebSocket

#### 2. Secuwifi 관리자 웹 & 서버 리팩토링
*2021.03 ~ 2021.07*

> **Description:**
> 원클릭 와이파이 자동 연결 서비스의 레거시 관리자 시스템을 리팩토링했습니다.

* **What did I do**
    * **Legacy Migration:** 기존 Spring Framework 프로젝트를 Spring Boot로 마이그레이션하여 모던한 개발 환경 구축
    * **MyBatis 전환:** 유지보수가 어려운 DB 프로시저 로직을 MyBatis로 전환하여 비즈니스 로직을 애플리케이션 레벨에서 관리하도록 개선
    * **UI/UX 개편:** 유료 템플릿을 활용하여 관리자 웹 UI를 전면 재구성

* **Tech Stack**
    * Java, Spring Boot, MyBatis

---

## 💻 Personal Projects

### 📈 업비트 급등 코인 알림 서비스
*2021.10 ~ 2021.12*

> **Description:**
> 업비트 WebSocket 데이터를 실시간으로 수신하여 급등 코인을 감지하고 슬랙으로 알림을 전송하는 토이 프로젝트입니다.

* **What did I do**
    * **Reactive Programming 도입:** Spring MVC가 아닌 **Spring WebFlux**를 도입하여 Non-blocking I/O 기반의 대용량 실시간 데이터 처리 학습
    * **Backpressure(배압) 해결:** 3개의 소켓 스트림 처리 중 발생한 배압 문제를 리액티브 오퍼레이터로 제어하며 시스템 안정성 확보

* **Tech Stack**
    * Kotlin, Spring WebFlux

---

## 🏆 Education & Awards
* **FLO Tech Town Hall Developer Award** (2024.06) - 신사업 공로 인정
* **캡스톤 디자인 졸업작품 은상** (2020.01) - 웹 크롤러 및 감정 분석 시스템
* **창업 리그 은상** (2019.01) - OCR 기반 이미지 분석 프로젝트
* **경기과학기술대학교** 컴퓨터모바일융합과 졸업 (2014.03 ~ 2020.01)
