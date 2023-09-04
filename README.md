# SpringBoot-Project-WINWIN
태그를 활용한 진로 탐색 사이트


## 🖥️ 프로젝트 소개
다양한 진로 정보를 편하게 탐색할 수 있는 사이트를 만들어보자!
<br>

## 🕰️ 개발 기간
* 23.06.07 ~ 23.07.21

### 🧑‍🤝‍🧑 맴버구성
 - 팀장  : 정소이 - 메인페이지, 로그인/회원가입, 마이페이지(쪽지함), 발표, PPT
 - 팀원1 : 최예은 - DB설계, 멘토:멘티 게시판, 마이페이지(내 기록, 내 멘토:멘티)
 - 팀원2 : 조현호 - DB설계, 마이페이지(게시판별 활동내역, 진로정보 스크랩, 이력서 및 자기소개서 관리, 회원 정보 수정)
 - 팀원3 : 김병구 - 나눔 게시판, 진로정보 게시판, PPT
 - 팀원4 : 원창식 - 1대1 문의사항
 - 팀원5 : 이상진 - 커뮤니티(타임라인, 직장인, 대학생, 고등학생), Q&A 게시판
 - 팀원6 : 최성진 - 모임(스터디, 프로젝트) 게시판
 - 팀원7 : 김에스더 - 관리자 페이지, Q&A 게시판

### ⚙️ 사용 기술
- **개발환경** : 스프링 부트 5
- **개발도구** : git, intelliJ, vsCode, Dbeaver
- **개발언어 및 프레임워크** : java, ajax, html, css, javaScript, myBatis, spring boot, thymeleaf
- **DB** : Oracle
- **API** : 네이버 클라우드 SMS API

## 📌 주요 기능
#### 로그인 - <a href="https://github.com/chaehyuenwoo/SpringBoot-Project-MEGABOX/wiki/%EC%A3%BC%EC%9A%94-%EA%B8%B0%EB%8A%A5-%EC%86%8C%EA%B0%9C(Login)" >상세보기 - WIKI 이동</a>
- DB값 검증
- ID찾기, PW찾기
- 로그인 시 쿠키(Cookie) 및 세션(Session) 생성
#### 회원가입 - <a href="https://github.com/chaehyuenwoo/SpringBoot-Project-MEGABOX/wiki/%EC%A3%BC%EC%9A%94-%EA%B8%B0%EB%8A%A5-%EC%86%8C%EA%B0%9C(Member)" >상세보기 - WIKI 이동</a>
- 주소 API 연동
- ID 중복 체크
#### 마이 페이지 - <a href="https://github.com/chaehyuenwoo/SpringBoot-Project-MEGABOX/wiki/%EC%A3%BC%EC%9A%94-%EA%B8%B0%EB%8A%A5-%EC%86%8C%EA%B0%9C(Member)" >상세보기 - WIKI 이동</a>
- 주소 API 연동
- 회원정보 변경

#### 영화 예매 - <a href="https://github.com/chaehyuenwoo/SpringBoot-Project-MEGABOX/wiki/%EC%A3%BC%EC%9A%94-%EA%B8%B0%EB%8A%A5-%EC%86%8C%EA%B0%9C(%EC%98%81%ED%99%94-%EC%98%88%EB%A7%A4)" >상세보기 - WIKI 이동</a>
- 영화 선택(날짜 지정)
- 영화관 선택(대분류/소분류 선택) 및 시간 선택
- 좌석 선택
- 결제 페이지
- 예매 완료
#### 메인 페이지 - <a href="https://github.com/chaehyuenwoo/SpringBoot-Project-MEGABOX/wiki/%EC%A3%BC%EC%9A%94-%EA%B8%B0%EB%8A%A5-%EC%86%8C%EA%B0%9C(%EB%A9%94%EC%9D%B8-Page)" >상세보기 - WIKI 이동</a>
- YouTube API 연동
- 메인 포스터(영화) 이미지 슬라이드(CSS)
#### 1대1문의 및 공지사항 - <a href="" >상세보기 - WIKI 이동</a> 
- 글 작성, 읽기, 수정, 삭제(CRUD)

#### 관리자 페이지 
- 영화관 추가(대분류, 소분류)
- 영화 추가(상영시간 및 상영관 설정)
