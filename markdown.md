# WorkBench 활용한 MYSQL 접속 방법

* 링크를 통한 공식홈페이지 접속

* 다운로드 클릭

* 별도 로그인이나 회원가입 없이 진행 가능

* 설치 파일 실행

* 설치

-------------

## MYSQL WorkBench 확인(추가설정)

*  (1) Edit - Preferences
*  (2) 설정 완료

## [공통] 

1. 실습용 DB 준비

* DB 파일 다운로드 및 확인

 (1). 샘플 DB 다운 및 압축 풀기

 (2). sample_db.sql 파일 확인

2. Workbench 활용 실습용 DB 추가

 (1). MYSQL 접속
 (2). administration -> Data Import/Restore
 (3). Import from self-Contained File 체크
 (3)-1. . 클릭
 (3)-2. 다운로드 받은 sample_db.sql 파일 선택
 (3)-3. Start Import
 (4). Import 성공 화면 확인

 3. 실습용 DB 확인

 (1) Schemas 클릭
 -> 새로고침 버튼 클릭
 -> DB classicmodels 확인

---

1. 쿼리(QUERY) 실행 테스트
* classicmodels DB 선택
* Query 에디터 클릭
* 쿼리문 입력 (SELECT * FROM customers;)
* 쿼리 실행
* 출력 확인

--- 

1. 한글 입력 설정

* 데이터베이스 옆 도구 모양 클릭
* utf8과 utf8_bin 으로 변경 - Apply 클릭