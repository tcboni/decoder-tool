# Decoder Tool

A lightweight web app for encoding and decoding text.

**[→ Open Decoder Tool](https://tcboni.github.io/decoder-tool/)**

## Features

- **Real-time conversion** — type in either pane and the other updates instantly.
- **Auto-detect** — paste an encoded string and the tool picks the right algorithm.
- **Shareable URLs** — the Share button copies a link that restores your input on the other end.
- **Persistent state** — your last input is restored on page reload via `localStorage`.
- **Dark, sleek UI** — fills the viewport, keyboard-friendly, copy/paste/clear in each pane.

## Supported algorithms

| Algorithm       | Encode | Decode |
| --------------- | :----: | :----: |
| Base64          |   ✓    |   ✓    |
| URL Encoding    |   ✓    |   ✓    |
| Hexadecimal     |   ✓    |   ✓    |
| Binary          |   ✓    |   ✓    |
| ASCII (Decimal) |   ✓    |   ✓    |
| HTML Entities   |   ✓    |   ✓    |
| ROT13           |   ✓    |   ✓    |
| Caesar Cipher   |   ✓    |   ✓    |
| Morse Code      |   ✓    |   ✓    |
| Reverse         |   ✓    |   ✓    |
| JWT             |        |   ✓    |

## Privacy

Everything runs in your browser. No data leaves your machine — `localStorage` is local, and shareable URLs only encode your input into the URL hash (which browsers never send to the server).
