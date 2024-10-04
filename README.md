# ghコマンドテスト

## 使用したコマンドと効果
|コマンド|効果|
|---|---|
|`gh repo create`|リポジトリを作成する(対話型で各種設定を行う、ここではpublic にしてみる)|
|`gh pr create -a @me --draft --title "テスト1: 本文を追加"`|ドラフトで自分をアサインしたタイトル指定PRを作る|
|`gh pr create -a @me --draft --fill`|ドラフトで自分をアサインしたPRを作る(対話型でタイトルや本文を入力する)|
