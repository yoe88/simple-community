### 프로젝트 설정
- JDK 11
- Gradle
- Spring Boot
- JPA, Querydsl
- Thymeleaf
- docker 를 이용해 PostgreSQL 사용
>윈도우 환경 Docker Toolbox 접속 방법
```shell script
docker run -p 5432:5432 -e POSTGRES_USER=woo -e POSTGRES_PASSWORD=1234 -e POSTGRES_DB=community --name postgres_spring -d postgres
docker exec -i -t postgres_spring bash
psql --username woo --dbname community
```
- Flyway 를 이용한 마이그레이션
---
### 프로젝트 기능
- 회원
- 글 게시판
- 이미지 게시판
- 관리자
