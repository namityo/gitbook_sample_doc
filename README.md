# Gitbookでドキュメント作成

## はじめに

Gitbookを利用する際は **Node.js** が必要になります。

まずはNode.jsを[インストール](https://nodejs.org/ja/)してください。

## このリポジトリをCloneしたら

1. まずは `node install` を実行してください。
2. `./node_modules/.bin/gitbook install` を実行してください。
3. `./node_modules/.bin/gitbook serve` を実行してください。
4. [http://localhost:4000](http://localhost:4000) アクセスしてください。

このドキュメントがWebブラウザ上で表示されます。

## 静的ファイルを作るには

`./node_modules/.bin/gitbook build` を実行してください。

`_book` フォルダに生成されたファイルをWeb上にアップロードすれば完了です。

## ゼロから作るよりもスタートアップを利用するといい

https://www.gitbook.com/book/azu/gitbook-starter-kit/details
