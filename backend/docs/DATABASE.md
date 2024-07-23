# Databaseのセットアップ
以下のコマンドを実行する。
```bash
$ docker compose run backend bin/rails db:create
$ docker compose run backend bin/rails db:create RAILS_ENV=test
```
