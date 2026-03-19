# Xiaohongshu Aesthetics Guide / 小红书美学指南

Make every post beautiful — a visual-first guide to Xiaohongshu content design.

让每一篇帖子都好看 —— 一份以视觉为核心的小红书内容设计指南。

## What's Inside

| Part | Topic | Tutorials |
|------|-------|-----------|
| 1 | Cover Design 封面设计 | Composition, Typography, Layout |
| 2 | Color 配色 | Color Theory, Style Palettes, Matching Rules, Tools |
| 3 | Imagery 配图 | Selection, Editing, Arrangement, Cover Types |
| 4 | Copywriting 文案美学 | Titles, Body Text, Keywords |
| 5 | Visual Identity 个人风格 | Consistency, Finding Your Style, Evolution |
| 6 | Style by Category 品类适配 | Tech & Coding, Food, Travel, Fashion & Beauty |
| 7 | Video Aesthetics 视频美学 | Video Covers, Editing Rhythm, Subtitles |

**24 tutorials** across **7 parts**, available in **Chinese and English**.

## Features

- Interactive phone mockups showing before/after comparisons
- CSS color swatches and palette previews
- Visual-first approach: ~70% demos, ~30% text
- Light/dark mode with rose pink accent
- Bilingual (zh/en) with language toggle

## Quick Start

Requires [uv](https://docs.astral.sh/uv/) and Python 3.10+.

```bash
git clone https://github.com/hideak1/aesthetic_rednote.git
cd aesthetic_rednote
make install    # Install dependencies
make serve      # Start dev server at http://localhost:8000
```

## Commands

```bash
make install    # Install dependencies via uv
make serve      # Start MkDocs dev server
make build      # Build static site
make deploy     # Deploy to GitHub Pages
make clean      # Remove build artifacts
```

## Tech Stack

- [MkDocs Material](https://squidfunk.github.io/mkdocs-material/) — documentation framework
- [mkdocs-static-i18n](https://github.com/ultrabug/mkdocs-static-i18n) — bilingual support
- Custom CSS — phone mockups, color swatches, visual demos
- [Geist](https://vercel.com/font) — typography

## License

MIT
