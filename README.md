<p align="center"><img src="icon.png" width="128" alt="Choflix AVGrab"></p>

<h1 align="center">Choflix AVGrab</h1>

<p align="center">웹페이지 주소를 붙여넣으면 영상을 파일로 저장하는 앱 (Windows · macOS)</p>

<p align="center"><a href="https://github.com/fmj96/Choflix-AVGrab-download/releases/latest"><b>⬇ 최신 버전 내려받기</b></a></p>

## 내려받기

[Releases 최신 버전](https://github.com/fmj96/Choflix-AVGrab-download/releases/latest)에서 내 컴퓨터에 맞는 파일을 받으세요.

| 파일 | 대상 |
|---|---|
| `Choflix-AVGrab-<버전>-Setup.exe` | **Windows 10/11 (권장)** — 설치 프로그램 |
| `Choflix-AVGrab-<버전>-win-x64-portable.zip` | Windows — 설치 없이 압축만 풀어서 사용 |
| `Choflix-AVGrab-<버전>-mac.dmg` | macOS 13 이상, Apple Silicon(M1 이후) |

필수 엔진(yt-dlp, ffmpeg)이 함께 들어 있어서 따로 설치할 것이 없습니다.

## 설치

### Windows
1. `Setup.exe`를 실행하고 안내에 따라 설치합니다. (관리자 권한 필요 없음)
2. "Windows의 PC 보호" 창이 뜨면 **추가 정보 → 실행**을 누르세요. (코드 서명이 없는 앱이라 처음에 나올 수 있습니다)

### macOS
1. `dmg`를 열고 **Choflix AVGrab**을 **Applications** 폴더로 끌어다 놓습니다.
2. 처음 실행할 때 경고가 나오면 **시스템 설정 → 개인정보 보호 및 보안 → 그래도 열기**를 누르세요. (Apple 공증을 받지 않은 앱이라 처음 한 번만 필요합니다)

## 사용법
1. 영상이 있는 페이지 주소를 붙여넣고 **분석**
2. 화질을 고르면 **받을 포맷**(해상도·코덱·예상 용량)이 표시됩니다
3. **다운로드** → 완료 후 폴더에서 보기

주요 기능
- 최고 화질 / 해상도 지정 / 오디오만 / 포맷 직접 선택, MP4·MKV·WEBM
- 편집 호환 우선 (H.264 + AAC) — 편집 프로그램에서 바로 사용
- 파일명에 해상도·코덱 표시: `제목 [1080p] [H.264] [영상ID].mp4`
- 추가 저장: 오디오 파일(MP3·WAV), 자막(SRT)
- 네이버 뉴스 기사 영상 지원
- 사이트가 바뀌어 분석이 안 되면 앱 아래의 **[업데이트]** 를 누르세요

## 주의
- DRM(저작권 보호)이 걸린 스트리밍 영상은 받을 수 없습니다.
- 권리가 있거나 허용된 콘텐츠에만 사용하세요.

## 함께 들어 있는 외부 프로그램
- **yt-dlp** — https://github.com/yt-dlp/yt-dlp (The Unlicense)
- **FFmpeg** — https://ffmpeg.org (소스: https://ffmpeg.org/download.html)
  - Windows: [BtbN/FFmpeg-Builds](https://github.com/BtbN/FFmpeg-Builds) win64 LGPL 빌드 (LGPL v2.1+)
  - macOS: [Martin Riedl](https://ffmpeg.martin-riedl.de) arm64 정적 빌드 (GPL v3)

Choflix AVGrab은 위 프로그램을 별도 실행 파일로 포함하고 필요할 때 실행만 합니다.
