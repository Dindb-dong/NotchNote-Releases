# NotchNote Releases

[한국어](#korean) | [English](#english)

<a id="korean"></a>
## 한국어

이 디렉터리는 NotchNote 공개 배포용 문서를 담고 있습니다.

### 스크린샷 미리보기

릴리즈 저장소에는 아래 순서대로 스크린샷을 두는 것을 권장합니다. 이미지 파일은 `assets/` 아래에 넣어두면 됩니다.

권장 파일명:

- `hero-overlay.png`
- `quick-capture-overlay.png`
- `library-workspace.png`
- `onboarding-shortcut.png`
- `keychain-password-prompt.png`

대표 스크린샷:

`hero-overlay.png`
![NotchNote hero overlay](assets/hero-overlay.png)

추천 배치 이유:

- `hero-overlay.png`: 노치/상단 오버레이라는 제품의 첫인상을 바로 전달
- `quick-capture-overlay.png`: 현재 앱 컨텍스트에 붙는 메모 경험을 설명할 때 사용
- `library-workspace.png`: Library와 카드/투두 구조를 보여줄 때 사용
- `onboarding-shortcut.png`: 첫 실행 설정과 단축키 녹화 경험을 보여줄 때 사용
- `keychain-password-prompt.png`: 첫 실행 시 비밀번호 프롬프트가 정상 동작임을 미리 안내할 때 사용

### 핵심 화면

#### 1. 빠른 캡처

현재 작업 중인 앱 맥락으로 바로 메모를 여는 장면입니다.

![Quick capture overlay](assets/quick-capture-overlay.png)

#### 2. Library 워크스페이스

왼쪽 투두 목록과 오른쪽 카드형 메모를 함께 관리하는 장면입니다.

![Library workspace](assets/library-workspace.png)

#### 3. 첫 설정과 단축키

처음 실행 시 권한/단축키를 잡는 흐름을 보여주는 장면입니다.

![Onboarding shortcut setup](assets/onboarding-shortcut.png)

### 배포 범위

NotchNote는 독점 소프트웨어로 배포됩니다.

- 애플리케이션 소스 코드는 오픈소스로 제공되지 않습니다.
- 릴리즈 자산은 승인된 최종 사용자 사용만을 위해 제공됩니다.
- 애플리케이션 및 관련 자산을 복사, 수정, 재배포, 재패키징할 권한은 부여되지 않습니다.

### 첫 실행 보안 안내

처음 실행할 때 macOS가 로그인 비밀번호를 요구할 수 있습니다. 이는 NotchNote가 로컬 메모 데이터베이스 키를 macOS Keychain에 안전하게 생성하거나 읽기 위해 필요한 정상 동작입니다.

- 이 프롬프트는 정상입니다.
- NotchNote는 로컬 데이터베이스 키를 사용자의 Mac Keychain에 안전하게 저장합니다.
- 로그인 비밀번호는 NotchNote가 수집하거나 전송하지 않으며, macOS Keychain 시스템 UI에서만 처리됩니다.
- 이 프롬프트를 거부하면 로컬 메모 데이터베이스를 정상적으로 열지 못할 수 있습니다.

권장 스크린샷:

`keychain-password-prompt.png`
![Keychain password prompt](assets/keychain-password-prompt.png)

이 이미지는 사용자가 "왜 비밀번호를 요구하지?"라고 가장 먼저 불안해할 수 있는 지점을 미리 설명해주는 용도로 넣는 것이 좋습니다.

### 지식재산권

NotchNote는 독점 제품입니다. 구현 방식, 사용자 경험, 시각적 표현, 컨텍스트 기반 동작, 메모 그룹핑 모델, 온보딩 흐름, 리마인더 흐름, 인터랙션 설계 및 관련 제품 결정은 법이 허용하는 최대 범위까지 독점 자료로 보호됩니다.

여기에는 다음이 포함되며 이에 한정되지 않습니다.

- 앱 이름과 브랜딩
- 아이콘 및 그래픽 자산
- 인터페이스 문구와 스크린샷
- 릴리즈 패키지
- 제품 흐름과 고유한 상호작용 패턴
- 컨텍스트 기반 메모 캡처 및 그룹핑 동작
- 에디터, 라이브러리, 백업, 온보딩, 리마인더 경험 설계

사전 서면 허가 없이 이러한 자료를 복제, 모방, 변형, 상업화하거나 실질적으로 유사한 경쟁 제품을 만드는 것은 허용되지 않습니다.

### 문서 구성

- [LICENSE.md](LICENSE.md)
- [EULA.md](EULA.md)

### 사용 목적

이 문서들은 NotchNote 공개 배포 저장소, GitHub Releases 페이지, 또는 다운로드 가능한 릴리즈 압축 파일과 함께 제공되도록 작성되었습니다.

---

<a id="english"></a>
## English

This directory contains public-release support documents for NotchNote.

### Screenshot Preview

For the public release repository, it is worth placing screenshots in the following order. Put the image files under `assets/`.

Recommended filenames:

- `hero-overlay.png`
- `quick-capture-overlay.png`
- `library-workspace.png`
- `onboarding-shortcut.png`
- `keychain-password-prompt.png`

Hero screenshot:

`hero-overlay.png`
![NotchNote hero overlay](assets/hero-overlay.png)

Why this layout works:

- `hero-overlay.png`: immediately shows the notch/top-edge identity of the product
- `quick-capture-overlay.png`: explains the context-aware capture experience
- `library-workspace.png`: shows the Library split between todos and memo cards
- `onboarding-shortcut.png`: shows first-run setup and shortcut recording
- `keychain-password-prompt.png`: explains that the first-run password dialog is an expected macOS Keychain prompt

### Core Screens

#### 1. Quick Capture

Show the overlay attached to the current app context.

![Quick capture overlay](assets/quick-capture-overlay.png)

#### 2. Library Workspace

Show the left todo list and the right memo-card workspace together.

![Library workspace](assets/library-workspace.png)

#### 3. First-Run Setup and Shortcut

Show the onboarding step where permissions and the global shortcut are configured.

![Onboarding shortcut setup](assets/onboarding-shortcut.png)

### Distribution Scope

NotchNote is distributed as proprietary software.

- The application source code is not open source.
- Release assets are provided only for authorized end-user use.
- No permission is granted to copy, modify, redistribute, or repackage the application or its assets.

### First Launch Security Note

On first launch, macOS may ask for your login password so NotchNote can create or read its database key in Keychain.

- This prompt is expected.
- NotchNote uses Keychain to store the local database key securely on your Mac.
- Your login password is handled by macOS Keychain access UI, not collected or transmitted by NotchNote.
- If you deny the prompt, the app may not be able to open its local memo database correctly.

Recommended screenshot:

`keychain-password-prompt.png`
![Keychain password prompt](assets/keychain-password-prompt.png)

This image is worth including because it preemptively explains the one screen most likely to make a new user uneasy during first launch.

### Intellectual Property

NotchNote is a proprietary product. Its implementation, user experience, visual presentation, context-aware behavior, memo-grouping model, onboarding flow, reminder flow, interaction design, and related product decisions are protected as proprietary materials to the fullest extent permitted by law.

This includes, without limitation:

- app name and branding
- icons and graphic assets
- interface copy and screenshots
- release packages
- product flows and distinctive interaction patterns
- context-aware memo capture and grouping behavior
- editor, library, backup, onboarding, and reminder experience design

No person or organization may reproduce, imitate, adapt, or commercialize these materials or build a substantially similar competing product from them without prior written permission.

### Contents

- [LICENSE.md](LICENSE.md)
- [EULA.md](EULA.md)

### Intended Use

These files are meant to accompany a public distribution repository, GitHub Releases page, or downloadable release archive for NotchNote.
