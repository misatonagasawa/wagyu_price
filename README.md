# Git Lesson

## リモートリポジトリとローカルリポジトリとはそれぞれ何でしょうか？
リモートリポジトリ:ネット上に配置して複数人で共有するためのリポジトリ。(個人開発用にも使用可)
ローカルリポジトリ:開発者一人ひとりが使用するために自分のPC上に配置するためのリポジトリ。


## プッシュとマージの違いは何でしょうか？
プッシュ：ブランチの内容をリモートのブランチに反映する
マージ：実装や改修など作業をリモートブランチに変更履歴を反映する

## コミットとプッシュの違い
コミット：ローカルに編集内容を保存
プッシュ：リモートに編集内容を保存

## コミットのメッセージはどのように書いてあげるのが最適でしょうか？
編集内容が読んだだけで分かるコミットメッセージを残すようにする


## ローカルでマージするフローと、プルリクエストでマージするフローの違いは何でしょうか？
ローカルでマージするとバグが起こっている場合気がつかない。プルリクエストを行うことで、自分ではない人にマージしてもらうためバグがバグが発見される。


## コンフリクトを起こしてしまった場合、どう対処すべきですか？
時と場合で異なるが、後先構わずどちらも取り込む場合、解決のために行なった作業を内容をコミットする。
一番良いのはソースコードを書いた人と相談すること。
