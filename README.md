# wonjun-lab/homebrew-tap

wonjun-lab 도구들의 Homebrew tap.

- [hangul-nfc](https://github.com/wonjun-lab/hangul-nfc) — macOS 한글 파일명 자소분리(NFD) → 정상(NFC) 정리 도구 (예전 이름 nfd2nfc)
- [codex-swap](https://github.com/wonjun-lab/codex-swap) — Codex CLI 계정 여러 개를 두고 사용량에 따라 바꿔 쓰는 도구

```sh
brew install wonjun-lab/tap/hangul-nfc && hangul-nfc setup   # setup: Finder 우클릭 메뉴 설치
brew install wonjun-lab/tap/codex-swap
```

> 예전 이름 `nfd2nfc` 로 설치했다면 **한 줄 설치를 다시 실행**하세요 — Homebrew 설치본을 새 이름으로 옮기고(`brew migrate`) Finder 메뉴·자동 감시까지 옮깁니다.
> ```sh
> curl -fsSL https://raw.githubusercontent.com/wonjun-lab/hangul-nfc/main/install.sh | sh
> ```
> `brew upgrade` 만으로는 옮겨지지 않습니다(Homebrew 탭 신뢰 정책). 직접 하려면 `brew trust --formula wonjun-lab/tap/hangul-nfc && brew migrate hangul-nfc && brew upgrade hangul-nfc && hangul-nfc setup`.
