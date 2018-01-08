# Gitbookの問題点

## Windows環境で使いづらい

Windows環境ではGitbookは次の点で使いづらい

* `gitbook serve`のファイル監視でエラーが発生する

### `gitbook serve`のファイル監視でエラーが発生する

`gitbook serve` コマンドはファイルの変更を検出して、HTMLファイルを再生成する機能がある。
そのため、編集しながらWebブラウザで表示を見る事ができる。

しかし、Windowsではこの機能が正常に動作しない。[^※1]

{% hint style='tip' %}
これを解決する方法には次の2つがあります。
* Dockerを利用する
* WSL(windows subsystem for linux)上でgitbookを動作させる
{% endhint %}

## 日本語の情報が乏しい

良いライブラリは沢山ありそう。だけど**日本語の情報が少ない**！

[GitBook Plugins](https://plugins.gitbook.com/)というサイトがあるのでそこで探すのが吉。


[^1] Ver3.2.3の問題らしい？
