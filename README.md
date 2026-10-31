# AI 기반 학습 지원 서비스 TuddyBuddy
> TuddyBuddy는 내 학습 자료로 복습하고, 부족한 부분을 분석하며, 함께 공부할 환경을 하나의 서비스에 모으는 웹 프로젝트입니다. 자료로 문제를 만들고, 결과를 분석하고, 스터디룸에서 함께 학습하는 서비스입니다. 

## 👨‍🏫 프로젝트 소개
> 본 프로젝트는 학습의 단계를 연결하여 자신의 교재와 노트로 문제를 만들고, 풀이와 오답을 학습기록으로 남기는데 있습니다. 이 기록을 분석해 다음 학습에 참고하고, 스터디룸에서는 자료와 일정, 대화를 함께 관리합니다. 집중학습과 다이어그램, 버디봇은 이 흐름을 이어가는 보조 기능 입니다. 핵심 기능은 AI 개인 스터디와 그룹 스터디, 학습 통계, 출석과 친구추가, 커뮤니티, 버디봇 등의 기능을 제공합니다. 관리자는 회원과 콘텐츠, 신고와 이용 이력을 관리합니다.

## 🎥 시연 영상
https://drive.google.com/file/d/17hqCNW51ySgNfkA7dnbhWFxA29OnCJ8q/view

## 🚀 배포 주소
https://13.124.197.107/
> - 프로젝트의 전체 기능은 시연 영상과 로컬 실행 환경에서 정상적으로 확인할 수 있습니다.
> - 배포 환경 이슈를 분석하며 CORS 설정, 환경변수, API 통신 구조를 개선하고 있습니다.

## 🎥 프리젠테이션
https://drive.google.com/file/d/1RVuZHOM6F-uMSv-uUPhnQPE8G4NsPt0I/view

## ⏲️ 개발 기간   
> - 2026.9.28(월) ~ 2026.10.28(수)
> - Oracle Database 연동
> - Spring Boot를 통한 세션과 결과 관리
> - React를 통한 UI/UX 업데이트 및 구현
> - AI 문제 생성 및 검증 흐름 구현
> - 커뮤니티 CRUD RESTful API 구현
> - Open API 카카오톡 로그인 구현
> - Docker를 통한 배포 환경 및 자동화 구현

  
## 💻 개발환경
> - **Frontend** : React 19.2.8, TypeScript, JavaScript, HTML5, CSS3, Bootstrap 5
> - **Backend** : Java 25, Spring Boot 4.1.0, MyBatis 4.0.1, SockJS, Spring MVC, Spring Data JDBC, WebSocket,<br>
 Spring Security, Spring Data Redis, STOMP, JWT
> - **Database** : Oracle 11g, Redis
> - **Language & AI** : Gemini, Groq, Python, LangChain, FastAPI, MediaPipe, OpenCV
> - **Server & Infra** : Docker, AWS EC2. Nginx, Kubernetes, Jenkins, Traefik
> - **API & Service** : PortOne API, SMTP 이메일 전송, 카카오 로그인 API, Google 뉴스 RSS
> - **OS & Development Tools** : Windows 11, Eclipse, Visual Studio Code, Ubuntu, Gradle, Yarn
> - **Databse & API Tools** : SQLGate, Postman, Swagger UI, JUnit
> - **Modeling & Design** : draw.io,Visual Paradigm, eXERD, PlantText
> - **UI & Libraries** :React Router DOM, Lucide React, Axios, Fullpage.js, React Flow, Motion, Swiper


## 📓 기능 정의
> - **AI 개인 스터디**
> - **학습평가분석**
> - **스터디룸**
> - **출석 기능**
> - **친구 기능**
> - **커뮤니티**
> - **알림 기능**
> - **마이페이지**
> - **관리자페이지**


## ⚙️ 기술 스택
> - **PL/SQL 신고 대상 조회 프로시저 작성**
> - **OpenCV MediaPipe 집중 감지 타이머 연동**
> - **Python FastAPI, Gemini API 기반 문제 생성**
> - **Groq API 기반 문제생성 교차 검증**
> - **Spring Boot, MyBatis, Oracle 기반 채점**
> - **LLM, RAG, Chroma 기반 학습 피드백 구현**
> - **PortOne SDK 연동 포인트 충전 구현**
> - **커뮤니티 카테고리 필터, 키워드 검색 구현**
> - **글 작성 모달, 내 게시글 조회 구현**
> - **로그인 기반 접근, 로딩, 오류 상태 처리**
> - **스터디룸 초대 가입, 강퇴, 방장 위임, 탈퇴 구현**
> - **할일 상태 변경, 메모, 파일 공유 구현**
> - **FastAPI/chat 질문 응답 API 연동**
> - **LLM, RAG, FAISS 기반 버디봇 구현**
> - **카카오 OAuth API 연동 소셜 로그인 구현**
> - **회원가입, 닉네임 중복 검증 구현**
> - **JavaMailSender SMTP 인증 메일 발송 구현**
> - **Redis 기반 인증 코드 만료, 시도 관리**

