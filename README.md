# LLL QR

Developed by LLL Inc.'s dev team — visit us at https://www.live-laugh-love.world

A free, privacy-first browser QR code toolkit. Generate and scan QR codes
entirely client-side — nothing is uploaded to a server, no account required.

**Live:** https://lll-qr.pages.dev/

## Tools

- **Generate** — create QR codes for links, plain text, Wi-Fi credentials, contact cards, calendar events, and locations
- **Customize** — foreground/background colors, gradient fill, dot style (square, rounded, dots), optional "Scan me" frame with caption, adjustable error correction level, center logo
- **Export** — download as PNG (adjustable size) or SVG, copy image to clipboard, or share
- **Scan** — scan a QR code via camera or by uploading a photo, then copy, open, or recreate it as an editable QR
- **History** — recent codes saved locally for quick reuse

## Tech

- Plain HTML/CSS/JS, single-page app
- QR generation via a vendored QRCode.js encoder; scanning via a vendored jsQR decoder
- Dark mode support, mobile-first responsive design