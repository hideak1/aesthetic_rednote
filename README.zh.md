# 小红书美学指南

> **🌐 Language / 语言 / 言語:** [English](README.md) | [中文](README.zh.md) | [日本語](README.ja.md)

让每一篇帖子都好看 —— 一份以视觉为核心的小红书内容设计指南。

## 内容导览

| 模块 | 主题 | 教程 |
|------|------|------|
| 1 | 封面设计 | 构图、字体排版、信息层级 |
| 2 | 配色 | 色彩基础、风格色板、搭配法则、工具实操 |
| 3 | 配图 | 选图、修图、多图编排、封面类型 |
| 4 | 文案美学 | 标题、正文排版、关键词 |
| 5 | 个人视觉风格 | 一致性、找到风格、风格迭代 |
| 6 | 品类风格适配 | 技术/开源、美食、旅行、穿搭美妆 |
| 7 | 视频美学 | 视频封面、剪辑节奏、字幕设计 |

**7 个模块**，**24 篇教程**，支持**中文、英文、日文**。

## 特色

- 手机模拟器展示 before/after 对比
- CSS 交互色卡和配色预览
- 视觉优先：~70% 示例演示，~30% 文字
- 明暗模式，玫瑰粉主题色
- 三语切换（中/英/日）

## 快速开始

需要 [uv](https://docs.astral.sh/uv/) 和 Python 3.10+。

```bash
git clone https://github.com/hideak1/aesthetic_rednote.git
cd aesthetic_rednote
make install    # 安装依赖
make serve      # 启动开发服务器 http://localhost:8000
```

## 命令

```bash
make install    # 安装依赖
make serve      # 启动 MkDocs 开发服务器
make build      # 构建静态站点
make deploy     # 部署到 GitHub Pages
make clean      # 清理构建产物
```

## 技术栈

- [MkDocs Material](https://squidfunk.github.io/mkdocs-material/) — 文档框架
- [mkdocs-static-i18n](https://github.com/ultrabug/mkdocs-static-i18n) — 多语言支持
- 自定义 CSS — 手机模拟、色卡、视觉演示
- [Geist](https://vercel.com/font) — 字体

## 许可证

MIT
