# TokenPulse — 공개 릴리스

AI 토큰 사용량을 자동 트래킹하는 macOS 메뉴바 앱. 이 저장소는 **다운로드 자산과 자동 업데이트 피드(appcast)** 만 호스팅합니다.

## 다운로드

최신 빌드: **[Releases](https://github.com/contextors99/token-pulse/releases)**

## 설치

1. 최신 릴리스에서 `TokenPulse-v*.dmg` 다운로드
2. DMG 열고 `TokenPulse.app`을 `Applications` 폴더로 드래그
3. 앱 실행

Apple 공증된 빌드라 macOS의 "확인되지 않은 개발자" 경고 없이 바로 열립니다.

## 자동 업데이트 (Sparkle)

v1.0.2 이상 빌드는 다음 appcast을 통해 새 버전을 자동 감지합니다:

```
https://contextors99.github.io/token-pulse/appcast.xml
```

앱 자체에서 처리하므로 사용자가 별도로 무언가 할 필요는 없습니다.

## 시스템 요구사항

- macOS 14 (Sonoma) 이상
- Claude Code, Codex, 또는 Gemini CLI 중 하나 이상
