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

  - gatsby-casper は見当たらないため、gatsby-starter-blog を導入

  ```sh
  $ npx gatsby new gatsbyjs-blog https://github.com/gatsbyjs/gatsby-starter-blog
  ```

- 開発環境動作確認

  ```sh
  $ cd gatsbyjs-blog
  $ gatsby develop
  ```

  http://localhost:8000/

## 参考文献

- [YouTube ｜マイケル｜ Gatsby 入門](https://bit.ly/3PytG4m)
- [GatsbyJS 公式サイト｜ How to use gatsby-cli](https://www.gatsbyjs.com/docs/reference/gatsby-cli/)
- [GatsbyJS テンプレート｜ gatsby-starter-blog](https://www.gatsbyjs.com/starters/gatsbyjs/gatsby-starter-blog)
