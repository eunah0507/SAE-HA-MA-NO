# 새하마노 SAE-HA-MA-NO

![image](https://github.com/user-attachments/assets/ae8e4189-4975-4ed8-a83b-bd2b93e8c98b)


### 가상의 궁 새하마노 소개 사이트 
#### 새하마노(SAE-HA-MA-NO : 순우리말로 동서남북을 뜻합니다.)
---

<br>

### < 기획 의도 >

* 우리나라 관광객 증가 추세에 맞춰 전통 고궁을 알리고 전시회 및 관련 굿즈를 구매할 수 있는 사이트 개발
* 전통 문화와 역사를 현대적으로 재조명하여 방문객들에게 한국의 역사적 가치를 교육하는 플랫폼 개발
* 웹 사이트로 즐김으로써 편리성 증가

<br>

 ### < 서비스 소개 >

 * 회원 가입 및 로그인 기능
 * 실시간 다대다 채팅
 * 전시 프로그램 찜 및 예약
 * 티켓 및 관련 굿즈 구매(장바구니, 쿠폰, 리뷰 작성 등)
 * 이벤트 페이지, 공지 및 자주 묻는 질문 게시판

<br>

### < 팀원 구성 및 프로젝트 기간 >

* 기간 : 2022년 12월 05일 ~ 2023년 02월 28일
* 팀원 구성

  |정은아|구인영|장현주|서지효|이학연|김소희|
  |:---:|:---:|:---:|:---:|:---:|:---:|
  |팀장, BE|BE|BE|BE|BE|FE|
  
<br>

### < 기술 스택 >
#### ✔️ Spring MVC 
        * Framework : Spring
        * Library : SpringBoot, Lombok, Spring Web, Validation, jQuery, Servelet, WebSocket, SMTP
        * Databse : Oracle
        * Language : Java 11


<br>
<br>

## < 메인 기능 소개> 

### 1-1. 회원 서비스 - 회원 가입 및 로그인

<p align="center">
  <img src="https://github.com/user-attachments/assets/6792d81d-433a-48bb-b46f-d5c74fef6b13" alt="Image 1" width="49%">
  <img src="https://github.com/user-attachments/assets/d1ac0673-25b8-4fc8-a059-1ba81f62ec5f" alt="Image 2" width="49%">
</p>

* 일반 로그인 및 소셜 로그인(Naver, kakao) 가능
* 회원 가입 시 생년월일로 어린이, 학생, 청년, 중년 구분
* PW 찾기 시 SMTP 587 port를 이용한 임시 비밀번호 발급
* 프로필 편집 기능

<br>

### 1-2. 메인 페이지 - 실시간 다대다 채팅 & 지도

<p align="center">
  <img src="https://github.com/user-attachments/assets/b017bc89-c936-4ff7-b16d-5801599c0c01" alt="Image 3" width="38%">
  <img src="https://github.com/user-attachments/assets/1aa167af-6f67-4c5a-acb5-358989964bfc" alt="Image 4" width="58%">
</p>


* WebSocket.io를 이용한 실시간 다대다 채팅 기능
* kakao maps를 이용한 오시는 길 소개

<br>

### 2. 전시 프로그램 찜 및 예약

<p align="center">
  <img src="https://github.com/user-attachments/assets/d1d688f2-1e3e-46e8-baca-ef1105a17747" alt="Image 1" width="49%">
  <img src="https://github.com/user-attachments/assets/47f0ecf0-d210-400f-9348-dfed1a023038" alt="Image 2" width="49%">
</p>

* 관련 프로그램 전시, 체험 등으로 분류
* 좋아요(찜) 기능으로 마이 페이지에서 확인 가능
* 날짜 및 시간으로예약 가능

<br>

### 3. 새하마노 관림 티켓 예약 및 구매(장바구니, 쿠폰, 리뷰 작성 등)

<p align="center">
  <img src="https://github.com/user-attachments/assets/3ead50ae-0fb3-46bb-8994-580ae7f7fa0f" alt="Image 1" width="49%">
  <img src="https://github.com/user-attachments/assets/9b22355b-28b1-4b33-8fc3-098699411bf6" alt="Image 2" width="49%">
</p>


* 새하마노 궁 관람 티켓 구매 시, 본인의 등급(나이로 구분)에 따라 구매 가능
* 추가로 다른 인원의 티켓 예약 및 구매 가능

<br>

### 4. 새하마노 굿즈 구매(장바구니, 쿠폰, 구매)

<p align="center">
  <img src="https://github.com/user-attachments/assets/15c04e5d-f6cd-4d7a-b83f-31613d6f8707" alt="Image 1" width="49%">
  <img src="https://github.com/user-attachments/assets/33e9afa6-1f37-4b1c-a0a2-9c0a6b3fdc22" alt="Image 2" width="49%">
</p>

* 새하마노 굿즈 구매 시, 카테고리 분류 (한복, 굿즈)
* 굿즈 목록 페이지네이션 처리
* 굿즈 상세 보기 시, 장바구니 담기 가능
* 해당 회원이 쿠폰 보유 시 결제 금액에서 할인

<p align="center">
  <img src="https://github.com/user-attachments/assets/10637cbd-4186-42a8-9d01-a5e1c169dd3f" alt="Image 1" width="49%">
  <img src="https://github.com/user-attachments/assets/ee2179f8-8e5c-4ef6-a4aa-7b3fcae75a5e" alt="Image 2" width="49%">
</p>

* 기존 프로젝트 시 카카오 간편 결제만 가능하였으나 리팩토릭 후 KG 이니시스 결제 방식 도입
* 결제 후 리뷰 게시판에서 글 작성 가능
  * 글 작성 시 별점을 부여하여 별점별로 검색 가능
  * 해당 상품에 몇 개의 리뷰와 평균 별점이 몇 점인지 파악 가능

<br>

### 5. 고궁 사진 이벤트 페이지

![image](https://github.com/user-attachments/assets/d20aecdc-a372-43c5-943f-da56542f5e0c)

* 고궁 관련 단일 이미지 삽입
* 투표 기능을 통해 최다 투표 수 사진 3개 최상단 노출

<br>

### 6. 공지 및 자주 묻는 질문 게시판

<p align="center">
  <img src="https://github.com/user-attachments/assets/028defa5-9a5e-4cf9-a03f-cd5185ae30f9" alt="Image 1" width="49%">
  <img src="https://github.com/user-attachments/assets/70a9eb6f-e174-4a6e-b7d4-ec3bab2cd990" alt="Image 2" width="49%">
</p>

* 고궁 관련 사이트이기 때문에 공지 사항과 자주 묻는 질문 게시판 분류

<br>
<br>

## <ERD 다이어그램>

![image](https://github.com/user-attachments/assets/13c6ec90-c3b7-4449-b6f9-8ed64164ba54)






