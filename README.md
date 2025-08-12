# test-notes-content

開発環境用のテストコンテンツリポジトリです。

## 概要

このリポジトリは [arakoshi/notes](https://github.com/arakoshi/notes) の開発環境（developブランチ）で使用するテスト用コンテンツを管理します。

## 構造

```
posts/
├── tag-navigation-test.md    # タグナビゲーション機能のテスト
└── development-sample.md     # 開発環境のサンプル記事
```

## 使用方法

1. `arakoshi/notes` の develop ブランチにプッシュ
2. GitHub Actions が自動的にこのリポジトリからコンテンツを取得
3. Cloudflare Pages の開発環境にデプロイ

## テスト用タグ

- `#テスト` - 機能テスト用
- `#開発` - 開発関連
- `#日記` - 日記形式のサンプル
- `#プログラミング` - 技術的な内容
- `#サンプル` - サンプルデータ

## 注意事項

- このリポジトリはテスト専用です
- 本番環境では使用されません
- 自由にコンテンツを追加・編集してください