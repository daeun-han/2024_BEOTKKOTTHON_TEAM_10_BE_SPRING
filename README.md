# 🎓 CEN [2024_BEOTKKOTTHON_TEAM_10_BE_SPRING]
**"복잡한 공고 속에서 찾는 나만의 혜택, 맞춤형 장학금 큐레이션 플랫폼"**
<br>

<img width="1976" height="1114" alt="image" src="https://github.com/user-attachments/assets/e3c027ff-6efc-4777-b700-2d5d11fc1250" />


## 📍 서비스 개요
대학생들의 지역 정보, 학년, 성적 등 개인화된 조건을 분석하여 최적의 장학금을 매칭해주는 서비스입니다. 단순 정보 제공을 넘어 실시간 D-Day 계산 및 지원 상태 관리 기능을 통해 대학생들의 경제적 기회를 지원합니다.

---
![10팀cen_구름톤발표자료 - 조예진_page-0002](https://github.com/user-attachments/assets/9b13461e-b128-4bbc-a35d-36da8fb5dbcd)
![10팀cen_구름톤발표자료 - 조예진_page-0003](https://github.com/user-attachments/assets/93e27213-582e-4101-afb2-55853e5208fe)
![10팀cen_구름톤발표자료 - 조예진_page-0004](https://github.com/user-attachments/assets/295c698b-e0a7-49ee-8e5e-ec5cfc282aed)
![10팀cen_구름톤발표자료 - 조예진_page-0006](https://github.com/user-attachments/assets/8a1e7c6f-be67-47af-a486-69e3640c1d23)
![10팀cen_구름톤발표자료 - 조예진_page-0007](https://github.com/user-attachments/assets/634b51c9-55f0-4366-ae02-bf5f39b07c85)
![10팀cen_구름톤발표자료 - 조예진_page-0008](https://github.com/user-attachments/assets/3a66d653-dbbd-4339-9cd6-0008b7a99d5a)
![10팀cen_구름톤발표자료 - 조예진_page-0009](https://github.com/user-attachments/assets/65fe9507-cfb3-4048-b1a5-d7795db2f272)

---
## 🛠️ Tech Stack

| Category | Content |
| :--- | :--- |
| **Language** | Java 17 |
| **Framework** | Spring Boot 2.7.x |
| **Database** | MariaDB, MySQL (WorkBench) |
| **ORM** | Spring Data JPA |
| **Deployment** | Cloudtype |
| **Etc** | Gradle, HikariCP, Lombok |

---
## 🖥️ 담당 API (Backend)

| 기능 | 상세 내용 |
| :--- | :--- |
| **추천 알고리즘** | 유저의 지역(시/군/구) 및 학년 정보를 대조하여 맞춤형 장학금 매칭 로직 구현 |
| **스크랩 관리** | `Save` 테이블 및 `Status` Enum을 활용한 스크랩 및 지원 상태(지원중/완료) 관리 API |
| **인프라/배포** | 환경 변수 처리를 통한 DB 연동 및 Cloudtype을 활용한 서버 배포 자동화 |

---

## 🤝 협업 포인트: Spring과 Express 서버간 스택 통합
```
[ Client: iOS ]
       │
       ▼
 [ API Gateway ] ◀─── (통합 엔드포인트 / 라우팅)
       │
       ├───────────────────────┐
       ▼                       ▼
 [ Spring Boot Server ]   [ Express Server ]
 (장학금 매칭/필터링)      (로그인/기타 기능)
```
