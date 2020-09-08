# cologne
- 香水お試しサイト

### HOW TO BUILD
1. clone project
```
git clone git@github.com:shun012526/cologne.git
```

2. build by local
```
(初動時は biuld オプションで実行)
docker-compose up --build

(立ち上がったら web ブラウザで localhost:3000 確認)

(2回目以降はこちらのコマンド)
docker-compose up
```

3. モジュールを追加する
  - (docker-compose コマンドを実行するときは docker-compose.yml が存在するディレクトリで実行)

```console
(起動中のコンテナの中に入る場合)
docker-compose exec web /bin/bash

(コンテナの中でライブラリ追加 Commander の場合)
# yarn add commander

(コンテナ終了)
# exit

(コンテナの外からモジュールを追加したいとき vuex-persistedstate の場合)
docker-compose exec web yarn add vuex-persistedstate
```
