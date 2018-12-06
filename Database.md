# DBMS

DBMS란 데이터베이스의 집합을 만들고 저장, 관리하는 기능을 제공하는 응용 프로그램이다.

데이터의 관리에 특화된 프로그램으로 자료의 통합성을 증진시키고 데이터의 접근성이 용이하며 프로그램 개발 관리의 용이함과 강한 보안성이 장점으로 꼽힌다.

널리 알려진 DBMS엔 오라클의 오라클 데이터베이스, MySQL. MariaDB Foundation의 MariaDB. IBM의 INFORMIX, DB2. 마이크로소프트의 Microsoft SQL Server. 알티베이스의 ALTIBASE HDB. 그리고 최근 각광받는 PostgreSQL 등이 있다.

우리는 최근 사용률이 크게 증가하여 관련 정보를 찾기 쉬운 PostgreSQL을 사용하기로 한다.

## 오라클 데이터베이스

오라클 데이터베이스는 오라클 사에서 개발한 관계형 데이터베이스 관리 시스템으로 은행 등 기업체에서 많이 사용된다.

현재 유닉스 환경에서 가장 널리 쓰이는 DBMS이다.

## MySQL

MySQL은 1995년 발표된 오픈 소스 DBMS이다. 제작사는 MySQL AB인데 이 회사는 썬 마이크로시스템즈에게 인수되었고, 썬 마이크로시스템즈가 오라클에게 인수되면서 현재는 오라클이 MySQL의 소유주이다.

그러나 오라클이 이미 오라클 데이터베이스를 가지고 있고, 오픈 소스에 호의적이지 않으며 프로그램이 점차 복잡해지자 MySQL 사용자들 사이에서 많은 불만이 나오고 있으며 이에 대안으로 MariaDB라는 DBMS가 생겨났다.

상당히 높은 점유율을 가지고 있었으나 오라클에게 인수 된 이후 MariaDB나 PostgreSQL로 넘어가는 움직임이 많이 보이고 있으며, 예시로 애플은 OS X 서버 버전에서 MySQL 대신 PostgreSQL을 채택했다.

MySQL의 이름은 MySQL 설립자 몬티 와이드니어스의 첫째 딸 이름 마이에서 따온 것이라고 한다.

## MariaDB

MySQL이 오라클에게 인수된 후 라이언스 문제를 해결하고자 대안으로 나온 DBMS이다. MySQL AB 출신의 개발자들이 2009년 퇴사한 후 개발한 DBMS로 기능적으로는 MySQL과는 거의 동일하다.

오라클이 MySQL의 기능 추가를 제대로 하지 않고 있어서 많은 개발자들이 MariaDB로 넘어와서 현재 꽤 높은 점유율을 보인다.

C++로 구현되어있으며 현재는 MariaDB에 먼저 구현된 기능이 MySQL에 도입되기도 한다고 한다.

MariaDB에서의 Maria는 MySQL 설립자 몬티 와이드니어스의 둘째 딸의 이름인 마리아에서 따왔다고 한다.

### 몬티 와이드니어스

몬티 와이드니어스는 헬싱키 출신의 프로그래머이다.

그는 MySQL과 MariaDB의 창시자로 MySQL을 썬 마이크로시스템즈에 매각한 후 썬 마이크로시스템즈가 오라클에게 인수되자 MySQL의 대항마로 MariaDB를 개발하여 배포했다.

MySQL과 MariaDB는 그의 두 딸 이름에서 따와서 명명했다고 알려져있다.

## PostgreSQL

PostgreSQL은 The PostgreSQL Global Development Group에서 개발한 오픈소스 DBMS이다.

PostgreSQL은 Oracle Database, MySQL, Microsoft SQL에 이어 4위인데 꾸준히 사용률이 증가하고 있다.

MySQL에 비해 SQL 표준을 잘 지원하고 강력한 기능을 가지고 있단 것이 장점으로 꼽히며, 최근 애플이 OS X 서버에서 MySQL 대신 채택했다.

MySQL이 오라클에게 넘어가면서 저작권 분쟁 문제가 일어날 가능성이 있단 점에서 프로그래머들 사이에서 대안으로 많이 선택된다고 한다.
