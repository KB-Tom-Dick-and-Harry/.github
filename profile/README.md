# 세상을 바꾸는 소프트웨어 케이비케이션

---

![케이비케이션 서비스](https://github.com/user-attachments/assets/7b0e7ad3-8264-4af6-8cf0-712a972d586d)


## 💬 프로젝트 개요

---

**본 프로젝트는 20대 청년층의 낮은 금융 이해력과 지식을 개선하기 위해 금융 교육과 게임을 결합한 플랫폼을 개발하여, 사용자들이 재미있게 금융 지식을 습득하고 실제 금융 서비스 이용을 활성화하는 것을 목표로 합니다.**

---

## 🧑‍🤝‍🧑 팀원 구성

---

| 김시완 | 김동준 | 최규찬 | 김수민 | 김연비 | 김연지 | 이태웅 |
| --- | --- | --- | --- | --- | --- | --- |
| ![김시완](https://avatars.githubusercontent.com/u/170385125?v=4) | ![김동준](https://avatars.githubusercontent.com/u/122508669?v=4) | ![최규찬](https://avatars.githubusercontent.com/u/169640483?v=4) | ![김수민](https://avatars.githubusercontent.com/u/170384833?v=4) | ![김연비](https://avatars.githubusercontent.com/u/171995592?v=4) | ![김연지](https://avatars.githubusercontent.com/u/165933276?v=4) | ![이태웅](https://avatars.githubusercontent.com/u/169640990?v=4) |
| PM & Front End & Back End | Front End | Front End & UX/UI | Back End | Back End | Back End | Back End & AI |

### 🗓️ 개발 기간

---

2024.11.01 ~ 2024.11.04

- 아이디어 회의
- 개발 기획
- UI 설계

2024.11.05 ~ 2024.11.07

- 데이터베이스 스키마 설계
- UI 설계 및 수정
- 기능 명세서 작성
- API 명세서 작성

2024.11.11 ~ 2024.11.19

- 백엔드 개발 및 프론트엔드 개발

2024.11.20 ~ 2024.11.22

- 백엔드 프론트엔드 API 연동 및 디버깅
- 프로젝트 발표 준비
- 프로젝트 발표

## 💻 개발 환경 및 기술

---

- Front End : Vue.js, TypeScript, CVA(Class-Variancem-authority), Shadcn-Vue
- Back End : Spring Boot(3.3.5), JWT(0.12.3), Spring Security(6.3.4), Gradle(8.10.2)
- AI : Langchain, Chroma DB, Gpt4-o
- 버전 관리 및 이슈 관리 : GitHub
- 협업 툴 : Notion, Slack, Discord
- 배포 : AWS EC2
- UI/UX : Figma

## 📎 협업 과정

---

매주 1회씩 스크럼을 진행하며 진행상황을 공유. 컨벤션을 정해서 협업의 효율을 증대.

### 🧑🏻‍💻 브랜치 컨벤션

| 주요 브랜치 | 브랜치명 | 설명 |
| --- | --- | --- |
|  | develop | 기본 디폴트 브랜치 |
| 서브 브랜치 |  |  |
|  | feature/** | 기능 구현 브랜치 |
|  | hotfix/** | 긴급 수정 브랜치 |
|  | refactor/** | 리팩토링 브랜치 |

ex) `feature/login` : 로그인 기능 구현 브랜치

### 🗒️ 커밋 컨벤션

| `:tada:` | 🎉 | Init |  |
| --- | --- | --- | --- |
| `:sparkles:` | ✨ | Feat | 기능 구현 첫 커밋 할 때 |
| `:pencil2:` | ✏️ | Fix | 자잘한 코드 수정 |
| `:art:` | 🎨 | Refactor | 코드 수정 (기능 수정 없이 이쁘게 최적화) |
| `:ambulance:` | 🚑 | Hotfix | 급하게 치명적인 버그를 고쳐야하는 경우 |
| `:rewind:` | ⏪️ | Revert | 변경 사항 되돌리기 |
| **`:memo:`** | 🗒️ | docs | 문서 수정 (문서 추가, 수정, 삭제, README) |
| `:wrench:` | 🔧 | chore | 기타 변경사항 (빌드 스크립트 수정, assets, 패키지 매니저 등) |
| `:label:` | 🏷️ | rename | 파일 혹은 폴더명을 수정하거나 옮기는 작업만 한 경우 |
| `:coffin:` | ⚰️ | remove | 파일을 삭제하는 작업만 수행한 경우 |

### 💬 이슈 컨벤션

<aside>
💬 **`recommend`** **`custom`** **`not used`**

</aside>

🐛 **`bug`** : 버그 관련 Issue == 예기치 않은 문제 또는 의도하지 않은 동작이 발생

🛠️ **`fix`** : 버그 수정 관련 Issue == 버그 해결 등 기능 및 동작에 대한 수정

🔨 **`refactoring`** : 동작 결과에 대한 변경 없이 로직, 변수명 등을 변경

✨ **`feature`** : 새로운 기능 추가 관련 Issue == 기능 구현

---

✅ **`test`** : test 관련 Issue

📑 **`documentation`** : 문서화 관련 Issue == 문서 작성 및 수정

🎨 **`style`** : UI 관련 Issue에 사용

### 🗒️ PR 컨벤션

### Reviewer’s To-Do List

1. source-target 브랜치 확인
2. 코드 리뷰 꼼꼼히 하기
3. approve 하거나 리뷰 적기 (둘다 해도 좋음)
4. 백엔드, 프론트는 작성자 제외하고 1명 이상의 approve를 얻어야 merge 가능

### Merge Request Body Template

<JIRA Issue Number> Header의 설명

```markdown
## 🔎 Summary

## 📑 Description

## ✅ Check List
- 소스-타겟 브랜치 확인하기
- 코드 리뷰하기
```

## 📎 데이터베이스 ERD

---

<img width="1027" alt="ERD" src="https://github.com/user-attachments/assets/62fe34ab-c917-4044-bc79-7f3c21dc1f3d" />


## ⚙️ 아키텍쳐 다이어그램

---

![아키텍쳐](https://github.com/user-attachments/assets/cc368caa-21e3-4e4f-831d-8fd72d03d00f)


## 🔎 서비스 기능

---

### ✏️ 회원가입

![회원가입](https://github.com/user-attachments/assets/88af5099-fc07-4ba0-a779-8a3746760a15)

- 일반 로그인 화면에서 시작하여 기본 회원정보를 입력
- 서비스 이용을 위한 필수 약관 동의


### 📎 메인 화면 - 퀴즈 시작

![메인 화면 - 퀴즈 시작](https://github.com/user-attachments/assets/592a826b-70ac-4b78-a14b-17b591f2582b)


- 사용자에게 일일 3회의 퀴즈 게임 기회 제공
- 메인 화면 상단에 '도전하고 포인트 받기' 버튼을 통해 퀴즈 게임 시작
- 현재 보유한 총 자산과 포인트 현황 표시
- 최근 거래 내역에서 최근 3건의 소비 내역을 시간순으로 표시
 

### 📎 퀴즈 화면

![퀴즈 화면](https://github.com/user-attachments/assets/a2353855-a454-41f8-9674-de5061c1d96a)

- 상단에 현재 퀴즈 진행 상황을 표시 (1/3)
- 4개의 선택지 중 정답을 고르는 객관식 퀴즈 형식
- 정답/오답 여부에 따른 피드백 메시지 제공
- 퀴즈 완료 시 획득한 포인트(1,000P) 표시


### 📎 챗봇 화면

![챗봇 화면](https://github.com/user-attachments/assets/018eda4d-6827-4373-98a9-1ce49e0f2820)

- 메인 화면의 최근 소비 내역에서 특정 거래 선택 시 챗봇 상담 시작
- AI 챗봇과의 대화형 인터페이스를 통해 카드 추천 서비스 제공
- 챗봇이 사용자의 소비 패턴을 분석하여 맞춤형 신용카드 추천
- 카드 추천 시 해당 카드의 주요 혜택과 특징을 상세히 설명


## ⛏️ 이슈 해결 및 트러블 슈팅

---

CODEF API 연동 문제
- 문제: API 호출 시 CORS 정책으로 인한 접근 제한 발생
- 해결: Spring Security 설정에서 CORS 관련 설정 추가
