
# PHPとComposerのDocker環境

## 環境の構築と開始

```
# ビルド
docker compose build

# 起動
docker compose up -d

# コンテナに入る
docker compose exec app bash
```

## バージョンの確認

```
# PHPのバージョン
php -v

# Composerのバージョン
composer --version
```

## パッケージの管理

```
# 初回インストール（実行するとvendorディレクトリができる）
composer install

# パッケージの追加例
composer require monolog/monolog

# パッケージの削除例
composer remove monolog/monolog
```
