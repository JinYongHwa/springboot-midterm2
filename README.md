# 객체지향언어 실습 중간고사

### 1. 다음의 조건에 맞게 Spring Boot 프로젝트를 생성하세요(60점)
- package 이름 : kr.ac.mjc.itc[본인학번]
- Spring Boot 버전 : 3.1.5
- 언어 : Java
- 빌드도구 : Gradle-Groovy
- JDK 버전 : 17

  
### 2. mysql 서버에 'itc[본인학번]' 으로 데이터베이스를 생성하고 Spring Boot 에서 이 데이터베이스로 접속하도록 설정하세요 (10점)

### 3. @Entity 어노테이션을 이용해서 아래의 스키마를 만족하는 테이블이 생성되도록 만드세요 (10점)
테이블 명 : product

컬럼명 : id
- type : 정수형
- primary key
- 데이터입력시 값 자동증가

컬럼명 : name
- type: 문자열
- null을 허용하지 않음

컬럼명 : price
- type : 정수형





### 4. Spring Boot로 ProductController 를 만들고 Rest API가 호출될시 3번문제의 테이블에 값이 저장되도록 만드세요 (10점)
- method : POST
- url : /api/products
- body(JSON) : {"name":"모듬회","price":50000}

![277873338-4065d397-7037-49cd-a174-8987fba3922c](https://github.com/JinYongHwa/springboot-midterm2/assets/21700482/9a7032bf-a1dd-43c5-9273-a1e3b2c10191)



### 5. Spring Boot로 ProductViewController 를 만들고 "/products" 로 접속했을때  위에서 입력한 학생 데이터가 나오도록 만드세요,단 css는 아래의 화면과 다르게나와도 정답으로 인정(10점)


![277873855-953131ea-163e-47f1-9119-07fd14ae86e8](https://github.com/JinYongHwa/springboot-midterm2/assets/21700482/f8146baf-9fdb-486c-8aab-d6c9cd0fcde0)


