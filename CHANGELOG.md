# Changelog

All notable changes to the Bricktris web version are documented in this file.

## 2026-01-29

- Updated `hra.html` to load logo, brick textures, and sounds from hosted GitHub asset URLs.
- Switched to direct raw GitHub links for reliable image/audio loading on external websites.
- Added local `assets/...` fallback loading if hosted files are unavailable.
- Added `bricktris-embed.html`: a minimal embed version with only canvas + script for direct insertion into an existing website page.
- Added `bricktris-embed-snippet.html`: single copy-paste snippet without `<!DOCTYPE>`, `<html>`, or `<body>`.
