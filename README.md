# reddit_ishikihikui
主な仕様

* 閲覧とか書き込み部分は全部RESまかせ
* スレタイダブルクリックで開く
* APIの仕様で1回のクエリで取れる最大数の100件を取得する
* 取得した一覧からのスレタイ検索が可能
* API経由でRedditからの検索も可能、(書式もそのままサポートできてるはずhttp://www.reddit.com/wiki/search)

既知のバグ・不具合・問題点

* ソート機能は無い
* ソースコードがガバガバ
* 開発に使った言語（なでしこ）が使ってるライブラリがかつてマルウェアに組み込まれたことがあるせいで一部のアンチウイルスソフトが激おこ



動作確認環境：Windows 7(x64) なでしこ1.549


ライセンス：MIT 

This software is released under the MIT License, see LICENSE.txt.

# インストール方法

このソースをダウンロードしてなでしこエディタで開き、一度実行して一通りの動作を行ってください。(なでしこエディタが依存性のあるDLLを自動選別してくれます。)
その後”ファイル(F)”＞”実行ファイル作成(M)”で完了となります。
実行ファイル形式に拘らないのであればソースのままなでしこで実行して頂いてかまいません。(実行速度はほぼ変わりません。)

"板一覧.txt"を同じフォルダに入れてないと動きません。

# 今後

今後は多分いちいちバイナリ配布せずにこっちをチマチマ更新していきます。


大き目の更新があったらバイナリ貼って告知します。
