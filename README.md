# Laravel Mix Boilerplate for Static Site

## 使用法

1. `package.json` を開き、各種プロパティを変更してください。
```
"name": "foobar-japan",
"description": "FooBar Japan Corporate site",
```

2. `.env-sample` を複製し、名前を `.env` に変更してください。
```
$ cp .env-sample .env
```

3. 依存パッケージをインストールします。
```
$ npm i
```

4. 開発用コマンドを実行し、`http://localhost:3000` へアクセスすると、サンプルページが表示されます。
```
$ npm run dev
```

5. 本番環境へ反映する前には、本番用コマンドを実行してください。
```
$ npm run prod
```

## Usage

1. Open `package.json`, and update properties.
```
"name": "foobar-japan",
"description": "FooBar Japan Corporate site",
```

2. Duplicate `.env` as `.env-sample`.
```
$ cp .env-sample .env
```

3. Install dependencies.
```
$ npm i
```

4. Run command for development, then you can see sample page.
```
$ npm run dev
```

5. Before deploying, run command for production.
```
$ npm run prod
```
