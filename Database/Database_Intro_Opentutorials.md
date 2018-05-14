# Database Intro

> "데이터베이스에 대한 정리가 한번 필요하다"라는 생각을 행동으로 옮긴 날(18.05.14)
>
> 지식 공유자 - Opentutorials 재단에서 양질의 정보를 무료로 제공하시는 egoing님

## 데이터가 중요한 이유

* 데이터를 가공해서 다양한 일을 할 수 있기 때문이다.
* 인터넷에 연결된 앱과 웹을 통해서 지식을 전파할 수 있고,
* 빅데이터, 인공지능과 같은 기술을 이용해 대규모의 데이터로부터 통찰력 있는 분석결과를 얻을 수도 있다.
* 이런 결과를 위해서는 데이터를 저장하고, 꺼낼수 있어야 한다.
* 이를 위해서 우리가 선택할 수 있는 첫번째 수단은 **파일**이다.

### file

* 파일은 배우기가 쉽고, OS마나 file기능을 제공하기 때문에 어디에서나 사용할 수 있다.(심지어 Email과 메신저를 통해서 자유롭게 전송도 가능하다.)
* 하지만, 파일은 성능, 보안, 편의성에 한계를 가지고 있다.
* 파일의 한계를 극복하기 위해 고안된 전문화된 소프트웨어가 **데이터베이스**이다.

### database

* 데이터베이스를 이용하면 데이터를 안전하고, 편리하고, 빠르게 보관하고 사용할 수 있다.
* 종류
  * MySQL
  * Oracle
  * SQL Server
  * PostgreSQL
  * MongoDB
  * ...

## 데이터베이스의 본질

* 데이터베이스는 매우 방대한 기능을 가지고 있는 정보 도구이다.
* 기능이 방대한 이유는 데이터 관련해서 일어날 수 있는 일들이 매우 많기 때문이다.
* 이렇게 표면적이 넓은 기술을 배울 때에는 하나하나 각개격파하면서 학습하는 것은 좋은 방법이 아니다.
* 어떤 데이터베이스를 만나건, 데이터베이스에 데이터를 어떻게 입력하고 어떻게 출력하는가를 따져보는 것이 가장 중요하다.(데이터베이스의 본질에 집중하는 것)
* **입력**은 다시 세가지 작업으로 나눌 수 있다.
  * Create
  * Update
  * Delete
* **출력**
  * Read
* 데이터를 생성하고, 읽고, 수정하고, 삭제하는 네가지 작업이 데이터 관련해서 우리에게 필요한 거의 모든것이라고 해도 과언이 아니다.
* 데이터베이스의 방대한 기능들은 핵심인 CRUD를 보좌하는 부가적인 기능에 불과하다.
