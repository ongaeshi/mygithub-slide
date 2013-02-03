# MyGithub - Githubにある自分のコードを高速に検索

## 準備:

- スライドはChromeで開く : リロードを忘れずに
- Authorized applications [MyGithub] を [Revoke]
- Github を Sign out
- bundle exec bin/mygithub web -n で起動
- http://127.0.0.1:9295/login を開いておく

## スライド(1分):

最初だけ英語?

## デモ(1分30秒):

- Sign In
- Github画面
- すると、私が今までGithubにpushしたレポジトリをダウンロードし、検索用のインデックスを張ってくれます。

- ホーム画面 : アイコンもGithubから取得しています、全部で55個のレポジトリ、2663個のファイルをコミット
- パッケージ画面 : Githubにpushした全てのレポジトリ

- 検索 test, def test, class Util s:rb : 2000ファイル程ありますが、インデックス化されているのでかなり高速に検索することが可能です。
- 検索 mygithubの下に移動して class Cli : ディレクトリを移動することで、特定のレポジトリに絞って検索することも簡単です
- さらにGithubアイコンをクリックすると、Githubのレポジトリと行き来することが出来ます。

## ありがとうございました
RubyGemsにアップする予定なので、よかったら使ってみて下さい。

どうもありがとうございました。

