# Git Lesson

## リモートリポジトリとローカルリポジトリとはそれぞれ何でしょうか？
- リモートリポジトリ：サーバー上にあるものがリモートリポジトリ
- ローカルリポジトリ：手元のＰＣにあるものがローカルリポジトリ

## プッシュとマージの違いは何でしょうか？
- プッシュ：ローカルリポジトリの変更をリモートリポジトリにアップロード すること
- マージ：ブランチで作業したものをメインブランチへ取り込むこと

## コミットとプッシュの違い
- コミット：コミットはローカルリポジトリでの変更を保存する
- プッシュ：ローカルリポジトリのコミットをリモートリポジトリへアップロードすること

## コミットのメッセージはどのように書いてあげるのが最適でしょうか？
- コミットの修正内容などを記載する。変更内容を簡潔に記述であれ　　ば新機能追加など


## ローカルでマージするフローと、プルリクエストでマージするフローの違いは何でしょうか？
1. 他のブランチの変更を自分の作業に取り込むことができる マー　ジ後リモートリポジトリで他の人と共有される
1. Githubなどプラットフォームでマージが行われる。プルリク　　エストは他の人やチームの人が変更を確認し、フィードバック　　　する機会を与えることができる。 

## コンフリクトを起こしてしまった場合、どう対処すべきですか？
- git status でファイルを特定しファイルを表示、修正後両方のファイルの統合かどちらを使用するかを決定し、変更をコミットしてマージするとよい
