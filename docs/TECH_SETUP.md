# Technical Setup (v0.1)

## 엔진/해상도
- Godot 4.x
- 기준 해상도: 320x180 또는 640x360 (정수 배율 업스케일)
- Pixel Snap 활성화

## Steam 배포 고려사항
- 대상 OS: Windows 10/11 x64
- 컨트롤: 키보드+마우스 / 패드
- 빌드 파이프라인: 추후 CI에서 Windows export preset 자동화

## 코드/데이터 원칙
- `scripts/core`: 씬 전환, 저장, 오디오 매니저
- `scripts/gameplay`: 상호작용, 퍼즐, 상태머신
- `scripts/narrative`: 대사 재생, 선택지 누적, 플래그 처리
- 내러티브 데이터는 JSON으로 분리(`data/dialogue`)

## 우선 구현 항목
1. 메인 허브 이동 + 상호작용
2. 대화 시스템(초상화/텍스트/선택)
3. 내면 던전 1개 + 퍼즐 1종
4. 챕터 종료 리포트(주인공 내면 독백)
