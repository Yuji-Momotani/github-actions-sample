# サンプルアプリケーション

静的なフロントエンドと Web API から成る、足し算アプリケーションです。

## 開発モードでの起動手順

サンプルアプリケーションは、以下の手順で開発モードで起動します。

```console
cd backend/
npm ci
npm run dev
```

## バックエンドをビルドして実行する手順

バックエンドをビルドして実行する場合は、以下のコマンドを実行してください。

```console
cd backend/
npm ci
npm run build
node dist/index.js
```

## バッチ

[![backend](https://github.com/Yuji-Momotani/github-actions-sample/actions/workflows/backend.yml/badge.svg)](https://github.com/Yuji-Momotani/github-actions-sample/actions/workflows/backend.yml)

`Actions` のタブから > 最新のテスト結果 > 右上の三点リーダー > `Create status badge`から作成できる
