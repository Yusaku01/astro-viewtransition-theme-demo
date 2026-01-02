# astro-viewtransition-theme-demo

`astro-viewtransition-theme` を試すためのデモプロジェクト。AstroのView Transitionsと連携し、テーマ切り替え時の挙動を確認する。

## このプロジェクトの目的

- `astro-viewtransition-theme` の導入手順と使い方を最小構成で確認する
- View Transitionを使ったテーマ切り替えの動作を検証する
- 変更の影響を小さく保った検証用ベースとして使えるようにする

## 機能

- `ThemeInit` - 初期テーマの適用と同期
- `ThemeToggle` - テーマ切り替えボタン
- `ClientRouter` - View Transitionsを有効化するためのルーター

## プロジェクト構造

```
src/
├── layouts/       # ThemeInit/ThemeToggle を組み込んだレイアウト
├── pages/         # デモページ
└── assets/        # 画像やスタイルなどのアセット
public/            # 公開アセット（favicon など）
```

## コマンド

| コマンド | 説明 |
|---------|------|
| `pnpm install` | 依存関係のインストール |
| `pnpm dev` | 開発サーバー起動（localhost:4321） |
| `pnpm build` | 本番ビルド |
| `pnpm preview` | ビルドのプレビュー |
