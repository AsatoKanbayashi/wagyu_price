# Git Lesson

## リモートリポジトリとローカルリポジトリとはそれぞれ何でしょうか？

- リモートリポジトリはサーバー上にあり複数人で共有することができる
- ローカルリポジトリは一人が利用するためにPC上にある 


## プッシュとマージの違いは何でしょうか？

- プッシュはリモートリポジトリの内容をローカルに反映すること
- マージはあるブランチの変更を他のブランチに統合すること


## コミットとプッシュの違い

- コミットは変更内容をGitに保存すること
- プッシュは変更内容をリモートに反映させること



## コミットのメッセージはどのように書いてあげるのが最適でしょうか？

- 変更/保存内容がわかるように書く


## ローカルでマージするフローと、プルリクエストでマージするフローの違いは何でしょうか？

- 第三者にコードを確認してもらっているかどうか
- プレフィックス：番号や符号、識別子などの先頭部分に付加し、何らかの意味や情報を表す短い部分のこと  
例:preseason,preview


## コンフリクトを起こしてしまった場合、どう対処すべきですか？

1. 先にマージされた変更内容を取り込む
2. 後にマージしようとしている変更内容を取り込む
3. どちらの変更内容も取り込む
