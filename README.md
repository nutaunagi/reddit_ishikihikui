# reddit_ishikihikui
主な仕様
* 閲覧とか書き込み部分は全部RESまかせ
* スレタイダブルクリックで開く
* APIの仕様で1回のクエリで取れる最大数の100件を取得する
* 取得した一覧からのスレタイ検索が可能


既知のバグ・不具合・問題点
* 長いスレタイを取得するとスレタイ列の幅がおかしくなる
* ソート機能が無い
* 取得済みのスレからしか検索できない
* 絞込み検索をサポートしていない
* 開発に使った言語（なでしこ）が使ってるライブラリがかつてマルウェアに組み込まれたことがあるせいで一部のアンチウイルスソフトが激おこ(dllに対して反応してしまう)


動作確認環境：Windows 7(x64) なでしこ1.549


ライセンス：アフィカス以外なら好きに使ってよし

# インストール方法

このソースをダウンロードしてなでしこで”ファイル(F)”＞”実行ファイル作成(M)”で完了

"板一覧.txt"を同じフォルダに入れてないと動きません。

# 今後

今後は多分いちいちバイナリ配布せずにこっちをチマチマ更新していきます。
