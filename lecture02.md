# バージョン管理システム
## 概要
* 開発上の人的ミスを折り込んで、こまめにセーブ＆ロードしながら開発を進めるためのシステム。
* **Git**とSVNがある。前者が主流。

## SVN
* 分散型ではない。リモートリポジトリ（保存場所）のみ。

## Git
* 分散型。ローカルとリモートの2つのリポジトリでバージョンを管理する。
* 複数人で開発する際は、最新のリモートのデータを取得してから作業を開始するのが大事。
* プルリクエスト。
    ブランチをリモートにプッシュし、変更をメインブランチに反映して良いかどうか、他の開発者にレビューしてもらう。
    変更は差分形式で確認。
    よく使うコマンド4つ。
 1. git add
 2. git commit
 3. git push
 4. git pull
* 検索：プルリクエスト　テンプレート　おすすめ

# Markdown
* 記号で文字を装飾する機能。HTMLタグに変換される
* 参考：[Markdown記法 チートシート](https://qiita.com/Qiita/items/c686397e4a0f4f11683d)
* cloud9だとPreview機能使いながら書くのが楽？

# チーム開発におけるバージョン管理
* GitHub-FlowとGit-Flow
* developブランチ？？？
* コンフリクトはpullの段階で分かるらしい???
* (後で復習)プルリクエスト Issue コメント　承認

# おまけ
vim
保存して終了:wq
保存せず終了:q
