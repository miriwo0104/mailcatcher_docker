# 概要

- mailcatcherのコンテナが起動するだけのリポジトリです
- .envでローカルマシン側のポートを変更できます

# 使い方

1. 初回
    1. 取得
    1. docker-compose.ymlがあるディレクトリで下記コマンドを実行

        ```terminal
        $ docker-compose up -d
        ```

    1. デフォルトのポートフォワーディング設定なら下記にアクセスすることでmailcatcherを確認できます。
        1. [http://localhost:1080/](http://localhost:1080/)
1. .envを書き換えたら
    1. docker-compose.ymlがあるディレクトリで下記コマンドを実行

        ```terminal
        $ docker-compose up -d --build
        ```