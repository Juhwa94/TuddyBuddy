# AI 기반 학습 지원 서비스 TuddyBuddy
> TuddyBuddy는 내 학습 자료로 복습하고, 부족한 부분을 분석하며, 함께 공부할 환경을 하나의 서비스에 모으는 웹 프로젝트입니다. 자료로 문제를 만들고, 결과를 분석하고, 스터디룸에서 함께 학습하는 서비스입니다. 

## 👨‍🏫 프로젝트 소개
> 본 프로젝트는 학습의 단계를 연결하여 자신의 교재와 노트로 문제를 만들고, 풀이와 오답을 학습기록으로 남기는데 있습니다. 이 기록을 분석해 다음 학습에 참고하고, 스터디룸에서는 자료와 일정, 대화를 함께 관리합니다. 집중학습과 다이어그램, 버디봇은 이 흐름을 이어가는 보조 기능 입니다. 핵심 기능은 AI 개인 스터디와 그룹 스터디, 학습 통계, 출석과 친구추가, 커뮤니티, 버디봇 등의 기능을 제공합니다. 관리자는 회원과 콘텐츠, 신고와 이용 이력을 관리합니다.

## 🎥 시연 영상
> https://drive.google.com/file/d/17hqCNW51ySgNfkA7dnbhWFxA29OnCJ8q/view

## 🚀 배포 주소
https://13.124.197.107/
> - 프로젝트의 전체 기능은 시연 영상과 로컬 실행 환경에서 정상적으로 확인할 수 있습니다.
> - 배포 환경 이슈를 분석하며 CORS 설정, 환경변수, API 통신 구조를 개선하고 있습니다.

## 🎥 프리젠테이션
> https://drive.google.com/file/d/1RVuZHOM6F-uMSv-uUPhnQPE8G4NsPt0I/view

## 📚 DB 기획서
> https://docs.google.com/spreadsheets/d/1ab8Lfi0Dayt52mdYYhSwp01VyzFPjjUOFZnMaiPgcEs/edit?usp=sharing

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


## 📂 프로젝트 특징
> 1. AI 기반의 맞춤형 자기주도 학습 환경 : AI 개인스터디 기능을 통해 학습자의 수준과 성향에 맞춘 최적화된 학습 콘텐츠를 제공하며, 효율적인 개인별 맞춤 학습을 지원합니다.
> 2. 정밀한 학습 진단 및 피드백 체계 : 학습평가분석을 통해 학습 성취도와 취약점을 객관적으로 진단하고, 이에 기반한 피드백을 제공하여 지속적인 실력 향상을 유도합니다.
> 3. 온라인 가상 공부방을 통한 집중력 향상 : 스터디룸 공부방 기능을 제공하여 물리적 제약 없이 다른 학습자들과 함께 공부하는 분위기를 조성하고 학습 몰입도를 높입니다.
> 4. 지속적인 학습 습관 형성을 위한 출석 관리 : 출석 기능을 통해 매일의 학습 참여를 기록하고 관리함으로써, 학습자가 꾸준한 학습 루틴과 성실성을 유지할 수 있도록 돕습니다.
> 5. 소셜 기능을 통한 상호작용 및 동기 부여 : 친구추가 기능과 커뮤니티를 통해 학습자 간 정보 공유, 소통, 선의의 경쟁을 유도하여 혼자 하는 공부의 지루함을 줄이고 학습 동기를 강화합니다.
> 6. 체계적인 사용자 및 플랫폼 운영 관리 : 마이페이지로 개인별 학습 이력과 활동 내역을 직관적으로 관리할 수 있으며, 관리자페이지를 통해 전체 서비스 운영과 사용자 관리를 효율적으로 수행할 수 있습니다.
