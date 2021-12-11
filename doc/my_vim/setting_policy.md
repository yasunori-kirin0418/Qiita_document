# 始めに

今回は、自分のVimの設定方針のようなものを紹介・解説していきたいと思います。
`.vimrc`や`init.vim`の解説をしたいのですが、何分量が多いので、設定するうえで気にしていることを書いていきたいと思います。

https://github.com/yasunori-kirin0418/dotfiles/tree/master/.vim

まだまだ未熟な設定ばかりですが、自分はdotfilesの`.vim`内に設定をまとめてますので、合わせて読んでいただければ幸いです。


## ディレクトリ構造

自分がVimの設定ファイルを配置する際に気にしているのは、ディレクトリの名前で何を管理しているのか分りやすくすることです。

ディレクトリ名,説明
`rc/`,起動時に必ず読み込まれる設定ファイル。
`toml/`,dein.vimで使用する、toml形式のプラグインを管理しているファイル。
`plugins`,コード量の大目なプラグインの設定ファイル。基本的にはプラグイン名でファイルを作成する。

`.vim`を開いて最初に見えるファイルは、`init.vim`と`ginit.vim`だけにしています。