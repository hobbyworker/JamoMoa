<div align="center">

# JamoMoa · 자모모아

**macOS 파일명 정규화 유틸리티 — 무료**

[**웹사이트**](https://jamomoa.hobbyworker.me) ·
[한국어](https://jamomoa.hobbyworker.me/ko/) ·
[日本語](https://jamomoa.hobbyworker.me/ja/) ·
[Tiếng Việt](https://jamomoa.hobbyworker.me/vi/)

[**⬇ 최신 버전 다운로드**](https://github.com/hobbyworker/JamoMoa/releases/latest)

</div>

---

## What it does

macOS stores Korean filenames with the jamo pulled apart (NFD). Move those
files to another OS or service and the names break, or stop matching in
search and sort. JamoMoa converts them back to their **composed (NFC)**
form, renaming in place.

It previews first: a drop only *builds a list*. Nothing on disk changes
until you confirm.

The same decomposition problem shows up beyond Korean — Japanese dakuten
(が = か + U+3099), Vietnamese diacritics (ế = e + U+0302 + U+0301) — and
detection is script-agnostic, so filenames in any language work.

Full feature list, help and FAQ: **[jamomoa.hobbyworker.me](https://jamomoa.hobbyworker.me)**

macOS 14.0 (Sonoma) or later · Apple Silicon and Intel universal binary

## 이게 뭐 하는 앱인가

macOS는 한글 파일명을 자모가 분리된(NFD) 형태로 저장합니다. 다른 OS나
서비스로 옮기면 이름이 깨지거나 검색·정렬에 안 걸리는 고질병이 여기서
옵니다. 자모모아는 이것을 **조합형(NFC)** 으로 되돌립니다.

먼저 보여주고 나중에 바꿉니다 — 드롭하면 목록만 만들어지고, 확인을 누르기
전까지 디스크는 그대로입니다. 한글뿐 아니라 일본어 탁점, 베트남어 성조
부호도 동일하게 처리합니다.

자세한 기능과 도움말: **[jamomoa.hobbyworker.me/ko/](https://jamomoa.hobbyworker.me/ko/)**

## About this repository

This is the **distribution channel**, not the source. JamoMoa is
proprietary software and its source code is not public. What you find here
is the signed, notarized DMG attached to each release — nothing else.

여기는 **배포 채널**입니다. 소스 저장소가 아닙니다.

## Free, and donations change nothing

JamoMoa is free. Every feature is available to everyone, always.

Donations are gratefully accepted and buy you **no additional
functionality** — no unlocked features, no removed limits, no priority
support. They are a thank-you, not a purchase. If you would rather not
donate, use the app freely and without guilt; that is the intended way to
use it.

기부는 감사히 받지만 **기능상 차이는 전혀 없습니다.** 잠금 해제되는 기능도,
풀리는 제한도 없습니다.

Sponsor links live on the website and inside the app (설정 ▸ 후원).

## License

**Copyright © 2026 hobbyworker (취미생활자). All rights reserved.**

JamoMoa is proprietary software, licensed for use — not given away. See
[`LICENSE`](LICENSE) for the terms. In short: use it freely on any machine
you control, for anything you like, but do not redistribute or repackage
it.

The app bundles open-source components under their own licenses (Sparkle
and KeyboardShortcuts, both MIT). Their full texts are shown in the app
under **설정 ▸ 정보 ▸ 라이센스 보기**.
