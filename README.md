# D.L. Releases

한국어 · [English](#english)

D.L.에서 만드는 맥 앱의 설치 파일을 여기서 받는다. 소스 코드는 공개하지 않는다.

| 앱 | 무엇 | 받기 |
|---|---|---|
| **VALE** | 대화를 기억하는 로컬 비서. 클로드·ChatGPT·Grok 계정을 붙여 쓴다 | [최신 판](https://github.com/Dominic-YG-Lee/DL-Releases/releases/latest) |
| VIRGO | 알고리즘 트레이딩 에이전트 | 준비 중 |

## VALE 설치 (macOS · Apple Silicon)

1. [Releases](https://github.com/Dominic-YG-Lee/DL-Releases/releases/latest)에서 `VALE-<판>-mac-arm64.dmg`를 받는다.
2. DMG를 열고 **VALE**를 **응용 프로그램** 폴더로 끌어 넣는다. (DMG 안에서 바로 켜면 앱이 옮겨 주겠다고 묻는다.)
3. 처음 켜면 필요한 것을 내려받는다 — 기억 모델(약 2GB)과 도구 셋. 몇 분 걸린다.
4. 설정 › 연결에서 쓰는 계정(클로드·ChatGPT·Grok)에 로그인한다. 그걸로 끝이다.

- 필요한 것: macOS 13 이상, Apple Silicon(M1 이후), 여유 공간 약 10GB(모델·도구 포함).
- 앱은 Apple Developer ID로 서명·공증되어 있어 따로 보안 설정을 풀 것이 없다.
- 데이터는 전부 내 컴퓨터의 `~/DL/VALE` 폴더에만 있다. 대화·기억이 밖으로 나가지 않는다.
- 앱은 하루 한 번 새 판이 있는지 여기 Releases에 묻는다. 설정에서 끌 수 있다.

## 문제가 생기면

설정 › **오류 기록 내보내기**로 만든 zip을 [Issues](https://github.com/Dominic-YG-Lee/DL-Releases/issues)에 올리거나 메일로 보낸다. zip에는 앱 로그와 판·OS 정보가 들어 있고, 대화 조각이 섞일 수 있으니 올리기 전에 한 번 열어 본다.

## 판 이력

| 판 | 날짜 | 무엇 |
|---|---|---|
| 0.1.0 | 2026-09 | 첫 공개 판 |

---

## English

Installers for D.L. apps for the Mac. Source code is not published.

| App | What | Download |
|---|---|---|
| **VALE** | A local assistant that remembers your conversations. Sign in with your Claude, ChatGPT or Grok account | [Latest release](https://github.com/Dominic-YG-Lee/DL-Releases/releases/latest) |
| VIRGO | Algorithmic trading agent | Coming soon |

### Installing VALE (macOS · Apple Silicon)

1. Download `VALE-<version>-mac-arm64.dmg` from [Releases](https://github.com/Dominic-YG-Lee/DL-Releases/releases/latest).
2. Open the DMG and drag **VALE** into **Applications**. (If you launch it from inside the DMG, the app offers to move itself.)
3. On first launch it downloads what it needs: the memory model (about 2 GB) and its tools. This takes a few minutes.
4. Go to Settings › Connections and sign in to the account you use (Claude, ChatGPT or Grok). That's it.

- Requirements: macOS 13 or later, Apple Silicon (M1 or newer), about 10 GB free (models and tools included).
- The app is signed and notarized with an Apple Developer ID, so no security settings need changing.
- Everything stays on your Mac in `~/DL/VALE`. Conversations and memories never leave your computer.
- Once a day the app asks this Releases page whether a new version exists. You can turn that off in Settings.
- The interface follows your Mac's language: Korean on a Korean Mac, English otherwise. Switch anytime in Settings.

### If something goes wrong

Use Settings › **Export error log** and attach the zip to an [Issue](https://github.com/Dominic-YG-Lee/DL-Releases/issues). The zip contains app logs plus version and OS info; it may include fragments of conversations, so glance through it before uploading.

### Versions

| Version | Date | Notes |
|---|---|---|
| 0.1.0 | 2026-09 | First public release |
