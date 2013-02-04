# MyGithub - Githubにある自分のコードを高速に検索

## 準備:

- スライドはChromeで開く : リロードを忘れずに
// 本当は認証ONにするべきだけど、時間短縮のため省略
// - Authorized applications [MyGithub] を [Revoke]
// - Github を Sign out
- bundle exec bin/mygithub web -n で起動
- http://127.0.0.1:9295/login を開いておく

## スライド(1分):

MyGithub - Githubにある自分のコードを高速に検索
ongaeshiといいます。

## デモ(1分30秒):

- Sign In
- Github画面
- 今までGithubにpushしたレポジトリをダウンロードし、検索用のインデックスを張ってくれています。

- ホーム画面 : アイコンもGithubから取得しています、全部で55個のレポジトリ、2663個のファイルをコミット

- 検索1: def test, aaaaa, bbbb : 2000ファイル程ありますが、インデックス化されているのでかなり高速に検索することが可能です。10万ファイル位あってもこれくらいのスピードで見つけることが可能です
- 検索2: 連番画像 : 日本語ももちろん可能です。
- 検索3: ComicAppBuilderに移動して、Comic : また、レポジトリを絞りこんで検索したり
- 検索4: s:.m : 拡張子やファイル名で絞り込むことも可能です。

Githubアイコンをクリックすることで、関連するGithubのサイトに移動することも可能です。

最後にrequireの相対パス指定のコードを見つけて終わりにしたいと思います。
- require __FILE__ join s:rb

## ありがとうございました
RubyGemsにアップする予定なので、よかったら使ってみて下さい。

どうもありがとうございました。

