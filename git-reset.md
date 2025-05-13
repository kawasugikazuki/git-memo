# git resetについて
間違ってadd、commitしたときに戻るためのコマンド

```
git reset  --soft HEAD^
```
直前のcommitをなかったことにする
```
git reset  --mixed HEAD^
```
直前のcommitとaddをなかったことにする
```
git reset  --hard HEAD^
```
直前の変更(commit、add、コード)をなかったことにする