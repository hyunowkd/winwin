# SpringBoot-Project-WINWIN
태그를 활용한 진로 탐색 사이트

## 🖥️ 프로젝트 소개
다양한 진로 정보를 편하게 탐색할 수 있는 사이트를 만들어보자!

## 🕰️ 개발 기간
* 23.06.07 ~ 23.07.21

### 🧑‍🤝‍🧑 맴버구성
 - 팀장 : 정소이 - 메인페이지, 로그인/회원가입, 마이페이지(쪽지함), 발표, PPT
 - 부팀 : 최예은 - DB설계, 멘토:멘티 게시판, 마이페이지(내 기록, 내 멘토:멘티)
 - ***IT'S ME! : 조현호 - DB설계, 마이페이지(게시판별 활동내역, 진로정보 스크랩, 이력서 관리, 회원 정보 수정)***
 - 팀원 : 김병구 - 나눔 게시판, 진로정보 게시판, PPT
 - 팀원 : 원창식 - 문의사항
 - 팀원 : 이상진 - 커뮤니티(타임라인, 직장인, 대학생, 고등학생), Q&A 게시판
 - 팀원 : 최성진 - 모임(스터디, 프로젝트) 게시판
 - 팀원 : 김에스더 - 관리자 페이지, Q&A 게시판

### ⚙️ 사용 기술
- **Front-End** : HTML, CSS, JavaScript
- **Back-End** : Java
- **DB** : Oracle
- **FrameWork** : Ajax, MyBatis, Spring Boot, thymeleaf
- **Devops**: GitHub
- **API** : SMS API

## 📌 주요 기능
#### *마이 페이지 - <a href="https://github.com/hyunowkd/winwin/wiki/%EC%A3%BC%EC%9A%94-%EA%B8%B0%EB%8A%A5-%EC%86%8C%EA%B0%9C(%EB%A7%88%EC%9D%B4%ED%8E%98%EC%9D%B4%EC%A7%80)">THIS IS MY PART! 상세보기</a>*
- 게시판별 활동내역(게시글/댓글)
- 좋아요 누른 진로정보 게시글 모아보기
- 무한스크롤
- 이력서/자기소개서 관리 및 pdf 다운로드
- 회원 정보 변경
- 쪽지함
- 내 기록(오픈소스 summerNote 활용한 메모장 기능)

#### 로그인, 회원가입
- ID 중복체크, ID 찾기, PW 찾기
- 멘토 권한 부여 전 증명서류 받기
- 로그인 시 세션(Session) 생성
- 위 과정을 모달창으로 구현

#### 멘토:멘티
- 멘토 프로필 리스트
- 멘토 신청
- 멘토에게 쪽지 보내기
- 좋아요 기능
  
#### 진로정보
- 태그 검색 기능
- 글 작성/수정/삭제(멘토만 가능)
- 오픈소스 summerNote 활용
- 추천/좋아요 기능
- 댓글 기능
- 신고하기

#### Q&A
- 태그 검색 기능
- 글 작성/수정/삭제
- 인증 태그 보유자만 답변 가능
- 신고하기

#### 커뮤니티
- 무한스크롤
- 글 작성/수정/삭제
- 인기순으로 게시글 조회
- 신고하기

#### 모임
- 오픈채팅 링크 연결
- 글 작성/수정/삭제
- 좋아요, 인기순으로 게시글 조회
- 신고하기

#### 나눔
- 포인트 결제 기능
- 글 작성/수정/삭제
- 쪽지 기능
- 신고하기
  
#### 문의사항
- 글 작성, 읽기, 수정, 삭제(CRUD)
- 관리자만 답변 가능

#### 관리자 페이지 
- 회원관리 : 회원 검색, 회원 상태 변경
- 게시판 관리 : 게시판 검색 기능, 글 상태 변경
- 포인트 관리 : 회원 검색 기능
- 신고 관리 : 게시글 검색 기능, 글 상태 변경
