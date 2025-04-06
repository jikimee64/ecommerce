
## 이커머스 프로젝트
- 이커머스 주제는 거들뿐 장난감 프로젝트성으로 이것저것 실험 및 적용이 목적

### 적용 기술
- Spring Boot
- Spring Data JPA
- Exposed
- Redis
- MySQL
- Kotest
- mock
- kotlin-logging

### 모듈 구성

|**모듈**|**설명**|
|---|---|
|api/user-api|사용자용 API (Controller, Facade, UseCase)|
|common|공통 유틸, DTO, 예외처리, 공통 response 등|
|core/domain|도메인 엔티티, 비즈니스 로직 (JPA Entity, Domain Service 등)|
|core/persistence|JPA Repository, QueryDsl 구현체, DB 연동 로직|
|support/logging|로그 설정, AOP, Custom Logging|

### Todo 리스트

- [X] 멀티 모듈