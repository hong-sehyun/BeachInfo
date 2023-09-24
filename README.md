# Beach Info

# 1. 개요
![beachinfo1 (2)](https://github.com/hong-sehyun/BeachInfo/assets/119600891/f3f689c3-f92b-4123-a87b-e3ab78f70645)


풀스택 미니 프로젝트<p/>
프로젝트 기간 : 2023.07.24 ~ 2023.08.09 <p/>
## 1.1 데이터 출처
해양수산부_해수욕장 개폐장일정 정보<p/>
https://www.data.go.kr/data/15056091/fileData.do <p/>


## 1.2 개발 엔진 및 언어
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=JavaScript&logoColor=black"/>
  <img src="https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=React&logoColor=black"/>
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white"/>
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white"/>

  <img src="https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=MySQL&logoColor=white"/>
  <img src="https://img.shields.io/badge/Spring-6DB33F?style=flat-square&logo=Spring&logoColor=white"/>


# 2. 웹서비스
## 2.1 지역 검색
<!-- ![beachinfo2](https://github.com/hong-sehyun/BeachInfo/assets/119600891/ce8dc8aa-4a5f-4e17-8dd8-0bedcea80197) -->
* 시 도, 시 군 구 선택 시 해당 지역의 해수욕장 목록 호출
* 지도보기 클릭 시 해수욕장 위치 지도 표시
<p align="center">
<img src="https://github.com/hong-sehyun/BeachInfo/assets/119600891/38e2296b-c1f7-49f9-89fa-38a9573a8129" align="center" width="49%">
  <img src="https://github.com/hong-sehyun/BeachInfo/assets/119600891/6ff434da-fb4d-47e8-bf8c-929bbd24a1a4" align="center" width="43.5%">
</p>

<!-- ![beachinfo4](https://github.com/hong-sehyun/BeachInfo/assets/119600891/2ae6aaac-6317-41d0-933d-a88e1a634cb8) -->
<!-- ![image](https://github.com/hong-sehyun/BeachInfo/assets/119600891/37ff7abf-e5b4-4db5-b869-617105f7b49d) -->


## 2.3 게시판
### 2.3.1 회원가입 및 JWT 로그인
***
* 회원이 아닌 사용자(게스트)는 게시글을 읽을 수 있으나 작성은 못함
* 게스트 상태에서 글쓰기를 클릭하면 '로그인을 해주세요'라는 alert가 뜸
<p align="center">
  <img src="https://github.com/hong-sehyun/BeachInfo/assets/119600891/3ab9f1f0-135f-4b5f-8bfa-34c1e999e57b" align="center" width="49%">
  <img src="https://github.com/hong-sehyun/BeachInfo/assets/119600891/7519c91e-44ab-4685-a37f-4db8decf90c7" align="center" width="49%">
</p>

* 로그인 페이지 하단 '가입' 클릭 시 회원가입 페이지로 이동
* 비밀번호 입력 시 일치 여부 확인 후 일치해야 가입 가능
<p align="center">
<img src="https://github.com/hong-sehyun/BeachInfo/assets/119600891/0fa04c60-6341-4583-9580-0628df2b61a4" align="center" width="49%">
<img src="https://github.com/hong-sehyun/BeachInfo/assets/119600891/134b7921-306d-4d7d-9b11-cc3b5a365bf6" align="center" width="49%">
</p>


### 2.3.2 게시글 작성
* * *
* 로그인을 하면 게시판 헤더의 '게스트'가 사용자 id로 바뀜
* 게시글 작성 페이지의 아이디도 사용자의 id로 고정되어 나타남
<p align="center">
<img src="https://github.com/hong-sehyun/BeachInfo/assets/119600891/a3bf35d9-6c95-4573-945f-a18fbbdcf1ec" align="center" width="67%">
<!-- <img src="" align="center" width="49%">
</p> -->


* 게시글 작성 시 해수욕장을 선택하게 하여 게시판을 이용하는 사용자가 정보를 편하게 검색할 수 있도록 함

<p align="center">
<img src="https://github.com/hong-sehyun/BeachInfo/assets/119600891/66b3fb39-27b0-4303-928e-3583044c50ef" align="center" width="67%">
<!-- <img src="" align="center" width="49%"> -->
</p>

* 이미지 첨부
<p align="center">
<img src="https://github.com/hong-sehyun/BeachInfo/assets/119600891/3cfd6b64-c88d-4dbe-9d92-d75c6a63daac" align="center" width="67%">
</p>

* 제출
<p align="center">
  <img src="https://github.com/hong-sehyun/BeachInfo/assets/119600891/5c0b7da5-12ad-4be9-ae72-f647bd46318d" align="center" width="32%">
  <img src="https://github.com/hong-sehyun/BeachInfo/assets/119600891/b7f7895e-7a87-4266-a674-6c683ba9afde" align="center" width="32.5%">
</p>

### 2.3.3 게시글 수정
_____

<p align="center">
<img src="https://github.com/hong-sehyun/BeachInfo/assets/119600891/e36afa75-031a-45cd-8f73-9bcbadd73fbf" align="center" width="67%">
</p>


## 2.4 반응형
* react-responsive 라이브러리 사용

<p align="center">
  <img src="https://github.com/hong-sehyun/BeachInfo/assets/119600891/d6b94dc9-0416-4046-a1a7-dadd6a2e4877" align="center" width="32%">
  <img src="https://github.com/hong-sehyun/BeachInfo/assets/119600891/9c5b6b3b-6937-4650-a3b2-82f0909ff991" align="center" width="32%">
  <img src="https://github.com/hong-sehyun/BeachInfo/assets/119600891/612b316f-55bd-413f-904c-cd659e87ea2f" align="center" width="32%">
</p>


<!-- ![게시판반응 (3)](https://github.com/hong-sehyun/BeachInfo/assets/119600891/612b316f-55bd-413f-904c-cd659e87ea2f)
![beachinfo5반응 (2)](https://github.com/hong-sehyun/BeachInfo/assets/119600891/9c5b6b3b-6937-4650-a3b2-82f0909ff991)
![beachinfo3](https://github.com/hong-sehyun/BeachInfo/assets/119600891/d6b94dc9-0416-4046-a1a7-dadd6a2e4877) -->




<p align="center">
  <img src="https://github.com/hong-sehyun/BeachInfo/assets/119600891/34fc1fd3-7409-41f0-b697-1d9c919d7598" align="center" width="32%">
  <img src="https://github.com/hong-sehyun/BeachInfo/assets/119600891/025091f3-d318-4d04-bbd0-656f36ddf2d6" align="center" width="32%">
  <img src="https://github.com/hong-sehyun/BeachInfo/assets/119600891/83e70959-2407-436d-95d5-081adf6dd7bb" align="center" width="32%">
</p>


