## 作成者
- 学籍番号：k20125
- 氏名：吉田佑吏
- グループ： 11
    - メンバー
        - k21109 牧村颯真（チームリーダー）
        - k21060 阪口穂香
        - k20235 永田朋也
        - k21045 葛谷飛羽
        - k21081 土井菜乃葉
        - k21108　　前野凜

## 仕様
- flaskを使用した愛知工業大学の掲示板アプリ
- データベースを使用して登録ユーザ、現在あるスレッド、各スレッドの中身を保存
- 登録にユーザー名、学籍番号、パスワードを使用
- スレッドを自由に立ち上げることができる(削除は立ち上げた本人のみ)
- 各スレッドでは自由にコメントができる(削除は本人のみ)
- 検索機能を実装し、知りたい情報がすぐに見つかる機能の作成
- CSSで画面を見やすくする

## アプリ完成イメージ
- ログインページのイメージ（login.pngもMoodleへアップロードした）
- サインアップページのイメージ (sinup.png)
- スレッド選択画面のイメージ(thread.png)
- スレッド表示画面(comment.png)

## 作業分担
- ログイン機能の作成（担当：牧村颯真）
- 機能単位の結合(担当：牧村颯真)
- ログイン、サインアップページの作成（担当：阪口穂香）
- データベースの構築と制御（担当：永田朋也，吉田佑吏）
- スレッドの検索機能の実装(担当 : 永田朋也)
- flaskによるルーティング処理（担当：葛谷飛羽）
- スレッドの表示画面の作成とサイトの装飾(html, css)（担当：土井菜乃葉, 前野凜）

## 作業報告
- DBのテーブルの構成や必要なテーブル、カラムなどをグループで話し合った。
- スレッド内でのコメントをDBに追加する処理やスレッドの名前に応じたスレッドの中身をjsonファイルとして返す処理を完成させた(永田朋也さんと共に)
    - プルリクエストへのリンク 
	https://github.com/2022AIT-OOP2-G11/ziyuukadai/pull/18
    - 上のプルリクエストがマージされた
- 現在はユーザーを管理するDBの構築とその制御を行うメソッドを作成中

## グループ内でお世話になった人2〜3名を理由とともに挙げる
- 何度かミーティングを行った時に、現状の問題点や個人の次回までのタスクを技術力や進捗を見極めて割り当ててくれたため、非常に作業がしやすかった (k21109 牧村颯真)
- 同じDB部分を担当したが、スレッド管理のDBを素早く作成していた。その後、実装方法などを教えてもらいました。（k20235 永田朋也）
- ミーティングの時に、内容をメモしてくれていたため、ミーティング後に個人で内容を確認や振り返りをするときに作業がしやすかった。(k21060 阪口穂香)

## 振り返り（感想含む）と次回までの作業予定
- 担当部分としては計画的には進んでいる。
- 今回は、詳しい他のグループメンバーにかなり助けられた部分があったため、次回は自身でも実装できるように意識する

