# Hianime with Local MPV: CLI Anime Streamer for MPV & Custom Subs
![Python](https://img.shields.io/badge/python-3.12-green)

## Description
A CLI Python tool for streaming anime from hianime.to using your local MPV player. Supports custom subtitle imports via Jimaku API—perfect for anime fans wanting a lightweight hianime MPV extension with multi-language subs and history tracking.

## Introduction
This code was mostly written with AI assistance. I just gave the idea for what to build, then handled some code tweaks and cleanup. It's great for importing subtitles in other languages and using MPV extensions for hianime.

![CLI Demo](screenshots/cli-menu.gif)  <!-- Add your GIF here for that "aha!" moment -->

## Features
- 📌 **Pin Series**: Save your favorites for quick access.
- 📺 **Recent History**: Pick up where you left off.
- 🌐 **Jimaku API Integration**: Fetch and import Japanese subtitles.

## Requirements
- Python 3.12+
- MPV player (install via [official site](https://mpv.io/))
- Key libraries (via `requirements.txt`): requests (for APIs), and beautifulsoup4 (for parsing). Full list in `requirements.txt`

## Installation
1. `git clone https://github.com/dhilzyi/hianime-with-local-mpv.git`
2. `cd hianime-with-local-mpv`
3. `pip install -r requirements.txt`

## Usage
```bash
python hianime.py
```
- Paste an anime URL (e.g., https://hianime.to/watch/one-piece-100).
- Select options like episode, or 'p' to pin to series.
- Choose servers manually or automatically.
- Enable Jimaku in config.json by setting "jimaku_enabled": true.

## Troubleshooting
- Jimaku API issues: Get your key from jimaku.cc and add it to environment variables (e.g., export JIMAKU_API_KEY=yourkey) or paste directly in the code.
- MPV not launching? Ensure it's in your PATH (test with mpv --version).

## Contributing
Pull requests welcome! Fork the repo, create a branch, and submit.

## License
This project is licensed under the MIT License - see the LICENSE file for details.

