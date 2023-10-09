✍️ 구독 상품 구매 사이트 프로젝트
----   
>React와 Json Server 사용하여 진행한 프로젝트입니다.  

 <br>
  
![Dadok 메인화면](https://github.com/kwonminji-v/Dadok_Service_2/assets/124131332/b579d12a-947e-48f7-b8e1-0da1e0d43a1c)

<br>

## 목차

- [프로젝트 시작](#프로젝트-시작)
  - [프로젝트 소개](#1-프로젝트-소개)
  - [프로젝트 기능](#2-프로젝트-기능)
  - [사용 기술](#3-사용-기술)
  - [프로젝트 실행 화면](#4-프로젝트-실행-화면)
  
- [구조 및 설계](#구조-및-설계)
   - [패키지 구조](#1-패키지-구조)

- [개발 내용](#개발-내용)

- [프로젝트 리뷰](#프로젝트-리뷰)
  - [프로젝트 보완점](#1-프로젝트-보완점)
  - [후기](#2-후기)


---

### 프로젝트 시작  

<br>

   #### 1. 프로젝트 소개

코로나로 인해 비대면 서비스가 각광받으며, OTT 서비스 및 정기적으로 상품이나 서비스를 배송받을 수 있는 서비스가 급격히 발전하였습니다.   
초기 OTT 서비스들은 자사의 서비스 및 상품을 개발하는데 전념했지만, 많은 기업들이 해당 산업에 뛰어들게 되며, 많은 구독 서비스들이 파생되었습니다.  
소비자들은 여러 구독 서비스를 이용하고 싶으나, 개별로 가입을 하게되며 구독 상품 관리가 번거롭고 어렵게 되어 불편함이 증가하게 되었습니다.   
그래서 소비자가 원하는 각각의 구독상품을 묶어서 구매할 수 있는 서비스를 가지고 있는 사이트를 만들게 되었습니다.

<br>


   #### 2. 프로젝트 기능
   프로젝트의 주요 기능은 다음과 같습니다.

   - Main 화면 - 스크롤에 따라 시간차를 두고 변화하는 UI
   - 상품 장바구니 담기 - 상품을 장바구니에 담을 시 해당 상품의 데이터가 실제로 이동함
   - Json 서버를 이용해서 상품 불러오기

   #### 3. 사용 기술
   - React
   - Html / Css / JavaScript
   - Bootstrap

<br><br>
<br>
<br>
<br>
 
프로젝트에 사용한 언어 및 라이브러리 : HTML, CSS , JavaScript, React, node.js, MongoDB

프로젝트 주제 : 다양한 구독 서비스들을 제공받고, 구독 및 관리가능 사이트

발표 순서 
1) 프로젝트 기획의도 및 팀원 소개 , 페이지 구성 소개 : 주현준
2) 간략하게 전체 페이지 기능을 시연하며 소개 : 주현준
3) 서버 구축 단계 / 각각의 페이지 UI 구성 및 개인의 프로젝트 현황 개선사항 발표

 - 서버구축 및 mongoose 기능 : 주현준, 권혜연
 - 로그인 기능구현 및 DB연결 : 주현준
 - 게시판 기능구현 및 DB연결: 권혜연
 - 메인페이지 & 장바구니 UI와 기능구현 : 박재원
 - 상품 상세설명 페이지 & 마이페이지 UI와 기능 구현 : 권민지

4) 각자 소감 발표
5) QnA

파일 실행 순서
1.node.js를 설치해준다.
2. mongoDB를 https://www.mongoDB.com/try/download/community에 접속하여 프로그램을 다운받는다.
3. mongoDB Compass를 실행하여 해당 pc와 프로젝트 파일의 서버를 연결해주기
4. PC의 vscode로 프로젝트 폴더 open 
5.blog-backend 폴더의 터미널을 열어 라이브러리인 npm install mongoose를 설치해준다.
설명 : Mongoose는 Node.js와 MongoDB를 연결해주는 ODM

6.blog-backend 폴더의 터미널을 열어 npm install mongoose-auto-increment
설명 : 몽구스 플러그인 / DB에 글 작성시 작성된 글 개수를 바탕으로 자동으로 index숫자를 증가시켜줌

7. blog-frontend 폴더의 터미널을 열어서 추가 라이브러리 파일을 다운받기

설치 : npm install gsap
설명 : CSS 애니메이션 쉽고 간편하게 고성능의 이벤트를 적용할 수 있는 라이브러리 (플러그인 중 scroll event를 받는 친구 )

설치: npm install @reduxjs/toolkit
설명: Redux의 공식 도구 모음으로, Redux 관련 작업을 간소화합니다.

설치 : node.js
Node.js 에서 실행된다면 '런타임 환경' 은 Node.js 가 된다.

설치: npm install axios
"axios": "^1.3.3"
설명: HTTP 클라이언트 라이브러리로, API 요청을 쉽게 만들고 처리할 수 있습니다.


"bootstrap": "^5.2.3"
설명: 반응형 웹사이트 디자인을 쉽게 만드는 CSS 프레임워크입니다.
설치: npm install bootstrap

"react": "^18.2.0"
설명: 사용자 인터페이스를 구축하는 데 사용되는 JavaScript 라이브러리입니다.

설치: npm install react
"react-bootstrap": "^2.7.1"
설명: Bootstrap과 함께 사용되는 React 컴포넌트 모음입니다.

설치: npm install react-bootstrap
"react-dom": "^18.2.0"
설명: React를 웹사이트의 DOM에 렌더링하는 데 사용되는 라이브러리입니다.

설치: npm install react-dom
"react-redux": "^8.0.5"
설명: React 애플리케이션에서 Redux를 사용하는 데 필요한 바인딩 라이브러리입니다.

설치: npm install react-redux
"react-router-dom": "^6.8.1"
설명: 웹 애플리케이션에서 페이지 간 라우팅을 처리하는 React 라이브러리입니다.

설치: npm install react-router-dom
"react-scripts": "5.0.1"
설명: Create React App에서 사용되는 설정 및 스크립트 모음입니다.

설치: npm install react-scripts
"styled-components": "^5.3.6"
설명: 컴포넌트에 스타일을 적용하는 React 라이브러리입니다

npm install react-icons 
설명 : 아이콘을 이용해 ui를 표현할때, 라이브러리로 이용해 표현이 가능한 라이브러리

npm install swiper - swiper구동하기 위한 라이브러리

8. blog-backend 터미널에서 node src로 서버를 열어준다.
9. blog-frontend 터미널에서 yarn dev로 react 실행 및 json-server의 데이터를 불러와준다.

