<!--**[![Typing SVG](https://readme-typing-svg.herokuapp.com?font=Poppins&weight=700&height=70&size=40&pause=500&color=fcee2a&background=FFFFFF00&width=900&lines=Hi,+I'm+Yun+Seo!+🤩)](https://git.io/typing-svg)**
[![Typing SVG](https://readme-typing-svg.herokuapp.com?font=Roboto&weight=400&size=20&pause=500&color=FFFFFF&background=00000000&width=600&lines=안녕하세요.+성장을+즐기는+개발자+최윤서입니다.)](https://git.io/typing-svg)-->

## 👋 INTRODUCTION
- **Name** :&nbsp;&nbsp;최윤서
- **Birth** : &nbsp;&nbsp;2002.01.29
- **University** :&nbsp;&nbsp;상명대학교 소프트웨어학과 (졸업)
- **Email** :&nbsp;&nbsp;choeyusneo4060@naver.com
- **Tech Blog** :&nbsp;&nbsp;[Yunseo's velog](https://velog.io/@choeyunseo/series)
<!-- - **Birth** : &nbsp;&nbsp;2002.01.29 -->
<br>

<!--# 🎓 EDUCATION
- **상명대학교 소프트웨어학과** (**4.03**/4.5) <br>
2022.03 ~ 2026.02 (졸업) <br>
- **천안여자고등학교** <br>
2018.03 ~ 2021.02 (졸업)
<br>-->

## 💻 PROJECT

### **Baton - 크레딧 · 에스크로 기반 1:1 안전 재능 교환 플랫폼**
> `2026.06 ~ 2026.07(4주)` · `프로그래머스 데브코스 5인 프로젝트` · `백엔드 개발` · [GitHub](https://github.com/YunseoChoe/Baton-backend)

<!--
- **기간**: 2026.06 ~ 2026.07 (4주)
- **기관**: 프로그래머스 데브코스
- **인원**: 5명 (BE 5)
- **역할**: 백엔드
- **기술 스택**: Java, Spring Boot, JPA, Spring Security·JWT, Next.js, MySQL, EC2, Docker, GitHub Actions, JUnit, JaCoCo, k6, Prometheus, Grafana
- **GitHub**: BatonBE
-->

- 가상 화폐(Credit) 및 에스크로 기반 안전 결제 시스템 설계 및 구현
- 원자적 업데이트를 활용한 크레딧 결제 동시성 제어로 처리량 **2.6배 향상** 및 평균 응답 속도 **83.3% 단축**
- 커서 기반 페이징(No-Offset)을 적용하여 거래 내역 조회 성능 최적화
- AWS S3 Presigned URL을 도입하여 파일 업로드 트래픽 분산 및 서버 부하 최소화
- JaCoCo 기반 테스트 코드 작성 및 Line Coverage **87%**, Branch Coverage **74%** 달성

<br>

### **RunGo - 대규모 트래픽과 동시성 제어를 고려한 마라톤 대회 주최 · 접수 플랫폼**
> `2026.04 ~ 2026.05(6주)` · `프로그래머스 데브코스 5인 프로젝트` · `팀장 & 백엔드 개발` · `12개 팀 중 우수상 수상` · [GitHub](https://github.com/YunseoChoe/RunGo-backend-kotlin)
<!--
- **기간**: 2026.04 ~ 2026.05 (6주)
- **기관**: 프로그래머스 데브코스
- **인원**: 5명 (BE 5)
- **역할**: 팀장, 백엔드
- **BackEnd GitHub**: RunGoBE
- **FrontEnd GitHub**: 
-->

- Spring Security · JWT(Access & Refresh) 기반 인증 · 인가 시스템 구축
- Redis 기반 Refresh Token 관리 및 RTR(Rotate Refresh Token) 보안 체계 적용
- Redis 분산 락을 활용한 토큰 재발급 동시성 제어 구현
- k6 부하 테스트를 통해 30 VU 환경에서 **p95 75ms, 에러율 0%** 검증
- Java → Kotlin 마이그레이션을 수행하여 Null Safety 적용 및 유지보수성 개선
<!-- - 전자상거래법 보존 정책을 고려한 사용자 데이터 관리 및 개인정보 자동 파기 시스템 구현 -->

<br>

### **우아정 - AI 기반 안심 중고 거래 플랫폼**
> `2025.04 ~ 2025.06(10주)` · `상명대학교 캡스톤디자인 3인 프로젝트` · `백엔드 개발` · [GitHub](https://github.com/YunseoChoe/Wooajeong-backend)
<!--
- **기간**: 2025.04 ~ 2025.06 (3개월)
- **기관**: 상명대학교 캡스톤 디자인
- **인원**: 3명 (AI 1, BE 1, FE 1)
- **역할**: Backend Developer
- **GitHub**: wooajeongBE
-->

- EC2 ·  Docker · GitHub Actions 기반 CI/CD 파이프라인 구축 및 배포 자동화
- RabbitMQ · STOMP를 활용한 실시간 비동기 채팅 시스템 설계 및 구현
- 채팅 데이터 저장소를 MySQL(채팅방 정보) · MongoDB(채팅 메시지)로 분리하여 메시지 저장 성능 개선
  <!--
  - **10,424ms → 132ms (약 79배 개선)**
  - **959 TPS → 75,758 TPS**
  -->
- OAuth 2.0 기반 소셜 로그인 시스템 구축

<br>

### **댓칼코마니 - 웹툰 작가와 독자들 간의 긍정적 소통 지원 플랫폼**
> `2024.03` · `Kakao x 9oormthon 7인 프로젝트` · `백엔드 개발` · [GitHub](https://github.com/YunseoChoe/2024_BEOTKKOTTHON_TEAM_37_BE)

- JWT 기반 인증 · 인가 시스템을 구축하여 안전한 사용자 인증 및 접근 제어 체계 구현
- 서비스 요구사항 기반 ERD 설계 및 GCP 환경 MySQL 서버 구축
- Puppeteer 기반 실시간 댓글 크롤링 시스템 구현

<!--- ### **AI 기반 그림 분석을 통한 심리치료 서비스 (Web)** (2024.12)  
- **AI 모델 구축**
  * HTP(집, 나무, 사람) 검사 데이터를 기반으로 심리 상태를 진단하는 AI 모델 설계 및 구현
- **멀티모달 데이터 분석**
  * 수집한 생체 데이터(심박수, 호흡, 표정)와 AI 분석 결과를 결합하여 정서 상태 파악
- **웹 FE 개발**
  * React.js를 활용해 사용자 친화적인 웹 인터페이스 구현, AI 분석 결과 및 학습 계획 제공-->

<!--
- ### **공동 여행 계획 서비스 (Web)** (2024.09 ~ 2024.12)

#### 주요 기능
* WebSocket을 활용한 실시간 기능 구현
  <!--* 사용자 간 실시간 메시지 송수신, 준비물 체크리스트, 친구 초대 및 퇴장, 정산 기능 구현-->

<!--
* Vercel을 통한 CI/CD 파이프라인 구축 및 배포 자동화 경험
* [트립메이트 FE Repository](https://github.com/YunseoChoe/tripmate-frontend)
<br>
-->

<!--
### **웹툰 작가와 독자들 간의 긍정적인 소통을 지원하는 서비스 (Web)** (2024.03)

#### 주요 기능
* Puppeteer 기반 실시간 댓글 크롤링
* ERD 설계, GCP(Google Cloud Platform) 환경에서 MySQL 서버 구축
* JWT를 활용한 인증/인가 미들웨어 작성으로 안전한 사용자 인증 체계 확립
* 로그인 및 회원가입 등 회원 관리
* [댓칼코마니 BE Repository](https://github.com/YunseoChoe/2024_BEOTKKOTTHON_TEAM_37_BE)
<br>

-->

<!--
  – Role: `BackEnd` <br>
  – Skills: 
  – Detail: [댓칼코마니 BE Repository](https://github.com/YunseoChoe/2024_BEOTKKOTTHON_TEAM_37_BE)
<br>
-->

<br>

## 🔨 SKILLS
#### [ BackEnd ]
<img src="https://smartcart-s3-bucket.s3.ap-northeast-2.amazonaws.com/badge_SpringBoot.svg" alt="[ Spring Boot ]"/> <img src="https://img.shields.io/badge/Spring_Security-6DB33F?style=flat-square&logo=Spring-Security&logoColor=white"/> <br>
<img src="https://img.shields.io/badge/JWT-000000?style=flat-square&logo=JSON-Web-Tokens&logoColor=white"/> <img src="https://img.shields.io/badge/JPA-59666C?style=flat-square&logo=Hibernate&logoColor=white"/>

#### [ Database ]
<img src="https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=MySQL&logoColor=white"/> <img src="https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=MongoDB&logoColor=white"/> <img src="https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=Redis&logoColor=white"/>


#### [ Infra & DevOps ]
<img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=Docker&logoColor=white"/> <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=GitHub-Actions&logoColor=white"/> <br>
<img src="https://smartcart-s3-bucket.s3.ap-northeast-2.amazonaws.com/badge_AmazonAWS.svg" alt="[ Amazon AWS ]"/> 

<!--
#### [ Test & Monitoring ]
<img src="https://img.shields.io/badge/JUnit5-25A162?style=flat-square&logo=JUnit5&logoColor=white"/> <img src="https://img.shields.io/badge/k6-7D64FF?style=flat-square&logo=k6&logoColor=white"/> <img src="https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=Prometheus&logoColor=white"/> <img src="https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=Grafana&logoColor=white"/>
-->

#### [ Language ]
<img src="https://img.shields.io/badge/Java-007396?style=flat-square&logo=openjdk&logoColor=white"/> <img src="https://img.shields.io/badge/Kotlin-7F52FF?style=flat-square&logo=Kotlin&logoColor=white"/> <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=Python&logoColor=white"/>

<br>

## ✨ EXPERIENCES
<!--
| 활동명 | 주관 |  기간 | 내용 | 비고 |
|---|:---:|:---:|:---:|:---:|
| 첨단분야 혁신융합대학사업 서포터즈 | 한국연구재단 | 2024.04 ~ 2025.02 | 서포터즈 | [수료증](https://github.com/user-attachments/assets/21e6d772-406b-49f9-8132-71b783f3c260) |
| Kakao x 9oormthon Univ 2기 | goorm | 2024.02 ~ 2024.08 | 백엔드 | [수료증](https://github.com/user-attachments/assets/a0c5d906-5ae5-4a7d-9d87-d3241b676264) |
| 멋쟁이 사자처럼 대학 11기 | LIKELION | 2023.03 ~ 2023.12 | 백엔드 | - |
| Tableau 기반 상명 Big Data Visualization Training | 로고스데이터| 2023.07 (40H) | 교육 | [수료증](https://github.com/user-attachments/assets/68a73d8e-4994-4d67-bb1e-dbe9ac97b372) |
-->

| 활동 | 기관 |  기간 | 비고 |
|---|:---:|:---:|:---:|
| 프로그래머스 백엔드 데브코스 9기 | 그렙(Grepp) | 2026.01 ~ 2026.07 | 수료 |
| 상명대학교 소프트웨어학과 (졸업) | - | 2022.03 ~ 2026.02 | 졸업 학점: **4.0**/4.5 |
| Kakao x 9oormthon Univ 2기 | goorm | 2024.02 ~ 2024.08 | 백엔드 수료 |
| 멋쟁이 사자처럼 대학 11기 | LIKELION | 2023.03 ~ 2023.12 | 백엔드 수료 |
<!--
| 첨단분야 혁신융합대학사업 (서포터즈) | 한국연구재단 | 2024.04 ~ 2025.02 | 서포터즈 |
| Tableau 기반 상명 Big Data Visualization Training (교육) | 로고스데이터| 2023.07 (40H) | 수료 |
-->
<br>

## 🏅 AWARD & CERTIFICATE
<!--
| 내용 | 주관 | 취득일 | 비고 |
|---|---|---|:---:|
| 정보처리기사 | 한국산업인력공단 | 2025.09 | [합격증](https://github.com/user-attachments/assets/a0994212-4010-4cb8-9862-0c8c04959021) |
| SQL Developer (SQLD) | 한국데이터산업진흥원 | 2025.09 | [합격증](https://github.com/user-attachments/assets/8b00fa0d-8692-4d62-9628-ccdd1a49474f) |
|OPIc IM2|ACTFL|2025.02|-|
|SM@ COSSTHON **우수상** 🏆|상명대학교 바이오헬스|2024.12|[상장](https://github.com/user-attachments/assets/12ef2bf8-dd6d-41ad-8c0f-3947a75cee2b)|
| 정보처리기능사 | 한국산업인력공단 | 2024.09 | [합격증](https://github.com/user-attachments/assets/fb2f2f92-2997-4a0a-a6a4-21a9da05f8e9) |
-->
| 내용 | 주관 | 취득일 |
|---|---|---|
| 정보처리기사 | 한국산업인력공단 | 2025.09 |
| SQLD | 한국데이터산업진흥원 | 2025.09 |
| 리눅스마스터 2급(1차) | 한국정보통신진흥협회(KAIT) | 2025.05 |
|OPIc IM2|ACTFL|2025.02|-|
|SM@ COSSTHON **우수상** 🏆|상명대학교 바이오헬스|2024.12|
| 정보처리기능사 | 한국산업인력공단 | 2024.09 |
<br>

## 📈 ACTIVITY

[![Solved.ac Profile](http://mazassumnida.wtf/api/v2/generate_badge?boj=sky09508)](https://solved.ac/sky09508)


