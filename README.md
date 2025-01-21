# README

このリポジトリの構成
- Ruby 3.3.6
- Rails 7.2.1
- Node.js v20.18.0
- esbuild (JavaScriptバンドラー )
- Tailwind (CSSフレームワーク)
- PostgreSQL (データベース)
- 開発環境の構築 Docker・docker composeを使用


このリポジトリを使ってRenderにデプロイしたときの設定

Language：Ruby
Region：Singapore
Build Command：
```
./bin/render-build.sh
```
Start Command
```
bundle exec rails server
```
環境変数設定に
RAILS_ENV　production
を追加

