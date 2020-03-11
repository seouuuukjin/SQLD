<h1>PL/SQL</h1>
  오라클에서는 pl/sql 이고,<br>
  sql server 에서는 T-SQL이다.
  
<ol> 
<h2>1.pl/sql의 구조</h2>
  기본적으로 oracle에서 pl/sql은 블록구조로 이루어지며, <br><br>
  
   블록 구조  = DML문장(INSERT, UPDATE, SELECT, DELETE) + Query문장 + 절차형언어(IF, LOOP)
   <br>
   
   ![](http://wiki.gurubee.net/download/attachments/26744176/SQL_231.jpg)
   
<h2>2.pl/sql의 실행 과정</h2>
유저 프로세스가 pl/sql 블록을 서버프로세스에 보낸다<br>
-> 서버 프로세서는 pl/sql블록을 받아서, pl/sql 엔진으로는 프로그램 문장(procedual)을 보내고, sql문장은 SQL STATEMENT EXECUTOR로 보낸다. <br>
<h2>3.pl/sql 블록의 종류</h2>
<ol>
  1.익명 블록 : 이름이 없음. 이름이 없는 pl/sql 블록
  2.프로시저 : \*\*리턴값을 하나이상\*\* 가질수 있는 프로그램
  3.함수 : \*\*리턴값을 반드시\*\* 반환!
  4.패키지 : 하나 이상의 프로시저/ 함수/ 변수/ 예외 등의 \*\*묶음\*\*
  5.트리거 : 지정된 이벤트가 발생하면 자동으로 실행되는 pl/sql 블록
 </ol>
<h2>4.작성</h2>

</ol>
