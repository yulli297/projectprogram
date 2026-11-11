# 그린 아크(Green Ark) 프로젝트

6학년 4차시 프로젝트 수업용 웹 프로그램 (탐색 → 설계 → 건물 → 마을).

## 실행
```
npm install
npm start
```
Render: Build Command `npm install`, Start Command `npm start`

## 설정 (`public/index.html` 맨 위)
- `FIREBASE_CONFIG` : Firebase 웹 앱 설정 (비워 두면 체험 모드, 기기 안에만 저장)
- `CLASS_COUNT` : 반 수 (반마다 데이터가 따로 저장돼요)
- `TEACHER_PW` : 반별 선생님 화면 비밀번호

## 입장 방식
- 학생: 반 → 모둠 → 이름 → 반 입장 코드 → 내 비밀번호(숫자 4자리, 처음 들어올 때 정함)
- 반 입장 코드는 각 반 선생님이 선생님 화면에서 정해요.
- 비밀번호를 잊은 학생은 선생님 화면의 모둠 살펴보기에서 [초기화]해요.
- `UNLOCK_ALL` : true면 모든 단계가 열린 확인용 화면
- `GROUP_COUNT` : 모둠 수

사례 카드 사진은 `public/img/`에 있어요.