## 🧰 협업 도구
> - **Git**
> - **Github**
> - **Notion**
> - **Google Apps**
> - **Discord**
  

## 📌 주요 기능

> - AI 개인 스터디 : 사용자 학습 자료를 실제 문제 풀이와 복습을 연결하는 핵심 기능입니다. Python FastAPI는 Gemini와 Groq를 활용해 문제 생성과 검증을 수행합니다. 최종 결과는 Oracle에 저장합니다. Spring Boot는 요청을 받아 학습 세션을 관리하고, 문제 생성에 필요한 AI 호출과 답안 결과 저장을 연결합니다. 화면의 순서대로 이미지와 분류 입력, 문제 생성과 세션에 저장, 답안 채점과 결과 저장, 오답과 학습 기록 재조회가 이어집니다. 그리하여 화면 상태와 서버에 남는 학습 데이터를 나누어 관리해, 사용자가 풀이를 마친 뒤에도 같은 학습 내용을 다시 확인할 수 있도록 했습니다.
> - 학습평가분석 : 평가분석은 누적된 학습 결과를 다음 공부의 참고 자료로 바꾸는 기능입니다. 사용자가 분석을 요청하면 프론트는 인증 정보와 필요한 요청값을 서버에 전달합니다. 컨트롤러는 요청을 서비스로 넘기고, 서비스는 포인트 차감과 성적 이력 조회를 진행합니다. 분석에 필요한 데이터를 AI 서버에 전달하고 결과를 받으면, 분석 내용과 차트 데이터를 하나의 응답으로 묶어 반환합니다. 프론트는 이 응답으로 분석 결과를 표시합니다.
> - 스터디룸 : 스터디룸은 함께 공부할 대상을 찾고 협업하는 공간입니다. 태그로 원하는 스터디룸을 검색하고, 공개, 비공개 설정으로 참여 방식을 구분합니다. 비공개 방은 초대코드로 참여합니다. 참여한 멤버는 이후 소개할 일정과 할 일, 자료와 대화를 같은 공간에서 관리합니다. 기능별 메뉴를 분리하면서도 하나의 스터디룸에 연결해 공동 학습의 흐름을 만들었습니다. 서브 기능으로는 해야할일, 다이어그램, 일정, 참고자료, 질의응답, 메모 등의 기능들이 있습니다.
> - 출석 기능 : 출석시 포인트 지급의 기능도 제공합니다. 출석 요청은 로그인 처리 상태를 확인하고 잠금으로 중복 클릭을 막습니다. 출석 회원은 요청값이 아닌 서버의 로그인 인증 정보로 결정합니다. 그 외에 React로 구현한 달력에 월별 출석 기록과 서버 기준 오늘을 표시합니다. 서버의 지급 성공 응답을 확인한 뒤 300P 보상 팝업을 보여줍니다.
> - 친구 기능 : 
> - 커뮤니티 : 
> - 알림 기능 : 
> - 마이페이지 : 
> - 관리자페이지 : 



## 📂 프로젝트 특징
> 1. 비즈니스 로직(Model), 사용자 인터페이스(View), 흐름 제어(Controller)의 명확한 역할 분리로 MVC 패턴 기반의 높은 확장성을 구현했습니다.
> 2. 단순 상품 판매가 아닌, 도서 유통 구조(ISBN, 출판사, 발주 체계)를 깊이 이해하고 반영한 리테일러 전용 솔루션을 구현했습니다.
> 3. 입고 ➔ 재고 ➔ 판매 ➔ 발주 ➔ 정산으로 이어지는 유통 및 관리 전 과정을 하나의 플랫폼에서 처리하여 운영 라이프사이클의 원스톱을 통합하였습니다.
> 4. 직관적인 데이터 시각화를 통해 재고 과다/부족 리스크를 줄이고 효율적인 매장 운영 판단 지원하여 데이터 기반의 인사이트를 구축했습니다.
> 5. 복잡한 수치와 재고 목록을 단번에 파악할 수 있는 사용자 친화적 대시보드 및 워크플로우 구성하여 직관적인 UI/UX를 구현했습니다.
