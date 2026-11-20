<p align="center">
  <img src="icon.png" width="96" alt="Sense Loader">
</p>

<h1 align="center">Sense Loader</h1>

<p align="center">
  <b>필요한 것만, 정확하게.</b><br>
  쎈스 디렉터와 함께 쓰는 Windows 미디어 로더<br>
  검수할 영상이나 참고 영상을 링크 하나로 영상(MP4, 최대 4K·8K) · 음악(MP3 / M4A) · 둘 다 받아 둡니다
</p>

<p align="center">
  <a href="https://github.com/Osense/Sense_Loader-releases/releases/latest/download/Sense_Loader-win64.zip"><b>최신 버전 다운로드 (zip)</b></a>
  &nbsp;·&nbsp;
  <a href="CHANGELOG.md">변경 내역</a>
</p>

---

## 설치 / 실행

1. [`Sense_Loader-win64.zip`](https://github.com/Osense/Sense_Loader-releases/releases/latest/download/Sense_Loader-win64.zip)을 받습니다. 이 링크는 항상 최신 버전을 가리킵니다.
2. 압축을 풀고 **`Sense Loader.exe`** 를 실행합니다.

- 설치가 필요 없습니다. ffmpeg · ffprobe · deno가 함께 들어 있어 따로 설치할 것이 없습니다.
- Windows 10 / 11 (64bit). WebView2 런타임이 필요하며 Windows에 기본 설치되어 있습니다.
- 서명되지 않은 알파 버전이라 **SmartScreen 경고**가 뜰 수 있습니다 → **추가 정보 → 실행**

## 사용법

1. 영상 링크를 붙여넣습니다 (Ctrl+V 또는 끌어다 놓기)
2. **영상만** · **음악만** · **둘 다** 중에서 고릅니다
3. **다운로드** — 여러 개가 묶인 링크면 "하나만 / 전체"를 물어봅니다

## 기능

| | |
|---|---|
| 쎈스 디렉터와 함께 | 검수에 쓰는 영상을 미리 받아 두거나, 최종본을 영상 · 음악 파일로 정리할 때 씁니다 |
| 링크 그대로 | 주소창 · 공유 버튼 · 우클릭 복사 · 시작 시간이 붙은 링크도 그대로 붙여넣으면 항상 영상 전체를 받습니다 |
| 필요한 것만 | 여러 개가 묶인 링크는 하나만 받을지 전체를 받을지 묻습니다. 전체는 하위 폴더로 정리됩니다 |
| 영상 | 최대 4K · 8K MP4. 1080p 이하는 어디서나 재생되는 H.264로 맞추고, 1440p 이상은 원본 코덱(VP9 · AV1) 그대로 (설정에서 H.264 변환 가능) |
| 음악 | 원본의 가장 좋은 음원 → MP3 320kbps / AAC 256kbps, 앨범 자켓 · 태그 포함 |
| 둘 다 | 한 번에 영상 파일과 음악 파일을 함께 받습니다 |
| 링크 복사 | 다운로드 목록에서 받은 영상의 링크를 다시 복사할 수 있습니다 |
| 투명한 결과 | 완료 후 실제 파일의 해상도 · 코덱 · 비트레이트 · 샘플레이트를 보여줍니다 |
| 파일 이름 | 영상 제목 / 프로젝트명 + 제목 / 채널 + 제목 / 직접 입력 |
| 언어 | 한국어 · English |

## 문의 / 버그 제보

[Issues](https://github.com/Osense/Sense_Loader-releases/issues)에 남겨 주세요. 가능하면 사용한 링크와 화면 캡처를 함께 적어 주세요.

## 라이선스 고지

배포 zip에는 다음 오픈소스 소프트웨어가 포함되어 있습니다. 자세한 내용은 zip 안의 `THIRD_PARTY_NOTICES.txt`를 참고하세요.

- [FFmpeg](https://ffmpeg.org) — GPL v3 ([BtbN FFmpeg-Builds](https://github.com/BtbN/FFmpeg-Builds), 소스: https://ffmpeg.org/download.html)
- [Deno](https://deno.com) — MIT
- [yt-dlp](https://github.com/yt-dlp/yt-dlp) — Unlicense
- [pywebview](https://github.com/r0x0r/pywebview) — BSD 3-Clause
- [Pretendard](https://github.com/orioncactus/pretendard) — SIL OFL 1.1

권리가 있는 콘텐츠만 받아 주세요. 개인적인 용도로만 사용하고, 저작권이 있는 콘텐츠는 권리자가 허락한 범위 안에서 이용해야 합니다.
