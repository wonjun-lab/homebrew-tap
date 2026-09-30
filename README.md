# wonjun-lab/homebrew-tap

wonjun-lab 도구들의 Homebrew tap.

- [hangul-nfc](https://github.com/wonjun-lab/hangul-nfc) — macOS 한글 파일명 자소분리(NFD) → 정상(NFC) 정리 도구 (예전 이름 nfd2nfc)
- [codex-swap](https://github.com/wonjun-lab/codex-swap) — Codex CLI 계정 여러 개를 두고 사용량에 따라 바꿔 쓰는 도구

```sh
brew install wonjun-lab/tap/hangul-nfc && hangul-nfc setup   # setup: Finder 우클릭 메뉴 설치
brew install wonjun-lab/tap/codex-swap
```

> 예전 이름 `nfd2nfc` 로 설치했다면 `brew upgrade` 가 `hangul-nfc` 로 옮겨 줍니다(`formula_renames.json`). 그다음 `hangul-nfc setup` 을 한 번 실행하면 Finder 메뉴·자동 감시도 새 이름으로 옮겨집니다.
