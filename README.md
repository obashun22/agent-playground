# agent-playground

AI Agent に関する情報をまとめた静的 HTML サイトです。

## プロジェクト概要

AI Agent の基礎知識や LLM（大規模言語モデル）に関する情報を、わかりやすく整理して提供する学習用サイトです。

### 主な機能

- **AI Agent 入門ページ** (`index.html`) — AI Agent の概要・特徴・仕組みを解説
- **LLM 概要ページ** (`llm.html`) — 主要な LLM モデルの情報を整理
- **404 ページ** (`404.html`) — カスタムエラーページ

## 使用技術

| 技術 | 用途 |
|------|------|
| HTML / CSS | ページ構成・スタイリング |
| Google Fonts (Inter, Noto Sans JP) | タイポグラフィ |

## セットアップ

静的 HTML サイトのため、特別なビルド手順は不要です。

```bash
# リポジトリをクローン
git clone https://github.com/obashun22/agent-playground.git
cd agent-playground

# 任意のHTTPサーバーで配信（例: Python）
python3 -m http.server 8000
```

ブラウザで `http://localhost:8000` にアクセスしてください。

## ディレクトリ構成

```
agent-playground/
├── index.html       # AI Agent入門ページ
├── llm.html         # LLM概要ページ
├── 404.html         # カスタム404ページ
├── styles/
│   └── common.css   # 共通スタイルシート
└── README.md
```
