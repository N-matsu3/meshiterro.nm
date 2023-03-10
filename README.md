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

2023/03/06
🍚 モデル・テーブルの作成
 　id,created_at, updated_at, の3つのカラムは自動で作成されるということを見落としていた。

2023/03/07
🍚 コントローラの命名の規則というかタイピングミスで複数形に出来てなかった。
　 そのためエラーが起きてしまっていた
　 error：uninitialized constant UsersController
　 コントローラを作り直すという、ちょっと手間が発生
　 reils d controller コントローラ名で一度消して、、、
　 今後注意！

　 👉 投稿機能の作成（5）で画像投稿、一覧画面、詳細画面でそれぞれ遷移できてないのだけど、いいのかな、、、？
　    いや、全部リンクができないな。次回調べよう

2023/03/09
🍚　前回のリンクに関してはまたアプリとプレビューの更新ができていないだけだったのでおｋ
　　時間があまり取れず、勉強が思うように進まなかった。。。
　　
2023/03/10
🍚　👉SNSらしい機能を追加しよう(1) - コメント機能
　　　「ネストする」が理解しきれていないかも
　　👉SNSらしい機能を追加しよう(2) - いいね機能
　　　ログインしていないとエラーが起こる？
　　👉　
　　　「` before_action' for」...まさかの「before」の前に全角の空白が入ったことによるエラーが起きていた。
　　　空白を削除してOK！