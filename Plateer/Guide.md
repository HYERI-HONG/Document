Guide
===

> Vue

- 프로젝트 구조
- default 통신 방식 : 동기
- style태그는 사용X
- src/styles폴더는 수정X

> Java

- Controller
  - Parameter Validation
  - API speck check
  - service invoke
- Service
  - 비지니스 로직 처리
  - dao 호출
- DAO

> SQL

- namespace는 파일명과 동일하기
- 주석은 namespace.id
- 가급적 Mybatis 태그 사용하지 말것(static query사용)
- 1Tab = 4space
- 쿼리 왼쪽 정렬
- From절 테이블은 연결 순서로
- Where절 join은 테이블 선언 순서로
