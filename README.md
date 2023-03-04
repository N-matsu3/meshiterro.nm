# README

This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

* Ruby version

* System dependencies

* Configuration

* Database creation

* Database initialization

* How to run the test suite

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions

* ...
# meshiterro.nm

2023/03/04
🍚 認証機能がでてこないのだが

2023/03/05
🍚 前回の認証機能エラーはブラウザが更新できていなかっただけだった。
　 動的なヘッダーが出てこなくなってしまったが、解決済。というのも「layout」フォルダがあるべきフォルダ内になく、読み込まれなかった。
　 元の場所に戻し解決。