# Zenn CLI

* [📘 How to use](https://zenn.dev/zenn/articles/zenn-cli-guide)

## Building

プロジェクトをデフォルト設定で初期化
`package.json`があればskip

```sh
npm init --yes
```

zenn-cliを導入

```sh
npm install zenn-cli
```

zenn用のディレクトリ構成など整備
すでに`books`や`articles`がある場合は不要

```sh
npx zenn init
```

command version up

```sh
npm install zenn-cli@latest
```

## Usage

新規記事作製
作製した記事にはランダムslagが付与される。

```sh
npx zenn new:article
```

preview

```sh
npx zenn preview
```

記事を公開する場合は記事の先頭の`published` を`true`に変更してPushすると自動で公開される。
