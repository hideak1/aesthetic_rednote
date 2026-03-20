# Xiaohongshu Aesthetics Guide

> **🌐 Language / 语言 / 言語:** [English](README.md) | [中文](README.zh.md) | [日本語](README.ja.md)

Make every post beautiful — a visual-first guide to Xiaohongshu content design.

## What's Inside

| Part | Topic | Tutorials |
|------|-------|-----------|
| 1 | Cover Design | Composition, Typography, Layout |
| 2 | Color | Color Theory, Style Palettes, Matching Rules, Tools |
| 3 | Imagery | Selection, Editing, Arrangement, Cover Types |
| 4 | Copywriting | Titles, Body Text, Keywords |
| 5 | Visual Identity | Consistency, Finding Your Style, Evolution |
| 6 | Style by Category | Tech & Coding, Food, Travel, Fashion & Beauty |
| 7 | Video Aesthetics | Video Covers, Editing Rhythm, Subtitles |

**24 tutorials** across **7 parts**, available in **Chinese, English, and Japanese**.

## Features

- Interactive phone mockups showing before/after comparisons
- CSS color swatches and palette previews
- Visual-first approach: ~70% demos, ~30% text
- Light/dark mode with rose pink accent
- Trilingual (zh/en/ja) with language toggle

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
- [mkdocs-static-i18n](https://github.com/ultrabug/mkdocs-static-i18n) — trilingual support
- Custom CSS — phone mockups, color swatches, visual demos
- [Geist](https://vercel.com/font) — typography

## License

MIT
