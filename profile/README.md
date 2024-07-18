# 🤖 Gwelcome(경기웰컴)

![151801657](https://github.com/Gwelcome/.github/assets/56792033/6820cd1c-1ab1-4fc6-a1e3-36e4a6ac5dbf)

## 서비스 소개
 경기도에 거주하는 청년들을 위한 맞춤형 정책 추천 및 상담 서비스로, 조건에 맞는 청년 정부 정책에 대한 정보를 쉽게 접할 수 있도록 하는 AI 상담 서비스 <b>경기웰컴(G-Welcome)</b>입니다.

 경기웰컴은 <i>생성형 AI를 활용한 질의문답 서비스</i>와 <i>사용자 맞춤 정책 추천 서비스</i>를 제공합니다.
 
 24시간 이용이 가능하여 접근성이 높고, 정책 사이트룰 기반하여 신뢰성 높은 서비스를 제공하는 것을 목표로 합니다. 
## 프로젝트 소개
#### 프로젝트 기간
2023.11 ~ 2023.12
#### 프로젝트 팀원
|name|position|
|------|---|
|서지현|백앤드|
|배준우|프론트엔드|
|손승우|프론트엔드|
|김채인|기획 및 챗봇개발|
|김강민|챗봇 개발|

## 시스템 아키텍처
<img width="568" alt="image" src="https://github.com/user-attachments/assets/b80f51b3-38bf-4ffb-94b5-773e4142fd6b">

## 주요 기능

#### 1. 사용자 정보 기반 맞춤 정책 추천

Faiss 활용한 유사도 기반 맞춤 정책 검색

<img width="280" alt="image" src="https://github.com/user-attachments/assets/bdc3f100-4ef1-4ca3-91af-935737f65b4f">

#### 2. 챗봇

<i>사용자의 정책 관련 질문에 대한 답변을 제공</i> (GPT API 이용한 프롬프트 엔지니어링)

Faiss 활용한 유사도 계산 모듈을 통해 <i>사용자 질문과 유사한 3가지 FAQ 데이터 제공</i>

<img width="300" alt="image" src="https://github.com/user-attachments/assets/8492e667-4dcd-4b27-b12c-04bc84328d57">

#### 3. 댓글 기능을 통한 커뮤니티 활성화

#### 4. 정책 스크랩 기능 - 서비스 편의성 향상

## 시연 영상 (클릭 시 유튜브로 이동)

[![Video Label](http://img.youtube.com/vi/uULZv4cSsiA/0.jpg)](https://youtu.be/uULZv4cSsiA)

## ETC
<a href="https://github.com/Gwelcome/GwelcomeBackend"> 백엔드 레포지토리 readme 바로가기 </a>
<details>
<summary>AI 챗봇 기능 구현 방식</summary>
<div markdown="1">
<br>
<a href="https://github.com/Gwelcome/chatbot"> GPT API를 활용한 답변 생성 모듈 (프롬프트 엔지니어링) </a>
<br>
<a href="https://github.com/Gwelcome/Gwelcome_FAQ"> 잘문과 FAQ(자주 묻는 질문)에 대한 유사도를 검사하여 유사한 질문 3개를 반환</a>
</div>
</details>

