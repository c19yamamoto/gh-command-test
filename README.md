# ghコマンドテスト

## 使用したコマンドと効果
|コマンド|効果|
|---|---|
|`gh repo create`|リポジトリを作成する(対話型で各種設定を行う、ここではpublic にしてみる)|
|`gh pr create -a @me --draft --title "テスト1: 本文を追加"`|ドラフトで自分をアサインしたタイトル指定PRを作る|
|`gh pr create -a @me --draft --fill`|ドラフトで自分をアサインしたPRを作る(対話型でタイトルや本文を入力する)|
|`gh pr checkout 100`|PR番号100のPRをチェックアウトする|
|`gh co 100`|上記チェックアウトのエイリアス|
|`gh issue create --title "バグを修正する" --body "本文" --assignee @me`|タイトルと本文を指定して自分をアサインしたissueを作成する|
|`gh browse`|ブラウザでリポジトリを開く|
|`gh pr list --base HEAD --state merged --limit 5`|チェックアウトしているブランチにマージされたPRのうち最新5件を表示する|
