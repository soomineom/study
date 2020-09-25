# 3-Tier-architecture

3계층 구조란 presentation 로직(client, user interface), business 로직, database 로직을 각각 다른 플랫폼 상에서 구현한 것

***Tier와 Layer의 차이 ?***

Tier - 구성요소들의 물리적 분리

Layer - 구성요소들의 논리적 분리

3계층 구조에서 각 계층은 물리적으로 독립적이며 각 계층의 변경이 다른 계층에 의존하지 않음

1.프레젠테이션 계층(GUI / Front-end 등으로 불리기도 함)

application의 최상위에 위치. 서로 다른 층에 있는 data 등과 커뮤니케이션

user interface 지원

주로 웹서버를 뜻 ← presentation layer

2.애플리케이션 계층

비즈니스 로직 계층 또는 트랜잭션 계층이라고 함

주로 어플리케이션 서버를 뜻함

3.데이터 계층

데이터베이스와 그것에 액세스해서 읽거나 쓰는 것을 관리하는 프로그램 포함

주로 DB를 뜻함

DB 또는 File system을 접근, 관리