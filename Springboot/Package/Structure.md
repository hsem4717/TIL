# 패키지 구조

#### 계층형과 도메인형 크게 두 가지 유형으로 나뉘어짐

계층형 - 각 계층을 대표하는 디렉터리를 기준으로 코드를 구성

<h3>예시</h3>
Application.java

└ /controller

└ /service

└ /repository


장점
- 프로젝트에 이해도가 낮아도 전체적인 구조를 빠르게 파악할 수 있다<br>

단점
- 디렉토리에 클래스들이 너무 많이 모이게 된다
 
 <hr>
 
도메인형 - 도메인 디렉터리를 기준으로 코드를 구성

<h3>예시</h3>
Application.java

/book

└ /controller

└ /service

└ /repository

/card

└ /controller

└ /service

└ /repository

장점
- 관련된 코드들이 응집해 있다.<br>

단점
- 프로젝트에 대한 이해도가 낮을 경우 전체적인 구조를 파악하기 어렵다
- 패키지 간 순환 참조가 발생할 수도 있다
