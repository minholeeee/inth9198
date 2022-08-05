### Hi there 👋

## 백준 티어

[![Solved.ac Profile](http://mazassumnida.wtf/api/generate_badge?boj=inth9198)](https://solved.ac/inth9198)


# 진행한 프론트엔드 프로젝트
#취업사관학교


## 프로젝트 설명




유전체 정보 기반으로 큐레이션 및 의견을 공유할 수 있는 플랫폼
(인턴 진행하면서 참여함)

## 디자인

[https://www.figma.com/file/QBPcVJ7cBvHafi7OybH0Ud/OncoReader?node-id=2%3A312](https://www.figma.com/file/QBPcVJ7cBvHafi7OybH0Ud/OncoReader?node-id=2%3A312)

## 프로젝트 스킬 스택

- next.js - react framework
- redux(redux-saga) - status management
- emotion - css-in-js(style library)
- formik - form control library
- material-ui - ui library

## 프로젝트 구조

- components - 원소가 되는 컴포넌트 목록
- container - 컴포넌트를 모아서 만든 컴포넌트(특수화)
- hooks - 커스텀하게 만든 훅들
- models - type definition들
- pages - page 컴포넌트(라우팅)
- public - static 자원(이미지...등등)
- server - 프론트엔드 서버 커스터마이징 파일
- shared - 공통적으로 공유되는 정보들
- store - reducer & saga 연동 파일
- utils - 공통 사용 유틸 목록

# API연동하기

1. 관련 api 접근 모듈 생성 - api/*.ts
2. 액션타입선언 - actions/types/*.ts
3. 액션 생성 함수 선언 & 액션 생성 함수 타입 - actions/*.ts
4. 액션 객체들에 대한 타입 준비 (ReturnType) - actions/*.ts
5. 초기 상태 선언 & 상태의 타입 - reducers/*.ts
6. 리듀서 작성 - reducers/*.ts
7. 비동기 상태 핸들링 사가(미들웨어) 생성 - sagas/*.ts
8. api 호출 (액션 명령 실행) - 각컴포넌트/*.tsx

## 프로젝트 실행

- 개발 시(로컬환경) - npm run dev
- 정적 분석 테스트 - npm run lint
- 빌드 테스트 - npm run build
- 빌드파일 실행 테스트 - npm run start

## 프로젝트 배포

1. 새로운 작업 시 작업에 맞는 브랜치를 생성한다.
2. 작업이 완료 된 브랜치를 원격에 올린다.
3. merge request to develop 를 생성한다.
4. merge가 승인되면 자동 배포됨.

## CS공부 노션
https://www.notion.so/171722de241544698e075f5fe42d06ce

## 네이버 블로그
https://blog.naver.com/inth2474

## 클래스액트 인턴(특허 기여)

임상 참여 조건의 정형화를 위한 데이터 파이프라인 처리방법
1) 진행기간 : 2022/03/02~2022/06/30
2) 주요내용 : 환자에게 임상실험을 추천하는 알고리즘 (특허)
3) 출원 번호 : 10-2022-0067882
4) 논문명칭 : 임상 참여 조건의 정형화를 위한 데이터 파이프라인 처리방법
5) 본인이 기여한 점 : 모든 파이프 라인에 대한 코드 구현
6) 사용한 기술스택 및 지식 : 파이썬(주피터 노트북, pandas, numpy)
7) 결과 및 성과 : 이전 임상 실험 추천 시스템보다 더욱 구체화된 환자에 맞춤형 임상 실험 추천하는 파이프라인 구축

## 임상 참여 조건의 정형화를 위한 속성인식방법

1) 진행기간 : 2022/03/02~2022/06/30
2) 주요내용 : 환자에게 임상실험을 추천하는 알고리즘 (특허)
3) 출원 번호 : 10-2022-0067881
4) 논문명칭 : 임상 참여 조건의 정형화를 위한 속성인식방법
5) 본인이 기여한 점 : 모든 파이프 라인에 대한 코드 구현
6) 사용한 기술스택 및 지식 : 파이썬(주피터 노트북, pandas, numpy)
7) 결과 및 성과 : 이전 임상 실험 추천 시스템보다 더욱 구체화된 환자에 맞춤형 임상 실험 추천하는 파이프라인 구축을 위해 환자의 속성을 인식하는 방법

## 클래스액트 인턴(논문 참여)

1) 진행기간 : 2022/03/02~2022/06/30
2) 주요내용 : 부정을 처리하는 알고리즘 논문(예정)
3) 본인이 기여한 점 : 부정을 처리하는 알고리즘에 대한 모든 코드 적 부분의 구현과 여러 알고리즘 추가
4) 사용한 기술스택 및 지식 : 파이썬(주피터 노트북, pandas, numpy)
5) 결과 및 성과 : 이전에 부정을 처리하는 알고리즘 negex, deepen 에 비하여 더 좋은 성능을 나타냄 (더 높은 accuracy, 더 높은 precision, 더 높은 recall, 더 높은 f1, 더 적은 loss)
