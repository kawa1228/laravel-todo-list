# Laravel Todo List

# 環境構築

## dockerに移動
cd docker

## dockerビルド

docker-compose build --no-cache

## dockerコンテナ をデーモン起動する

docker-compose up -d

## dockerの状態を表示

docker-compose ps

## bash に入る

docker exec -it todo-list-laravel bash

## appに移動

cd app

## ライブラリをインストール

composer install

## サーバーを起動

php artisan serve --host 0.0.0.0

http://localhost:8000/

## dockerコンテナから抜ける

exit

## 作業が完了したらクリーンアップ

docker-compose down
