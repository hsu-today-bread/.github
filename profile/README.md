# 한성대학교 2026 모바일 캡스톤 - 오늘의 빵 🍞

2026학년도 한성대학교 모바일 소프트웨어 캡스톤 디자인 프로젝트입니다.  
오늘의 빵(TodayBread)은 근처 동네의 빵집에서 마감 시 버려지는 빵을 할인된 가격으로 구매하는 플랫폼입니다.  
당일 상품 탐색, 주문, 결제, 픽업 흐름을 모바일에서 연결하는 서비스입니다.

## 데모 영상

<a href="https://www.youtube.com/watch?v=KsKTnp1AZuo">
  <img src="https://img.youtube.com/vi/KsKTnp1AZuo/maxresdefault.jpg" alt="오늘의 빵 데모 영상" width="640" />
</a>

## 프로젝트 목표

- 사용자가 주변 빵집과 당일 판매 상품을 쉽게 탐색할 수 있는 모바일 앱 구현
- 주문, 결제, 픽업 상태를 하나의 흐름으로 관리하는 백엔드 API 설계
- 사장님, 사용자, 상품, 주문, 리뷰 데이터를 안정적으로 다루는 도메인 구조 구축
- Toss Payments, Naver Map/Geocoding, FCM, 사업자 검증 API 등 외부 서비스 연동
- 문서화와 컨벤션을 통해 팀원이 함께 유지보수할 수 있는 개발 환경 구성
- 릴리즈 가능 수준의 개발 완성도 추구

## 팀원

| 역할 | 이름 | GitHub |
| --- | --- | --- |
| 팀장, 프론트엔드 | 김민서 | [eric91405](https://github.com/eric91405) |
| 프론트엔드 | 최원재 | [chldnjswo](https://github.com/chldnjswo) |
| 백엔드 | 김현섭 | [hyunseop827](https://github.com/hyunseop827) |
| 백엔드 | 조영석 | [CHO-YoungSeok](https://github.com/CHO-YoungSeok) |

## 리포지터리

| Repository | Description | Stack |
| --- | --- | --- |
| [todaybread-backend](https://github.com/hsu-today-bread/todaybread-backend) | REST API 서버, 인증/인가, 주문/결제, 데이터 마이그레이션, API 문서화 | Java 21, Spring Boot 3, MySQL, Flyway, JWT, Argon2, Toss Payments, FCM |
| [todaybread-front](https://github.com/hsu-today-bread/todaybread-front) | 모바일 앱 UI, API 연동, 지도/주소 기반 기능, 주문 플로우 | Flutter, Dart, Naver Map/Geocoding |

## Tech Stack

### Backend

![Java](https://img.shields.io/badge/Java_21-007396?style=flat-square&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot_3-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![Spring Security](https://img.shields.io/badge/Spring_Security-6DB33F?style=flat-square&logo=springsecurity&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-000000?style=flat-square&logo=jsonwebtokens&logoColor=white)
![Gradle](https://img.shields.io/badge/Gradle-02303A?style=flat-square&logo=gradle&logoColor=white)

### DB & DevOps

![MySQL](https://img.shields.io/badge/MySQL_8-4479A1?style=flat-square&logo=mysql&logoColor=white)
![Flyway](https://img.shields.io/badge/Flyway-CC0200?style=flat-square&logo=flyway&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![AWS EC2](https://img.shields.io/badge/AWS_EC2-FF9900?style=flat-square&logo=amazonec2&logoColor=white)
![AWS S3](https://img.shields.io/badge/AWS_S3-569A31?style=flat-square&logo=amazons3&logoColor=white)

### Frontend

![Flutter](https://img.shields.io/badge/Flutter-02569B?style=flat-square&logo=flutter&logoColor=white)
![Dart](https://img.shields.io/badge/Dart-0175C2?style=flat-square&logo=dart&logoColor=white)
