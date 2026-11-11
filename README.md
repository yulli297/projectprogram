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
- `TEACHER_PW` : 선생님 화면 비밀번호 (모든 반 같음)
- `CLASS_CODE` : 반 입장 코드 (1반 2026601 … 5반 2026605)

## 입장 방식
- 학생: 반 → 모둠 → 이름 → 반 입장 코드
- 처음 쓰는 이름은 한 번 더 확인해요. 잘못 친 이름은 선생님 화면에서 [지우기]해요.
