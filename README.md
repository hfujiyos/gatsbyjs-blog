# GatsbyJS

## 環境構築

- バージョン確認

  ```sh
  $ node -v
  v16.14.2
  $ npm -v
  8.7.0
  ```

- GatsbyJS グローバルインストール

  ```sh
  $ npm install -g gatsby-cli
  $ gatsby -v
  Gatsby CLI version: 4.18.1
  ```

- GatsbyJS テンプレート（gatsby-starter-blog）のインストール

  ```sh
  $ npx gatsby new gatsbyjs-blog https://github.com/gatsbyjs/gatsby-starter-blog
  ```

- 開発環境動作確認

  ```sh
  $ cd gatsbyjs-blog
  $ gatsby develop
  ```

  http://localhost:8000/

## ディレクトリ構成

- /content/blog/
  - この中にブログの中身を記述するディレクトリとファイルが入っています。ちなみに Gatsby のブログはマークダウン(.md)で書きます。が、マークダウンを拡張した MDX を使うようにした方がいいと思います。
- /src/components/
  - この中にはコンポーネントが入っています。ブログを構成する部品（サイドバー、フッター、ヘッダー）やその部品を使い回したりするためのファイルが入っています。
- /src/images/
  - 画像ファイルが入っています。そのままですね。別にここに入れなくてもいいです。Gatsby のアイコンとかが入ってます。
- /src/pages/
  - いわゆる固定ページ用のディレクトリです。ここにあるファイルはそのままルートディレクトリにぶら下がっちゃいます。
- /src/templates/
  - ブログなんかは、それぞれのページが同じ形をしています。そのテンプレートを置いておくディレクトリです。ビルド時にここにあるファイルにデータを渡して、それぞれのブログページ等を作っていきます。

## 参考文献

- [YouTube ｜マイケル｜ Gatsby 入門](https://bit.ly/3PytG4m)
- [GatsbyJS 公式サイト｜ How to use gatsby-cli](https://www.gatsbyjs.com/docs/reference/gatsby-cli/)
- [GatsbyJS テンプレート｜ gatsby-starter-blog](https://www.gatsbyjs.com/starters/gatsbyjs/gatsby-starter-blog)
