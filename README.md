# SQL note

## Key의 종류 ()
### Super key
* 각 row들을 유일하게 특정할 수 있는 attribute의 집합.
* 테이블에서 각 super key의 값과 row는 1:1 관계이다.

### Candidate key
* Super key중에 크기가 가장 작은 key.
* Candidate key 안에 있는 column들은 prime attribute 라고 부른다.
    #### * Compound key
    * Candidate key 중에 2개 이상의 attribute로 이루어진 key들의 집합.

### Primary key
* Candidate key 중에서 relation의 key로 선택된 것.
* Primary key가 아닌 Candidate key들을 alternate key 라고 부른다.
* Table에서 Primary key에 포함된 attribute들을 밑줄 긋는다.
    #### * Foreign key
    * 다른 테이블의 primary key 안에 있는 attribute들을 내 테이블에서 attribute들의 집합으로 묶은 것을 Foreign key 라고 한다.
    * Foreign key는 2개의 테이블을 연결 할 수 있다.
---

