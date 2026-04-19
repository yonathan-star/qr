# QR Studio — Custom QR Code Generator

A clean, open-source QR code generator you can deploy to GitHub Pages in 30 seconds. No dependencies to install, no build step, no server.

## Features

- **Custom dot colors** — dots, background, corner squares, corner dots each independently colorable
- **6 dot styles** — rounded, dots, classy, classy-rounded, square, extra-rounded
- **Center logo/image** — upload any PNG, SVG, or JPG to embed in the center
- **Adjustable logo size & margin**
- **Multiple content types** — URL, plain text, email, phone, WiFi
- **4 error correction levels** — use H (High) when adding a logo
- **Download as PNG, SVG, or JPEG**
- **100% client-side** — no server, no tracking, no data leaves your browser
- **Single HTML file** — `index.html` is the entire app

## Deploy to GitHub Pages

1. Fork or clone this repo
2. Go to **Settings → Pages**
3. Set source to `main` branch, `/ (root)` folder
4. Done — your generator lives at `https://yourusername.github.io/your-repo-name`

## Run locally

No build step needed. Just open the file:

```bash
# Option 1: direct browser open
open index.html

# Option 2: local server (avoids any CORS issues)
npx serve .
# or
python3 -m http.server 8080
```

## Powered by

- [qr-code-styling](https://github.com/kozakdenys/qr-code-styling) — MIT license — the engine behind the customizable QR rendering
- [Space Grotesk](https://fonts.google.com/specimen/Space+Grotesk) — Google Fonts
- [JetBrains Mono](https://fonts.google.com/specimen/JetBrains+Mono) — Google Fonts

## License

MIT — use it, fork it, ship it, sell it.
