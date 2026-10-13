# ARKEY_Apps_macOS

Каталог защищённых программ **AR Launcher** для **macOS (Apple Silicon, arm64)**.

Отдельный репозиторий, не связанный с Windows-каталогом `ARKEY_Apps` — релизы не пересекаются.

- `mac/manifest.json` — манифест каталога (список программ, версии, sha256).
- `mac/*.arp` — запечатанные программы (ECIES+AEAD). Бесполезны без лаунчера и донгла-оракула.
- `mac/icon-*.png` — иконки плиток.

Лаунчер тянет каталог по raw-URL:
`https://raw.githubusercontent.com/Andyroc/ARKEY_Apps_macOS/main/mac/manifest.json`

