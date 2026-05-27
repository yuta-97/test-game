# Echoes of the Absurd (working title)

여성 주인공 중심의 싱글 플레이 도트 그래픽 철학 어드벤처 게임 프로젝트입니다.

## 프로젝트 목표
- **플랫폼**: Windows (Steam 배포 전제)
- **장르**: 내러티브 중심 탐험 + 퍼즐
- **그래픽**: 픽셀(도트) 아트
- **핵심 주제**: "인생은 공허하고 허무한가? 그렇다면 자살해야 하는가?"에 대한 플레이어 여정형 탐구
- **철학적 레퍼런스**: 알베르 카뮈, *시지프 신화*

## 기술 스택(초기)
- 엔진: **Godot 4.x**
- 버전 관리: Git
- 배포 대상: Steam(추후 Steamworks SDK 연동)

## 디렉토리 구조
```text
project/
  assets/
    art/
      characters/
      tilesets/
      ui/
    audio/
      bgm/
      sfx/
    narrative/
  scenes/
    core/
    levels/
    ui/
  scripts/
    core/
    gameplay/
    narrative/
  data/
    dialogue/
    items/
    levels/
docs/
  GDD.md
  STORY_BIBLE.md
  TECH_SETUP.md
```

## 빠른 시작
1. Godot 4.x 설치
2. `project/project.godot` 열기
3. `scenes/core/Main.tscn` 실행

## 다음 단계
- Steam App ID 발급 후 `steam_appid.txt`(로컬 전용) 세팅
- 픽셀 아트 파이프라인(Aseprite 등) 확정
- 대사/분기 데이터 JSON 스키마 확정
