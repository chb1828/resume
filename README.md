<div align="left">

# Jayce (최현범)
### 🚀 6th Year Server Developer
> "데이터의 올바른 흐름과 성능 최적화를 고민하며, 비즈니스 가치를 기술로 실현합니다."

[![Email Badge](https://img.shields.io/badge/Email-chb1828%40naver.com-c14438?style=flat-square&logo=Gmail&logoColor=white)](mailto:chb1828@naver.com)
[![GitHub Badge](https://img.shields.io/badge/GitHub-@chb1828-181717?style=flat-square&logo=GitHub&logoColor=white)](https://github.com/chb1828)
[![Velog Badge](https://img.shields.io/badge/Blog-Velog-20c997?style=flat-square&logo=Vimeo&logoColor=white)](https://velog.io/@chb1828)
[![Portfolio Badge](https://img.shields.io/badge/Portfolio-Link-blue?style=flat-square)](https://www.bumtfolio.com/)

<br>

## 💁🏻‍♂️ About Me
**Performance-Oriented**
* 불필요한 리소스 낭비를 줄이고, 올바른 흐름 제어를 통해 고성능 서버를 구현하는 데 집중합니다.
* 수치(Metric)에 기반한 의사결정을 선호하며, 인프라 비용 절감과 응답 속도 개선 경험이 있습니다.

**Active Learner**
* Java Reactive Programming, WebFlux 등 새로운 기술 스택을 적극적으로 도입하고 학습합니다.
* 배운 내용을 블로그에 정리하고 공유하며 함께 성장하는 문화를 지향합니다.

<br>

## 🛠 Tech Stack
| Category | Skills |
| :--- | :--- |
| **Backend** | ![Java](https://img.shields.io/badge/Java-007396?style=flat-square&logo=Java&logoColor=white) ![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=flat-square&logo=Kotlin&logoColor=white) ![Spring Boot](https://img.shields.io/badge/SpringBoot-6DB33F?style=flat-square&logo=SpringBoot&logoColor=white) ![JPA](https://img.shields.io/badge/JPA-59666C?style=flat-square) |
| **Database** | ![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=MySQL&logoColor=white) ![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=Redis&logoColor=white) ![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=MongoDB&logoColor=white) |
| **DevOps** | ![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=AmazonAWS&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=Docker&logoColor=white) ![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=GitHub-Actions&logoColor=white) |
| **Search** | ![Elasticsearch](https://img.shields.io/badge/Elasticsearch-005571?style=flat-square&logo=Elasticsearch&logoColor=white) ![OpenSearch](https://img.shields.io/badge/OpenSearch-005E7C?style=flat-square&logo=Opensearch&logoColor=white) |

<br>

## 💼 Work Experience

### 🏢 Dreamus Company (드림어스컴퍼니)
**Backend Developer** | *2022.04 ~ 현재*

#### 1. 신사업 티켓 프로젝트 VOC 시스템 개발 (2024.03 ~ 2024.05)
* **Role:** FLO 신규 티켓 사업의 1:1 문의, 상담 메모, 카테고리 관리 등 VOC(Voice of Customer) 전체 기능 모델링 및 개발.
* **Problem:** 문의 내역 전체 버전을 Grouping하여 조회 시 Full Scan 방지 이슈 발생.
* **Solution:** JPA와 Hibernate의 심도 있는 활용 및 쿼리 최적화로 성능 개선.

#### 2. CMS 검색 엔진 도입 및 성능 개선 (2023.07 ~ 2024.02)
* **Problem:** 8,500만 곡 이상의 데이터로 인해 CMS 관리자 곡 검색 시 15초 이상의 Timeout 발생.
* **Solution:** **OpenSearch(검색 엔진)** 도입 및 데이터 구조 최적화.
* **Result:** 검색 속도 1초 미만으로 단축 및 타임아웃 이슈 해결.

#### 3. FLO Moood(무드) 서비스 개발 (2023.06 ~ 2023.10)
* **Description:** YouTube Shorts와 유사한 숏폼 형태의 플레이리스트 미리듣기 서비스 개발.
* **Tech Focus:** 끊김 없는 데이터 서빙을 위한 **Caching 전략** 설계 및 적용.

#### 4. '듣템' 프로모션 이벤트 개발 (2022.07 ~ 2022.10)
* **Challenge:** 선착순 이벤트 트래픽 급증 시 중복 응모(따닥 이슈) 발생.
* **Solution:** **Redis Distributed Lock**을 도입하여 동시성 제어 및 데이터 무결성 보장.

<br>

### 🏢 (주)리턴트루
**Backend Developer** | *2020.03 ~ 2022.02*

#### 1. Wellvoice 관리자 웹 & 서버 개발 (2021.08 ~ 2021.12)
* **Description:** 문장을 입력하면 지정된 시간에 AI 보이스로 송출하는 예약 시스템.
* **Action:** Naver Clova TTS 연동 및 **Socket 통신**을 활용한 실시간 오디오 스케줄링 구현.

#### 2. Secuwifi 관리자 웹 & 서버 리팩토링 (2021.03 ~ 2021.07)
* **Action:** Spring Legacy → **Spring Boot 마이그레이션** 및 MyBatis 도입으로 유지보수성 향상.

<br>

## 💻 Personal Projects
### 📈 업비트 급등 코인 알림 서비스
*2021.10 ~ 2021.12*
* **Stack:** `Kotlin`, `Spring WebFlux`
* **Feature:** 업비트 WebSocket 실시간 데이터 수신 및 슬랙 알림 전송.
* **Key Learning:** **Non-blocking I/O** 및 Backpressure(배압) 처리를 통한 대용량 데이터 안정성 확보.

<br>

## 🏆 Education & Awards
* **2024.06** | FLO Tech Town Hall Developer Award (신사업 공로)
* **2020.01** | 캡스톤 디자인 졸업작품 은상
* **2014 ~ 2020** | 경기과학기술대학교 컴퓨터모바일융합과 졸업

</div>
