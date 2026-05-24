# TokenPulse

> AI 코딩 도구의 토큰 사용량을 자동으로 트래킹하는 macOS 메뉴바 앱

Claude Code · Codex · Gemini의 사용량을 한눈에 확인하고, 팀과 선택적으로 공유하세요. 입력할 거 없이 자동 감지로 동작합니다.

이 저장소는 **다운로드 자산과 자동 업데이트 피드(appcast.xml)** 만 호스팅합니다.

## 다운로드

[**최신 버전 받기 →**](https://github.com/contextors99/token-pulse/releases/latest)

전체 릴리스: [Releases](https://github.com/contextors99/token-pulse/releases)

## 설치

1. 최신 릴리스에서 `TokenPulse-v*.dmg` 다운로드
2. DMG 열고 `TokenPulse.app`을 `Applications` 폴더로 드래그
3. `Applications`에서 TokenPulse 실행 → 메뉴바 우측 상단에 아이콘이 나타납니다

## 주요 기능

- 🔍 **자동 수집** — Claude Code · Codex · Gemini 사용량을 백그라운드에서 자동 수집
- 📊 **실시간 표시** — 세션 / 주간 쿼터 잔여량을 메뉴바에 항상 노출
- 🏷️ **플랜 자동 감지** — Pro, Max 20x 등 사용 중인 플랜을 자동 인식
- 👥 **팀 공유** (선택) — 초대 코드로 팀원과 사용량 공유. 서버: `https://pulse.ctxpeople.cc`
- 🔒 **공유 범위 설정** — 요약 / 상세 / 세션 단위로 본인이 결정
- 🔄 **자동 업데이트** — 새 버전 자동 감지·설치 (v1.0.2부터)

## 사용법

설치 후 메뉴바 아이콘으로 조작합니다.

- **좌클릭** — 현재 사용량 패널 열기 (서비스별 세션/주간 쿼터, 플랜, 팀 공유 설정)
- **우클릭** — 컨텍스트 메뉴 (업데이트 확인 · 종료)

## 자동 업데이트

v1.0.2 이상은 다음 appcast을 통해 새 버전을 자동 감지·설치합니다:

```
https://contextors99.github.io/token-pulse/appcast.xml
```

하루 1회 자동 체크 + 즉시 확인은 메뉴바 우클릭 → 업데이트 확인…

## 시스템 요구사항

- macOS 14 (Sonoma) 이상
- Claude Code, Codex, 또는 Gemini CLI 중 하나 이상 설치
