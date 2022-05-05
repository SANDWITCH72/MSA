# MSA 구축 과제 - (STEP.3) Spring Cloud Gateway

## 구현 화면 및 기능
* 스프링 클라우드 게이트웨이를 추가하여 Front와 Back 가져오기

## Tech stack
* Spring Boot : 2.6.6
* JDK : 1.8
* Database : MySQL & Mybatis
  * 자신의 MYSQL DB 연결 정보로 변경 필요
    * [front-end/src/main/resources/application.yml/application.yml](front-end/src/main/resources/application.yml) 의 spring.datasource 설정 항목 변경 필요
  * 테이블 생성 쿼리는 아래 파일을 참고
    * [schema.sql](schema.sql)
* View Engine : Thymeleaf
* CSS : Bootstrap 4.2.1
* JavaScript : JQuery 3.3.1

## 실행 환경
* PORT : Front-end 8080, Back-end 8081, Gateway 9090
* Main Class인 FrontEndApplication 클래스를 기준으로 프로그램 실행
* 반드시 로컬 환경에서 실행하시기 바랍니다.