## 프로젝트: calendar-dev
본 프로젝트는 한국기술교육대학교 컴퓨터공학부 4학년 "웹서비스컴퓨팅및실습" 수업에서 Assignment로 활용하는 프로젝트입니다. 

### Assignment 2
#### 제목: Dao를 JdbcTemplate를 활용하여 작성하고 JUnit 프레임워크로 테스트 하기
#### 기한: 2014년 10월 04일 (토요일) 23시 59분 
- calendar-dev를 pull 하여 최신 버전으로 업데이트하기
- calendar-dev 오른쪽 클릭 > Maven > Update Project 실행하여 라이브러리 재정리하기
  - [참고] 새로 추가된 Maven 라이브러리
    - spring-test
    - junit
- 요구 사항 1 - 다음 두 개의 Dao 클래스를 JdbcTemplate를 활용하여 리펙토링하기
  - JdbcCalendarUserDao.java
  - JdbcEventDao.java
  - [주의 1] 각 클래스 마다 deleteAll() 메소드가 추가되었고 구현 필요
  - [주의 2] EventDao 및 JdbcEventDao에 있던 이전 findForUser(int userId)는 findForOwner(int ownerUserId)로 메소드 이름과 인자 이름이 변경되었음, 역시 구현 필요
- 요구 사항 2 - 다음 테스트 클래스 구현하기 
  - 주석으로 설명해 놓은 7가지 사항 코딩하기 
  - [주의 1] @Before 1개 + @Test 6개
  - [주의 2] 테스트는 모두 성공해야 함
  - [주의 3] 비교 테스트시에는 반드시 JUnit 테스트 방법을 활용한다.
  
