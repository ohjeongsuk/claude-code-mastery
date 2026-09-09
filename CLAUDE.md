# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## 프로젝트 상태

현재 프로젝트는 초기 단계(Phase 0)입니다. 실제 소스 코드, 빌드 설정, 테스트 환경 등이 아직 추가되지 않았습니다.

## 프로젝트 개요

**개발자 웹 이력서** - HTML, CSS, JavaScript, TailwindCSS를 활용한 반응형 개발자 포트폴리오 웹사이트

7개 Phase로 구성된 프로젝트입니다. 자세한 로드맵은 향후 `ROADMAP.md`에 정의될 예정입니다.

## Git 워크플로우

- **브랜치 네이밍 규칙**: `feature/기능명`, `fix/버그명`, `dev/개발명`, `hotfix/수정명`
- **커밋 단위**: 작은 단위로 나눠서 커밋
- **메인 브랜치**: `hotfix` (PR 대상)

## 프로젝트 구조 (계획)

```
.
├── index.html              # 메인 페이지
├── css/
│   └── styles.css          # TailwindCSS 커스텀 스타일
├── js/
│   └── script.js           # JavaScript 기능 및 상호작용
├── assets/                 # 이미지, 아이콘 등 리소스
├── package.json            # npm 의존성 및 스크립트
├── tailwind.config.js      # TailwindCSS 설정
├── postcss.config.js       # PostCSS 설정
├── ROADMAP.md              # 개발 로드맵 및 마일스톤
└── CLAUDE.md               # 이 파일
```

## 개발 명령어 (설정 예정)

프로젝트 초기화 후 다음 명령어들이 추가될 예정입니다:

- `npm install` - 의존성 설치
- `npm run dev` - 개발 서버 실행
- `npm run build` - 프로덕션 빌드
- `npm run lint` - 코드 린트 검사

## 주요 기술 스택

- **마크업**: HTML5
- **스타일**: CSS, TailwindCSS
- **스크립트**: Vanilla JavaScript
- **빌드 도구**: npm 스크립트 (예정)

## 향후 업데이트

이 문서는 프로젝트가 발전하면서 다음과 같이 갱신될 예정입니다:

1. 실제 소스 코드 추가 후 아키텍처 설명 보충
2. 빌드/테스트 명령어 추가
3. 개발 환경 설정 가이드 추가
4. ROADMAP.md 작성