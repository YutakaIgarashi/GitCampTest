# gitコマンド辞典

## git branch
現在のブランチの確認.&新しいブランチを作成する（上に追加してみる）。

## git init
リポジトリをカレントディレクトリに作成する。

## git add
コミットするファイルを指定する。

## git stash
現在の状態を保存する。

## git commit
インデックスに追加されたファイルをコミットする。

## git bisect
二分探索によって問題箇所を特定する。

## git pull --rebase
マージコミットが増えずに済む。

### git rebase --continue
git rebaseの変更を適応する。
rebase中に競合が起きたとき、解決後に実行しrebaseを終了する。

* エディタに入った競合の印（<<<<<<<<<）を参考に、競合をあるべき姿に修正。
* 「git add xxxx.xx」で再度インデックスに追加。
* 「git rebase --continue」でリベースを継続。


## git fetch --prune
リモートリポジトリの削除情報をローカルに更新する。

## git clone
リポジトリをコピーする。

## git push
リモートリポジトリに変更を書き込む。

## git diff
インデックスと作業ディレクトリの差分を表示する。

### git diff –cache
HEADとインデックスの差分を表示する。

## git remote
リモートリポジトリの一覧表示。

## git reset
return origin!!!

### git reset -hard HEAD
作業フォルダで行った編集をすべてクリアする。

## git rebase --continue
git rebaseの変更を適応する
rebase中に競合が起きたとき、解決後に実行しrebaseを終了する
HEADとインデックスの差分を表示する

## git reflog
過去にHEADが指していたコミット一覧をを表示する。

## git clean
作業ディレクトリから追跡対象外のファイルを削除する。

## git rebase --continue
rebase を継続する。

## id/14でのコミット
## git checkout [branch]
ブランチを変更する

## git branch **
make branch!!

