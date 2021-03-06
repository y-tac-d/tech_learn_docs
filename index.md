# Webの基礎知識 目次
- [はじめに](start.md)

# [ブラウザでWebページが表示されるまでを追いかけてみよう](web_browse/)
1. [ブラウザのアドレスバーにURLを入れる](web_browse/1.md)
2. [URLををもとに接続したい相手を探す](web_browse/2.md)
3. [クライアントとサーバの接続を確立する](web_browse/3.md)
4. [クライアントの要求をサーバに伝える](web_browse/4.md)
5. [サーバが応答を返却する](web_browse/5.md)
6. [受け取った応答をブラウザが解釈する](web_browse/6.md)
7. [HTMLを読み込む](web_browse/7.md)
8. [CSSを適用する](web_browse/8.md)
9. [JSの処理を実施する](web_browse/9.md)
10. [画面が表示される！](web_browse/10.md)

# 実際にサーバを用意してみよう
## Webページの公開に必要なもの
- サーバ
- ドメイン
## 実践編:AWS ec2
### サーバを作ろう！
1. [インスタンスを作成する](handson/server/aws_ec2/server_1.md)
### ドメインを設定しよう！
1. 独自ドメインを手に入れる
2. インスタンスに固定IPを設定する
3. 独自ドメインと固定IPを紐付ける
### サーバを片付けよう！
1. 独自ドメインとIPの紐付けを削除する
2. 固定IPを開放する
3. インスタンスを停止する

# 静的なサイトと動的なサイトに付いて理解しておこう
- 静的なサイト
- 動的なサイト

# クラウドについても知っておこう
- 結局何が嬉しいの？
- こんなサービスがある
    - 計算機能系サービス
        - サーバ
        - ファンクション
        - コンテナ
    - ネットワーク系サービス
        - ロードバランサー
        - CDN
    - いろんなマネージド・サービス
        - 認証

# コンテナについても知っておこう！
- コンテナって何？
- コンテナ実行環境の色々

# HTTPSについて知っておこう！
- httpsって何？
- SSL証明書って何？
- 何をしなきゃいけないの？
- SSLを導入してみよう！
    - let's encryptを利用したSSL認証