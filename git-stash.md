# git stashについて
作業ディレクトリの変更点を一時的に退避させるコマンド

デフォルトで追跡されているファイルのみ退避できる

```
git stash list
```
一覧を見る
```
git stash apply stash@{0}
```
元に戻す
```
git stash drop stash@{0}
```
applyだけだとlistに残るので消すことができる
```
git stash pop stash@{0}
```
元に戻すのとlistから消すのを同時にできる