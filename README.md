# SpringBoot-Project-HENOAIROCK
스프링 부트 + JSP 파싱_감정분석(노래추천) 사이트


## 🖥️ 프로젝트 소개
유저들의 감정을 분석해 노래를 추천해주는 사이트입니다.
<br>

## 🕰️ 개발 기간
* 23.07.06일 - 23.08.29일

### 🧑‍🤝‍🧑 맴버구성
 - 팀장   : 구자민 - 전체적인 DB 구축 및 백엔드 기능구현, KOBERT 학습 및 모듈 이식
 - 부팀장 : 김주명 - 전체적인 프론트엔드 기획 및 설계, 전체적인 피그마 제작
 - 팀원   : 양도헌 - 게시판 프론트엔드, 백엔드 설계 및 구현, 감정 분류 데이터셋, 음악 좋아요 버튼생성, 피그마 검토 및 PPT제작
 - 팀원   : 김지원 - 관리자관련페이지 프론트엔드 기획 및 설계, 음악순위 페이지 프론트엔드 기획 및 설계
 - 팀원   : 김형준 - 전체적인 DB구축 및 백엔드 기능구현, 마이페이지 관련 백엔드 기능 구현
 - 팀원   : 김혜성 - 음악 라벨링 분류 작업
 - 팀원   : 오성철 - 게시판 관련 프론트엔드와 백엔드 구현, 설정페이지 백엔드로 연결


### ⚙️ 개발 환경
- `Java 8`
- `JDK 1.8.0`
- **IDE** : STS 3.9
- **Framework** : Springboot(2.x)
- **Database** : Oracle DB(11xe)
- **ORM** : Mybatis

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
