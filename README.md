# blackjack

コンソール画面上で遊ぶブラックジャックを開発しました。

プレイ人数を増やしCPUとプレイできる機能を開発中。

## 環境構築

```bash
# Docker イメージのビルド
docker-compose build

# Docker コンテナの起動
docker-compose up -d

# Docker コンテナ内でコマンドを実行する
docker-compose exec app php -v

# Docker コンテナの停止・削除
docker-compose down
```

## 遊び方

```bash
# blackjackディレクトリ下でコマンドを実行
docker-compose exec app php BJMain.php
```
