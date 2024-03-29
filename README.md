# Express Web API Template

自分用のexpressサンプルテンプレートです。

## 構築方法

このリポジトリはテンプレートリポジトリとなっている。

右上の「Use this template」からリポジトリを作成して使用する。

## 実行方法

ビルドツールに vite が使用されている。

そのため、 vite の仕様に基づく。

### デバッグ実行

```sh
yarn vite dev
```

## 説明

各パッケージは以下の目的となっている。

|パッケージ名|目的|
|:--|:--|
|[express](https://github.com/expressjs/express)|Webアプリケーションフレームワークとして利用するため|
|[cors](https://github.com/expressjs/cors)|CORS対策のため|
|[express-validator](https://github.com/express-validator/express-validator)|バリデーションチェックのため|
|[node-fetch](https://github.com/node-fetch/node-fetch)|サンプルAPI呼出のため|
|[typescript](https://github.com/microsoft/TypeScript)|開発言語として利用するため|
|[vite](https://github.com/vitejs/vite)|ビルドツールとして利用するため|
|[vite-plugin-node](https://github.com/axe-me/vite-plugin-node)|viteを用いてNode.jsアプリケーションをホストするため|

※@typesは型情報なため省略

その他必要な処理は [Express middleware](https://expressjs.com/en/resources/middleware) の **Replaces built-in function** を参照して追加すること。
