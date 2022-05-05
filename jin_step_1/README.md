# MSA 구축 과제 - (STEP.1) Swagger Docs

## 구현 화면 및 기능
* http://localhost:8080/swagger-ui.html 접속하여 파라미터 전송 및 값 확인

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
* PORT : 8080
* Main Class인 BoardtEndApplication 클래스를 기준으로 프로그램 실행