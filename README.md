# 🎨 Color Studio

**단축키 한 번으로 화면의 색을 뽑아 HEX 코드를 복사하는 Windows 프로그램**

`Ctrl + Shift + C` → 원하는 곳 클릭 → HEX 코드(예: `#4ECDC4`)가 클립보드에 복사됩니다.

---

## 다운로드 & 실행

1. 위 파일 목록에서 **`ColorStudio.exe`** 를 클릭한 뒤, 오른쪽의 **다운로드(⬇) 버튼**을 누릅니다.
2. 받은 `ColorStudio.exe`를 실행합니다. **설치나 Python이 필요 없습니다.**
3. Windows 보호(SmartScreen) 경고가 뜨면 **추가 정보 → 실행**을 누르세요.
   (개인이 만든 프로그램이라 코드 서명이 없어서 표시되는 경고입니다.)

> 처음 한 번 실행하면 **Windows 시작 시 자동 실행**되고, **시작 메뉴**에 등록됩니다.
> (Windows 키 → "Color Studio" 검색)

---

## 사용법

### 스포이드

| 조작 | 기능 |
| --- | --- |
| `Ctrl + Shift + C` | 스포이드 시작 (어느 프로그램에서나) |
| 클릭 / `Enter` | 색 선택 → HEX 코드 복사 |
| 방향키 | 1픽셀 이동 (`Shift` 누르면 10픽셀) |
| 마우스 휠 | 돋보기 확대 / 축소 |
| `Esc` / 우클릭 | 취소 |

색을 고르면 화면 오른쪽 아래에 **복사 완료** 알림이 뜹니다. 바로 `Ctrl + V`로 붙여넣으세요.

### 앱 화면

- **색 선택**: 사각형(밝기·채도) + 무지개 막대(색상), 명암 단계
- **값 복사**: HEX · RGB · HSL · HSV · CMYK 등 11가지 형식
- **명암비 검사**: 흰/검정 글씨 대비율 (WCAG AA · AAA)
- **색상 조화**: 보색 · 유사색 · 분할 보색 · 삼각 · 사각 배색 추천
- **내 팔레트 / 최근 기록 / 프리셋**, 내보내기(JSON · CSS · GIMP · TXT)
- **붙여넣기**: `#abc`, `rgb()`, `hsl()` 같은 값을 `Ctrl + V`로 불러오기

---

## 알아두면 좋은 점

- **창을 닫아도 꺼지지 않습니다.** 시계 옆 트레이에서 계속 실행되어 단축키가 동작합니다.
- **완전히 종료**: 트레이 아이콘 우클릭 → **종료**
- **단축키 변경 · 자동 실행 끄기**: 앱의 **설정** 버튼
- 설정과 팔레트는 `%APPDATA%\ColorStudio`에 저장됩니다.

### 삭제하는 방법

1. 앱 **설정**에서 **Windows 시작 시 자동 실행** 체크 해제 → 저장
2. 트레이 아이콘 우클릭 → **종료**
3. `ColorStudio.exe` 삭제
4. (선택) 아래 폴더/파일 삭제
   - `%APPDATA%\ColorStudio` (설정·팔레트)
   - `%APPDATA%\Microsoft\Windows\Start Menu\Programs\Color Studio.lnk` (시작 메뉴 바로가기)

---

## 사양

- Windows 10 / 11 (64비트)
- 다중 모니터, 화면 배율(125% · 150%) 지원

## 글꼴 라이선스

이 프로그램에는 [페이퍼로지(Paperlogy)](https://freesentation.blog/paperlogyfont) 글꼴이 포함되어 있습니다.
Copyright 2024 The PAPERLOGY Authors — [SIL Open Font License 1.1](https://openfontlicense.org/open-font-license-official-text/)
