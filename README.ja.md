# 小紅書（RED）美学ガイド

> **🌐 Language / 语言 / 言語:** [English](README.md) | [中文](README.zh.md) | [日本語](README.ja.md)

すべての投稿を美しく —— ビジュアルファーストの小紅書コンテンツデザインガイド。

## コンテンツ

| パート | テーマ | チュートリアル |
|--------|--------|----------------|
| 1 | カバーデザイン | 構図、タイポグラフィ、レイアウト |
| 2 | 配色 | 色彩理論、スタイルパレット、配色ルール、ツール |
| 3 | 画像 | 選び方、編集、複数画像の配置、カバータイプ |
| 4 | コピーライティング | タイトル、本文レイアウト、キーワード |
| 5 | ビジュアルアイデンティティ | 一貫性、スタイル探し、スタイルの進化 |
| 6 | カテゴリ別スタイル | テック・コーディング、グルメ、旅行、ファッション・美容 |
| 7 | 動画の美学 | 動画カバー、編集リズム、字幕デザイン |

**7パート**、**24チュートリアル**、**中国語・英語・日本語**対応。

## 特徴

- スマホモックアップによるbefore/after比較
- CSSカラースウォッチとパレットプレビュー
- ビジュアルファースト：デモ約70%、テキスト約30%
- ライト/ダークモード、ローズピンクのアクセントカラー
- 3言語切替（中/英/日）

## クイックスタート

[uv](https://docs.astral.sh/uv/) と Python 3.10+ が必要です。

```bash
git clone https://github.com/hideak1/aesthetic_rednote.git
cd aesthetic_rednote
make install    # 依存関係をインストール
make serve      # 開発サーバーを起動 http://localhost:8000
```

## コマンド

```bash
make install    # 依存関係をインストール
make serve      # MkDocs 開発サーバーを起動
make build      # 静的サイトをビルド
make deploy     # GitHub Pages にデプロイ
make clean      # ビルド成果物を削除
```

## 技術スタック

- [MkDocs Material](https://squidfunk.github.io/mkdocs-material/) — ドキュメントフレームワーク
- [mkdocs-static-i18n](https://github.com/ultrabug/mkdocs-static-i18n) — 多言語サポート
- カスタム CSS — スマホモックアップ、カラースウォッチ、ビジュアルデモ
- [Geist](https://vercel.com/font) — タイポグラフィ

## ライセンス

MIT
