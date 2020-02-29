# 利用方法
1. 本リポジトリをクローン
  ~~~
  $ cd /path/to/
  $ git clone https://github.com/koreander2001/redmine-on-docker.git
  ~~~
2. DBのユーザー名、パスワードなどを設定
  ~~~
  $ cp .env.sample .env
  $ vim .env
  ~~~
3. 下記コマンドを実行
  ~~~
  $ docker-compose build
  $ docker-compose up -d
  ~~~
4. 「http://localhost:5000」にアクセス

# 参考URL
* [コンテナでRedmineの環境構築をやってみた](https://qiita.com/asubee/items/db6985549d83334d0a46)
