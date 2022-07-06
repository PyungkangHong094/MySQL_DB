# DATA BASE 베이직 MySQL

### 기본

- CRUD Basic and important 제일 중요한 기초적인 부분
- Create 데이터를 생성하고
- Read 데이터를 읽고
- Update 업데이트하고
- Delete 지운다

데이터 베이스는 표를 만들어주는거라고 생각하면 된다. 예를들어서 구글스프레드시트, 엑셀 같은거다

관계형 데이터는 스프레드 시트랑 비슷하다
표라고 생각하면 된다

웹을통해서 데이터베이스를 만들어서 관리를 할 수 있다.

---

## Mysql 다운로드 사이트

- https://dev.mysql.com/downloads/mysql/

---

## bitnami WAMP

- https://bitnami.com/stack/wamp

---

## 프로그램 실행방법

1. 윈도우 + R
2. cmd
3. C:\Bitnami\wampstack-8.1.7-0\mariadb\bin
4. mysql -uroot -p
5. Enter password

---

## MySQL 서버 접속/사용방법

> -uroot -p

- 비밀번호를 치면 데이터베이스로 입장한다

> CREATE DATABASE [NAME];

- 데이터 베이스 생성하기

> SHOW DATABASES;

- 데이터 베이스 보여주기

> USE [NAME];

- 데이터베이스 사용하려면

> CREATE TABLE [Name]

- 데이터 베이스 테이블 이름을 작성해준다

> id INT(11) NOT NULL AUTO_INCREMENT

- ID 컬럼에는 숫자만 오게한다
- PK 프라이머리 키라고한다.
- AUTO_INCREMENT 자동으로 1씩 증가하는거다

---

## CRUD

- Create
- Read
- Update
- Delete

데이터를 추가하는건 Create

> INSERT INTO [DATABASE_TABLE]

데이터를 보자 확인 필수

> SELECT \* FROM [TABLE_NAME]

데이터를 읽는거 Read

> WHERE [Col] [NAME]

> SELECT id,title,created,author FROM [TABLE_NAME]

데이터를 업데이트 하는건 Update

> UPDATE [TABLE_NAME] SET [바꾸고싶은거='내용'] , [행들=''], WHERE [id=?];

- where 문을 빠트리면 정말 제앙이옵니다 조심

데이터를 지우는건 Delete

> DELETE FROM [TABLE_NAME] WHERE id=number;

디센딩 뒤로 거꾸로 진행

> DESE

---

## SQL

Structured Query Language
SQL은 어떠한 언어어보다 쉽다

관계형 데이터라고 한다

---

## 용어

- Table : 표
- row : 행
- column : 열

---
