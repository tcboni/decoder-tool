# Decoder Tool

A lightweight web app for encoding and decoding text.

**[→ Open Decoder Tool](https://tcboni.github.io/decoder-tool/)**

## Features

- **Real-time conversion** — type in either pane and the other updates instantly.
- **Auto-detect** — paste an encoded string and the tool picks the right algorithm.
- **Shareable URLs** — the Share button copies a link that restores your input on the other end.
- **Persistent state** — your last input is restored on page reload via `localStorage`.
- **Worksheet UI** — a paper-and-typewriter "cryptanalysis worksheet" look; fills the viewport, keyboard-friendly, copy/paste/clear in each pane.

## Supported algorithms

| Algorithm       | Encode | Decode |
| --------------- | :----: | :----: |
| Base64          |   ✓    |   ✓    |
| URL Encoding    |   ✓    |   ✓    |
| Hexadecimal     |   ✓    |   ✓    |
| Binary          |   ✓    |   ✓    |
| ASCII (Decimal) |   ✓    |   ✓    |
| Unicode Escapes |   ✓    |   ✓    |
| HTML Entities   |   ✓    |   ✓    |
| ROT13           |   ✓    |   ✓    |
| Caesar Cipher   |   ✓    |   ✓    |
| Morse Code      |   ✓    |   ✓    |
| Reverse         |   ✓    |   ✓    |
| JWT             |        |   ✓    |
| MD5             |   ✓    |        |
| SHA-1           |   ✓    |        |
| SHA-256         |   ✓    |        |
| SHA-512         |   ✓    |        |

Hashes are one-way: the tool marks them with a **ONE-WAY** stamp, fixes the direction to plain → digest, and makes the digest pane read-only.

## Privacy

Everything runs in your browser. No data leaves your machine — `localStorage` is local, and shareable URLs only encode your input into the URL hash (which browsers never send to the server).
