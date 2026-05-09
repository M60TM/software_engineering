# software_engineering
홍익대학교 소프트웨어 공학 2분반 21조

## 파일 관리
- use case diagram은 starUML로 작업
- use case description과 requirement list는 md 파일을 수정, 이후에 word -> pdf로 변환 작업 거칠 거임
- figma로 작업한 UI 이미지를 커밋, 이후에 pptx -> pdf로 변환 작업 거칠 것임

## Branch Convention

브랜치는 작업 단위별로 생성한다.

### 형식

작업유형/UC번호-기능명-이름

### 예시

docs/UC-01-signup-jaemin

docs/UC-05-survey-create-gihyeon

docs/UC-09-survey-search-byeongseon

docs/UC-11-survey-response-uijin

### 작업 유형

docs: 요구사항, use case description 등 문서 작업
ui: Figma 화면, UI 관련 파일 작업
uml: Use Case Diagram 작업
fix: 오타, 누락, 오류 수정
chore: 폴더 정리, 제출 파일 정리 등 기타 작업

---

## Commit Message Convention

커밋 메시지는 아래 형식을 따른다.

### 형식

type(scope): 작업 내용

### type 종류

docs: requirement list, use case description 등 문서 작성
ui: UI 화면 작성 및 수정
uml: use case diagram 작성 및 수정
fix: 오타, 누락, 잘못된 내용 수정
chore: 폴더 구조 정리, 제출 파일 정리

### scope 규칙

scope에는 UC 번호 또는 문서 이름을 작성한다.

예시:
UC-01
UC-05
requirement-list
usecase-diagram
description
ui

---

## Commit Message Example

docs(UC-01): 회원 가입 requirement list 작성

docs(UC-01): 회원 가입 use case description 작성

ui(UC-01): 회원 가입 UI 화면 초안 추가

uml(usecase-diagram): 회원 가입 use case diagram 반영

fix(UC-09): 설문 검색 description 단계 수정

chore(submit): 제출용 파일 구조 정리

---

## 작업 규칙

1. 각 팀원은 본인이 맡은 Use Case 단위로 작업한다.
2. 각 팀원은 반드시 최소 1회 이상 commit을 남긴다.
3. 한 커밋에는 하나의 작업만 포함한다.
4. 커밋 메시지만 봐도 어떤 Use Case를 작업했는지 알 수 있게 작성한다.
5. 최종 제출 전 main branch에 모든 작업물을 병합한다.

---

## Folder Convention

/HW1

|

|- /requirement-list

| 

|- /usecase-description

|  

|- /usecase-diagram

|  

|- /ui