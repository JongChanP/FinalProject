FORK된 해당 프로젝트는 국비지원 교육시 Final Project로 진행한 작업물 입니다. 😃 

## 목차
### ​1️⃣ 어떤 프로젝트 인가? 
### 2️⃣ 나의 작업은?
### 3️⃣ 개발 환경 / 기술 스택은?
### 4️⃣​ 핵심 기능 구현 방법 설명
### 5️⃣ 나의 작업 파일 경로

&nbsp;

## ​1️⃣ 어떤 프로젝트 인가? 
Final Project 진행 당시 해외 dreamboard.com 이라는 꿈을 기록하는 일기 같은 웹 페이지를 보았는데
꿈을 다른사람들과 공유하고 사고 팔 수 있는 웹 페이지를 개발해보고 싶어
**달러구트 꿈백화점** 을 모티브로 만들었습니다.

&nbsp;
  <image src="https://github.com/JongChanP/FinalProject/blob/main/FinalImage/main.png" />
&nbsp;

## 2️⃣ 나의 작업은?
저는 당시 Semi Project 때 구현 하지 못한 결제와
cookie를 사용한 장바구니 기능을 구현 하고 싶어서 **쇼핑몰 화면 구현과 기능**을 담당하였습니다.

&nbsp;

## 3️⃣ 개발 환경 / 기술 스택은?
**개발환경**

- STS 
- Apache Tomcat 9.0
- jsp
- Mybatis
- maven
- Visual Studio Code
- SQL Developer

** 기술 스택**

- Java(jdk 11)
- spring Framework / MVC 아키텍처 패턴 
- Oracle DB
- vanila javascript
- jQuery
- HTML5
- CSS

&nbsp;
## 4️⃣​ 핵심 기능 구현 방법 설명
```java
👉 WIKI에 핵심 기능 구현 코드 및 방법 정리
```
* [01 상품 목록](https://github.com/JongChanP/FinalProject/wiki/01-%EC%83%81%ED%92%88-%EB%AA%A9%EB%A1%9D)
* [02 상품 등록](https://github.com/JongChanP/FinalProject/wiki/02-%EC%83%81%ED%92%88-%EC%B6%94%EA%B0%80)
* [03 상품 상세](https://github.com/JongChanP/FinalProject/wiki/03-%EC%83%81%ED%92%88-%EC%83%81%EC%84%B8)
* [04 상품 수정](https://github.com/JongChanP/FinalProject/wiki/04-%EC%83%81%ED%92%88-%EC%88%98%EC%A0%95-%EB%B0%8F-%EC%82%AD%EC%A0%9C)
* [05 장바구니](https://github.com/JongChanP/FinalProject/wiki/05-%EC%9E%A5%EB%B0%94%EA%B5%AC%EB%8B%88)
* [06 결제](https://github.com/JongChanP/FinalProject/wiki/06-%EA%B2%B0%EC%A0%9C)
* [07 댓글](https://github.com/JongChanP/FinalProject/wiki/07-%EB%8C%93%EA%B8%80)

## 5️⃣ 나의 작업 파일 경로
<details>
  <summary>Code 경로</summary>
  <br />
  <div markdown="1">
    **spring**
    1. 상품
    - controller : https://github.com/JongChanP/FinalProject/blob/main/workspace/FinalPrj/src/main/java/com/dds/app/product/controller/ProductController.java
    - service : https://github.com/JongChanP/FinalProject/tree/main/workspace/FinalPrj/src/main/java/com/dds/app/product/service
    - dao : https://github.com/JongChanP/FinalProject/blob/main/workspace/FinalPrj/src/main/java/com/dds/app/product/dao/ProductDao.java
    - vo : https://github.com/JongChanP/FinalProject/tree/main/workspace/FinalPrj/src/main/java/com/dds/app/product/vo
    - mapper(mybatis) : https://github.com/JongChanP/FinalProject/blob/main/workspace/FinalPrj/src/main/resources/mybatis/mapper/product-mapper.xml
    
    2. 상품 댓글
    - controller : https://github.com/JongChanP/FinalProject/tree/main/workspace/FinalPrj/src/main/java/com/dds/app/product/reply/controller
    - service : https://github.com/JongChanP/FinalProject/blob/main/workspace/FinalPrj/src/main/java/com/dds/app/product/reply/service/PReplyService.java
    - dao : https://github.com/JongChanP/FinalProject/blob/main/workspace/FinalPrj/src/main/java/com/dds/app/product/reply/dao/PReplyDao.java
    - vo : https://github.com/JongChanP/FinalProject/blob/main/workspace/FinalPrj/src/main/java/com/dds/app/product/reply/vo/PReplyVo.java
    - mapper(mybatis) : https://github.com/JongChanP/FinalProject/blob/main/workspace/FinalPrj/src/main/resources/mybatis/mapper/product-reply-mapper.xml
    
    3. 장바구니
    - controller : https://github.com/JongChanP/FinalProject/blob/main/workspace/FinalPrj/src/main/java/com/dds/app/cart/controller/CartController.java
    
    4. 결제
    - controller : https://github.com/JongChanP/FinalProject/blob/main/workspace/FinalPrj/src/main/java/com/dds/app/pay/controller/PayController.java
    - vo : https://github.com/JongChanP/FinalProject/blob/main/workspace/FinalPrj/src/main/java/com/dds/app/pay/vo/PayVo.java
    결제의 service , dao , mapper 는 회원 관련이라 member에 작성하였습니다.
    - service : https://github.com/JongChanP/FinalProject/blob/main/workspace/FinalPrj/src/main/java/com/dds/app/member/service/MemberService.java
    - dao : https://github.com/JongChanP/FinalProject/blob/main/workspace/FinalPrj/src/main/java/com/dds/app/member/dao/MemberDao.java
    - mapper : https://github.com/JongChanP/FinalProject/blob/main/workspace/FinalPrj/src/main/resources/mybatis/mapper/member-mapper.xml
  </div>
</details>
<details>
  <summary>jsp 경로</summary>
  <br />
  <div markdown="1">
    **jsp**
    - 상품 : https://github.com/JongChanP/FinalProject/tree/main/workspace/FinalPrj/src/main/webapp/WEB-INF/views/product
    
    - 장바구니 : https://github.com/JongChanP/FinalProject/blob/main/workspace/FinalPrj/src/main/webapp/WEB-INF/views/product/cart.jsp
    
    - 결제 : https://github.com/JongChanP/FinalProject/tree/main/workspace/FinalPrj/src/main/webapp/WEB-INF/views/pay
  </div>
</details>






&nbsp;
