# gatsby for docker
## セットアップ
```bash
# コンテナのビルド、立ち上げ
$ ./bin/bootstrap.sh
```
## コンテナ内に入る
```bash
$ docker exec -it gatsby bash
```
## コンテナ内での作業
### devサーバーの立ち上げ
```bash
$ npm run develop
```