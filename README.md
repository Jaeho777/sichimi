# Sichimi

지역 시장 탐색과 방문 경험을 연결하는 프런트엔드 실험 저장소입니다. Notion 프로젝트 기록의 **마케토리** 콘셉트(지도·가게 상세·TMI·Visit + Story·AI 기능)를 정리하기 위한 개인 저장소입니다.

[![React](https://img.shields.io/badge/React-19-61dafb?logo=react&logoColor=20232a)](https://react.dev/)
[![Vite](https://img.shields.io/badge/Vite-7-646cff?logo=vite&logoColor=white)](https://vite.dev/)
[![License](https://img.shields.io/badge/status-experimental-f59e0b)](#현재-상태)

## 현재 상태

이 저장소는 실험·보관용 스냅샷입니다. 현재 커밋에는 `sichimi/src/main.jsx`와 화면 컴포넌트가 포함되어 있지 않아 바로 실행되는 완성 앱으로 보지 않습니다. 기능을 복원하거나 팀 저장소를 이어받을 때 이 사실을 먼저 확인합니다.

- 구현 목표: 지도 중심 시장 탐색, 가게·카테고리 상세, Visit + Story, AI 콘텐츠 연동
- 기술 방향: React, Vite, JavaScript, API 연동
- 수상 기록: 2025 한동 SW 페스티벌 우수상(프로젝트 기록 기준)
- 원본 팀 저장소: [LikeLionHGU/Shichimi_Front](https://github.com/LikeLionHGU/Shichimi_Front)

## 폴더 구조

NaNtext
sichimi/
├─ package.json
├─ vite.config.js
├─ index.html
└─ src/
   ├─ App.css
   └─ index.css
NaN

## 개발 환경

NaNbash
cd sichimi
npm install
npm run dev
NaN

현재 상태에서는 `src/main.jsx`가 없어 Vite 실행·빌드가 실패할 수 있습니다. 팀 저장소에서 최신 소스를 가져온 뒤 아래 검사를 실행합니다.

NaNbash
npm run lint
npm run build
NaN

## 유지보수 메모

- API 키와 `.env` 파일은 커밋하지 않습니다.
- 화면 기능을 복원할 때 지도·가게 상세·AI 요청 실패 상태를 먼저 검증합니다.
- 디자인·반응형·API 연결 변경은 기능별 커밋으로 나눕니다.
- 완성된 배포본은 이 저장소의 실험 스냅샷과 구분해 기록합니다.

## 관련 프로젝트

- [VIC LMS](https://github.com/Jaeho777/vic-lms)
- [SCM Agent](https://github.com/Jaeho777/scm_agent)
