# <div align="center">**AJJShoppingmall**</div>

## Shoppingmall

### 기간 : 2022.8.15 ~ 2022.8.29

### 개발자 : 주병현, 안주영, 장지원

## 📌 본인 역할

### 백엔드 및 프론트엔드

### 프론트
1. 메인페이지 및 슬라이드 제작
2. 출석체크 페이지 제작
3. 포인트 이벤트 제작
4. 챗봇 페이지 제작
5. 사이드 리모컨 제작
</br>

### 백
1. DB설계
2. 마이페이지 db 설계 및 구현
3. 출석체크 db 설계 및 구현
4. 이벤트 포인트 db 설계 및 구현
5. 찜 목록 db 설계 및 구현
</br>

## 📌 개발 환경

<img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=JavaScript&logoColor=black">
<img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=CSS3&logoColor=white"> 
<img src="https://img.shields.io/badge/Mysql-2496ED?style=for-the-badge&logo=Mysql&logoColor=black"> 
<img src="https://img.shields.io/badge/Sequelize-2496ED?style=for-the-badge&logo=Sequelize&logoColor=black"> 
<img src="https://img.shields.io/badge/Express-363636?style=for-the-badge&logo=Express&logoColor=white">
<img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=Node.js&logoColor=white"> 
<img src="https://img.shields.io/badge/JWT-FF9900?style=for-the-badge&logo=JWT&logoColor=black">
<img src="https://img.shields.io/badge/EJS-FF9900?style=for-the-badge&logo=EJS&logoColor=black">
<img src="https://img.shields.io/badge/SOCKETIO-FF9900?style=for-the-badge&logo=EJS&logoColor=black">

</br>

## 📌 개발 목차
<ul>개요
    <li>전체 데이터베이스
    <li>메인 페이지
    <li>안주영 페이지 클릭
    <li>주병현 페이지 클릭
    <li>장지원 페이지 클릭
    <li>회원가입 페이지
    <li>로그인 페이지
    <li>로그인 후 페이지(JWT 로그인 유지)
    <li>유저 베스트 검색 실시간 페이지
    <li>출석체크 페이지
    <li>챗봇 페이지
    <li>장바구니 리모콘 페이지
    <li>장바구니 기능
</ul>

### 전체 데이터베이스

<br/>

<img src="https://user-images.githubusercontent.com/107897959/224006490-82aa1a87-a15e-4607-ac07-879ef20abd26.png" />

<br/>

### 메인 페이지

<br/>

<img src="https://user-images.githubusercontent.com/107897959/224006580-2faa7476-0cf6-4146-b076-21e5d8178341.png" />

<br/>

## 페이지를 누르면 각 디자이너의 쇼핑몰이 나옴.

### 안주영 페이지 클릭

<br/>

<img src="https://user-images.githubusercontent.com/107897959/224006668-a368bfc4-882d-4cd4-9776-dbec95c3fdf6.png" />

<br/>

### 주병현 페이지 클릭

<br/>

<img src="https://user-images.githubusercontent.com/107897959/224006761-bdc393bd-7d29-4ba9-bd75-4d0e70aa7989.png" />

<br/>

### 장지원 페이지 클릭

<br/>

<img src="https://user-images.githubusercontent.com/107897959/224006825-e7cbf69e-d262-4720-9aec-b15f383e8600.png" />

<br/>

### 회원가입 페이지

- 로그인이 진행된 유저에게는 회원가입 버튼이 눌려지지 않게 기능 구현.
- 회원가입 시 정규식을 작성하여 정규식 규칙 틀릴 시 회원가입 진행 불가 기능 구현.

<br/>

<img src="https://user-images.githubusercontent.com/107897959/224006936-a5677123-53d4-40f1-bc7c-787bae802c6c.png" />

<br/>

### 로그인 페이지

- 로그인이 완료된 사용자는 회원가입 진행 불가 처리.
- JWT로 로그인 유지 기능 구현.

<br/>

<img src="https://user-images.githubusercontent.com/107897959/224006990-3b5ec091-6fb8-491f-a057-eeb55f4e6865.png" />

<br/>

### 로그인 후 페이지(JWT 로그인 유지)

<br/>

<img src="https://user-images.githubusercontent.com/107897959/224007219-c7aa6520-257b-4dde-851e-0c1727dd8170.png" />

<br/>

### 출석체크 페이지

- 유저가 출석체크를 한다면 마일리지 포인트 지급.
- 하루에 한 번씩 출석체크 가능.
- 출석이 다 됐다면 색깔 변형으로 출석체크 중복 방지.

<br/>

<img src="https://user-images.githubusercontent.com/107897959/224007349-ccbee150-2624-4230-b5a9-9180e8da14f6.png" />

<br/>

### 챗봇 페이지

- 챗봇은 상담원으로 바로 연결하기 위해 정해진 답변을 내놓고 상담원과 바로 연결하는 로직.
- socketio를 활용하여 실시간 상담 구현


<br/>

<img src="https://user-images.githubusercontent.com/107897959/224007450-ad9fa61d-837a-4257-9d1e-d47377bd4c01.png" />

<br/>

###  메인 사이드 메뉴바

- 스크롤을 따라 메뉴바가 움직이고 해당 버튼을 누르면 각 페이지로 이동
- 맨 밑에 탑버튼 클릭시 페이지 최상단으로 이동

<br/>

<img src="https://user-images.githubusercontent.com/107897959/224007514-4006ccf8-bce6-48e7-915a-797762d35baf.png" />

<br/>

###  하트 풍선 이벤트

- 일정 랜덤한 시간에 따라 하트 풍선 아이콘이 생성됨.
- 하루에 한번 클릭 가능
- 클릭시 랜덤한 포인트 지급

<br/>

<img src="https://user-images.githubusercontent.com/107897959/224012186-ed3aa7bc-0f4f-4dbf-85cb-5e96ef42b9eb.png" />

<br/>

## 팀 노션 및 회의록

https://cuddly-petroleum-f3d.notion.site/AJJ-2022-691568ca87904d14bc145cf56dff1da5

## 오류

1. 이벤트 아이콘 클릭시 쿠키 오류로 하루에 한번 작동이 안됨.
2. 메인 슬라이드 및 부가적인 슬라이드 기능 구현의 완료가 부실.
3. 데이터 베이스 설계 중 정규화를 따르지 않는 데에서 생기는 처리 속도.
- 현업에서 자주 쓰이는 관계형 데이터베이스 형식은 정규화를 많이 사용함을 발견함.

오류 파악후 해결하도록 할 예정
