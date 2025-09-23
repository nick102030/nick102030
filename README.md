<!-- 프로필 배너/간단 인사말은 선택 -->
<h1 align="left">김태현 · Backend Developer (Spring Boot)</h1>
<p align="left">
백엔드 설계와 배포 자동화를 좋아합니다. Spring Boot + JPA + MySQL을 중심으로 <b>성능과 운영 편의</b>에 집착합니다.
</p>

<!-- Now: 한 줄씩 -->
💡 Now  
- 스프링 WebFlux 전환 & 고부하 환경에서의 안정화  
- 도커·NGINX·GitHub Actions로 CI/CD 고도화  
- 추천 시스템(노인 맞춤 간식 추천) 실서비스화  

---

## 대표 프로젝트
- **9oormCinema** — 공연/영화 예매 백엔드 (회원·비회원 예매, 좌석선택, 쿠폰)
  - p95 응답 **420s → 110s**, 실패율 **28% → 3%**(비동기 큐·배치·서킷브레이커 도입)
  - [Repo](https://github.com/USERNAME/9oormCinema) · [ERD/문서](https://github.com/USERNAME/9oormCinema/wiki)
- **SilverSnack** — 노인 맞춤 간식 추천 (Vertex AI/Gemini)
  - 카테고리 추천 파이프라인, 영양 CSV 파싱 → Top-N 후보군 필터링
  - [Repo](https://github.com/USERNAME/SilverSnack)
- **Tasting Note** — 커피/위스키/차 테이스팅 노트 SNS
  - JWT 인증, 카테고리·해시태그 모델링, MySQL 인덱싱 최적화
  - [Repo](https://github.com/USERNAME/tasting-note)
- **Maple Guild Tools** — 메이플 길드/캐릭터 도구 모음
  - Nexon Open API 연동, 랭킹/길드 관리 자동화
  - [Repo](https://github.com/USERNAME/maple-guild-tools)

---

## 기술 스택
**Backend**: Spring Boot, WebFlux, JPA/Hibernate, QueryDSL, Kotlin/Java  
**DB/Cache**: MySQL, Redis  
**Infra**: Docker, Nginx, AWS EC2/ECR/CodeDeploy  
**Data/AI**: Vertex AI (Gemini), Python(ETL)  
**Collab**: Git/GitHub Actions, Jira/Notion

<!-- 간단 뱃지만. 과용 금지 -->
<p>
  <img alt="Java" src="https://img.shields.io/badge/Java-ED8B00?logo=openjdk&logoColor=white">
  <img alt="Spring Boot" src="https://img.shields.io/badge/Spring%20Boot-6DB33F?logo=springboot&logoColor=white">
  <img alt="MySQL" src="https://img.shields.io/badge/MySQL-4479A1?logo=mysql&logoColor=white">
  <img alt="Docker" src="https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white">
  <img alt="AWS" src="https://img.shields.io/badge/AWS-232F3E?logo=amazon-aws&logoColor=white">
</p>

---

## 숫자로 보는 개선
- 동기 호출 → **잡 큐(비동기)** 전환, 작업당 VRAM 상한 & 배치 자동조절  
- 후처리 표준화/캐시로 **콜드스타트 제거**, 혼합정밀도(fp16)로 추론 최적화  
- 배포 파이프라인 개선(GitHub Actions + CodeDeploy)로 **릴리스 리드타임 단축**

> “장비빨”보다 모델링·설계·관측(Observability)로 성능을 뽑아내는 걸 좋아합니다.

---

## 글/발표(선택)
- WebFlux 전환기 & 서킷브레이커 적용기 – (링크)
- Vertex AI + Spring 통합 삽질기 – (링크)

---

## 연락
- Email: taehyun@example.com  
- Blog: https://blog.example.com  
- LinkedIn: https://www.linkedin.com/in/USERNAME/  
- (선택) Resume: [PDF](https://example.com/resume.pdf)

<!-- 통계 위젯은 취향껏. USERNAME 교체 -->
<!-- 
![GitHub Stats](https://github-readme-stats.vercel.app/api?username=USERNAME&show_icons=true)
![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=USERNAME&layout=compact)
-->
