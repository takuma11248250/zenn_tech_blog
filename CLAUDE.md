# Zenn記事執筆プロジェクト

## プロジェクト概要

ZennのCLI（zenn-cli）を使って記事を執筆・公開するリポジトリ。
ZennアカウントはGitHub連携で管理。公開先：https://zenn.dev/ordinary_person

## 記事の方向性

- **主テーマ**：マネジメント・組織開発・コーチング・リーダーシップ・データエンジニアリング
- **対象読者**：エンジニア〜EM志望者、データエンジニア
- **スタイル**：自分の経験や考えを率直に書く一人称スタイル

## ディレクトリ構成

- `articles/` — 記事ファイル（Zenn CLIで生成）
- `books/` — 本ファイル（必要に応じて）

## zenn-cli

- 記事作成：`npx zenn new:article`
- プレビュー：`npx zenn preview`
- ドキュメント：https://zenn.dev/zenn/articles/zenn-cli-guide

## 記事執筆の注意事項

- frontmatterの`published: false`のままでは公開されない（公開時は`true`に変更）
- slugはファイル名として使われる。変更するとURLが変わるので公開後は変えない
- 記事ファイルはコミット＆プッシュで公開される（git管理が公開フロー）
