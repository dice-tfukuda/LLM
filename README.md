# 概要
NLP技術を文章を分析する。

# 実行環境：Docker
**環境構築(以下のコマンドは一度だけ実行してください)**
```
git clone git@github.com:dice-tfukuda/nlp.git
cd nlp

※buildは環境は環境によって以下のどちらかを実行してください。
[Windows]
docker build -t dice_nlp:latest
[mac]
docker build -t dice_nlp:latest --platform linux/amd64 .

docker-compose up -d
docker ps
※このコマンドを実行後dice_ocr:latestのコンテナが立ち上がっていることを確認してください。
```

**接続方法**
ブラウザで`localhost:8888`にアクセスするとJupyter Labに接続できます。

**作業終了時のコマンド**
```
docker-compose down
```
**作業再開**
```
docker-compose up -d
```
