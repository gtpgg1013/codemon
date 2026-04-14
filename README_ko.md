<div align="center">
  <img src="docs/screenshots/hero.png" width="420" alt="Codemon — 코딩할수록 성장하는 생명체" />

  # Codemon

  **코딩할수록 성장하는 나만의 코딩 동반자.**

  실제 코딩 활동으로 픽셀 생명체를 키우는 macOS 메뉴바 앱.

  <br/>

  ### [⬇️ &nbsp; macOS용 다운로드 &nbsp; ⬇️](https://github.com/gtpgg1013/codemon/releases/latest)

  [![Latest Release](https://img.shields.io/github/v/release/gtpgg1013/codemon?style=for-the-badge&label=Latest&color=success)](https://github.com/gtpgg1013/codemon/releases/latest)
  ![macOS 14.0+](https://img.shields.io/badge/macOS-14.0%2B-black?style=for-the-badge&logo=apple)
  [![Support on Ko-fi](https://img.shields.io/badge/Support-Ko--fi-ff5e5b?style=for-the-badge&logo=ko-fi)](https://ko-fi.com/gangkk)
</div>

---

[English](README.md) | 한국어

---

**진화 단계 6단계** | **고유 생명체 100종** | **실제 코딩으로 XP 획득**

---

## 설치

1. [Releases](https://github.com/gtpgg1013/codemon/releases/latest)에서 최신 `Codemon-x.x.x.dmg` 다운로드
2. DMG를 열고 Codemon을 Applications 폴더로 드래그
3. Codemon 실행 — 메뉴바에 표시됨; 플로팅 패널을 원한다면 **별도 창** 모드도 사용 가능
4. 온보딩 화면에서 **훅 설치** 버튼을 클릭해 코딩 도구와 연결

## 지원 도구

| 도구 | 상태 |
|------|------|
| Claude Code (CLI) | ✅ |
| Cursor | ✅ |
| VS Code + Claude Extension | ✅ |

## 동작 원리

<div align="center">
  <img src="docs/screenshots/stats.png" width="400" alt="XP 추적, 연속 코딩, 일일 도전" />
</div>

1. **활동 감지** — 코딩 도구가 발생시키는 훅 이벤트를 실시간으로 감시합니다.
2. **분류** — 각 이벤트는 활동 유형(코드 생성, 테스트 작성, 검색, 리팩토링 등)으로 분류됩니다.
3. **XP 부여** — 활동 유형에 따라 기본 XP 10–60이 부여되며, 일일 보너스와 최대 2.0x의 연속 코딩 배율이 추가됩니다.
4. **성향 형성** — 활동 내역이 6가지 성향 포인트에 쌓이며 생명체의 개성을 형성합니다:
   - **Creator (창조자)** — 새 코드를 생성하고 작성
   - **Guardian (수호자)** — 테스트, 리뷰, 품질 보호
   - **Analyst (분석가)** — 검색, 읽기, 탐구
   - **Architect (설계자)** — 계획, 구조화, 리팩토링
   - **Artist (예술가)** — UI, 스타일, 시각 요소 제작
   - **Sage (현자)** — 문서화, 설명, 지식 공유
5. **진화** — 누적 XP가 기준값을 넘으면 Codemon이 진화하고, 해당 단계의 고유 생명체 변형이 무작위로 배정됩니다.

<div align="center">
  <img src="docs/screenshots/tendencies.png" width="400" alt="6가지 코딩 성향이 생명체를 형성합니다" />
</div>

## 진화 단계

| 단계 | 필요 XP | 대략적인 레벨 |
|------|---------|--------------|
| 알 (Egg) | 0 | 1 |
| 유아 (Baby) | 200 | ~5 |
| 유년 (Youth) | 1,000 | ~11 |
| 성체 (Adult) | 4,000 | ~23 |
| 장로 (Elder) | 12,000 | ~42 |
| 전설 (Legend) | 35,000 | ~73 |

모든 진화 단계에 걸쳐 **100종의 고유 생명체**가 존재하며, 진화 시 해당 단계의 변형이 무작위로 배정됩니다.

## 업적 & 환생

<div align="center">
  <img src="docs/screenshots/activities.png" width="400" alt="업적, 과거 생, 환생" />
</div>

### 업적

총 **30개의 업적**이 네 가지 카테고리로 구성됩니다:

- **활동 마일스톤** — XP 및 도구 사용 횟수 달성 보상
- **연속 코딩 보상** — 연속 코딩일 달성 보너스
- **진화 마일스톤** — 생명체가 단계를 거쳐 성장할 때 해금
- **특별** — 특수하거나 뛰어난 코딩 패턴에 숨겨진 업적

### 환생 시스템

생명체가 높은 레벨에 도달하면 **환생**을 선택할 수 있습니다:

- 레벨과 XP가 초기화됩니다
- 이후 XP 획득에 영구 프레스티지 보너스가 적용됩니다
- 지난 생명체의 기록이 **과거 생** 로그에 남습니다
- **Action** 탭에서 환생을 실행할 수 있습니다

## 일일 도전 & 이벤트

- **일일 미션** — 매일 갱신되는 목표를 달성하면 보너스 XP 획득
- **랜덤 이벤트** — 코딩 활동 중 갑작스럽게 발동하는 보너스
- **시즌 이벤트** — 연중 명절 테마와 특별 배율 이벤트

## 장식 & 칭호

생명체 환경을 꾸밀 수 있는 **55종의 장식**을 수집하세요. 장식은 5가지 희귀도 등급으로 나뉩니다:

| 희귀도 | 색상 |
|--------|------|
| Common (일반) | 회색 |
| Uncommon (희귀) | 초록색 |
| Rare (레어) | 파란색 |
| Epic (에픽) | 보라색 |
| Legendary (전설) | 금색 |

장식은 **Decorate** 탭에서 장착할 수 있습니다. 업적으로 획득한 칭호는 **Action** 탭에서 표시할 수 있습니다.

## 설정

<div align="center">
  <img src="docs/screenshots/settings.png" width="400" alt="설정 패널" />
</div>

| 설정 항목 | 설명 |
|-----------|------|
| Language | 영어 / 한국어 전환 |
| Sound Effects | 레벨업 및 이벤트 효과음 켜기/끄기 |
| Launch at Login | 로그인 시 Codemon 자동 시작 |
| Separate Window | 팝오버 대신 플로팅 창으로 표시 |
| Codemon stays centered | 스프라이트를 창 중앙에 고정 |
| Activity Tracking | XP 추적 전체 활성화/비활성화 |
| Window Height | Codemon 패널 높이 조절 |

## 보안

- 모든 활동 데이터는 AES-GCM으로 암호화되며, Apple Silicon 기기는 Secure Enclave를 키 저장소로 사용합니다
- 훅 이벤트는 암호학적으로 서명되며, 서명 신원과 부모 프로세스를 검증한 후에만 수락됩니다
- 활동 로그는 SHA-256 해시 체인으로 보호되어 변조를 감지합니다
- 계정 없음, 클라우드 동기화 없음, 원격 분석 없음 — 모든 데이터는 사용자 기기에만 저장됩니다

## 요구 사항

- macOS 14.0 (Sonoma) 이상
- Apple Silicon 또는 Intel Mac (2018년 이상)

## 자동 업데이트

Codemon은 [Sparkle](https://sparkle-project.org/)을 통해 업데이트를 자동으로 확인합니다. 새 버전이 출시되면 앱 내에서 알림을 받습니다.

## 라이선스

독점 소유권. 모든 권리 보유.

---

<div align="center">

[Ko-fi로 후원하기](https://ko-fi.com/codemon)

</div>
