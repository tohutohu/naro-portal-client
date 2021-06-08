# kuragate-client

Web エンジニアになろう講習会課題のポータルリポジトリ(Client)

## Router の処理のメモ

~~少し複雑で、自分でも分からなくなりそうなので書く
Store(Global に管理できる状態変数)に currentPage という名前で Page を保存/また userProfile という名前でログイン情報を保存
Router は currentPage や userProfile に変更があるたびに(Receive アクションが実行されて)自身の State とそれを同期して、ページを遷移させる(ここでログイン判定も行う)
他のコンポーネントは Store にアクセスして currentPage を変更すれば良い~~

###### 出来てなかった

出来てませんでした。結局 Hash が変わったのを検知する方法に戻ります。

## ToDo

#### それぞれのコンポーネントについて、ルーターを作る際のエラー回避の為に一次的にコメントアウトしている部分があるので、実装しなおす

~~Login~~

~~Home~~

~~Settings~~

Signup

#### パスワード間違えの時も内部エラーと出てしまう。

~~原因分からず~~
サーバー側の原因
