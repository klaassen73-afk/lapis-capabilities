# LAPIS — Agency Creative Capabilities

A web version of the Pinnacle Advertising & Marketing Group creative-capabilities
pitch deck for **LAPIS Automotive Group** (22 slides, 17 with embedded video reels).

> **Confidential — new-business pitch material.** This repository is private.
> Do not make it public or redistribute.

## Viewing
Videos stream over HTTP, so run a small local server rather than opening the file directly:
```bash
python3 -m http.server 8000   # then open http://localhost:8000
```
Controls: **← / →** or click to navigate · **G** overview grid · **F** fullscreen.
Video slides show a play button (two on slides 9 & 10); the reel loads only on click.

## Contents
- `index.html` — self-contained viewer
- `assets/slides/` — 22 full-res 1920×1080 slide images
- `assets/thumbs/` — overview thumbnails
- `assets/videos/` — 17 reels (**Git LFS**), H.264, compressed from ~1.1GB to ~171MB
