# nuxt3-ssg

## Overview

Nuxt.js v3 で SSG (静的サイトジェネレート) をするサンプルプログラムです。
以下の記事を解説するために作成したリポジトリです。

This is an example program for SSG (Static Site Generate) in Nuxt3.
This is a repository created to explain the following article.

- [Nuxt3 で SSG (静的サイトジェネレート) する方法](https://std9.jp/articles/01g37q8qg405a7c7d68mwyeg31/)

## Requirement

- Node.js (v16.14.2)
- Ubuntu 20.04 もしくは WSL2 環境。macOS 環境でも恐らく可能

  (素の Windows 環境では nuxt:3.0.0-rc.3 の不具合で npm run generate ができません。)

## Setup

```shell
# 依存関係のパッケージをインストール
$ npm i

# 開発環境で実行 (http://localhost:3000/)
$ npm run dev

# 本番環境向けにSSGビルド (静的サイトジェネレート)
$ npm run generate
```

## Author

[twitter](https://twitter.com/hikaru_firecamp)
