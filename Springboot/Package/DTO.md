# Dto

- Data Transfer Object의 약자
- Service나 Controller에서 DB에 접근할 때 사용하는 클래스
- view에서 controller로 넘어오는 데이터를 담거나, controller에서 service로 넘기는 데이터를 담거나 할 때 사용
- 로직을 가지지 않고, 데이터 객체에 대한 정보만 담고 있음
- 순수하게 데이터를 담아 계층 간으로 전달하는 객체

<h3>domain과의 차이점</h3>

- domain: DB 테이블에 대한 정보를 가지고 있는 클래스 
- dto: 해당 테이블에서 실제로 CRUD를 할 필드를 정의해둔 것

<h3>VO와의 차이점</h3>
- VO는 값 그 자체를 나태는 객체
- DTO와 반대로 로직 포함이 가능하다
